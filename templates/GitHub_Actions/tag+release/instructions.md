# Descrição

Estes 2 arquivos de workflow realizam a criação de uma tag e de uma release, baseados em um pull de um branch específico.

## Instruções

### Crie um Token de Acesso Pessoal (PAT)

Crie um Token de Acesso Pessoal chamado 'REPO_GHA_PAT' acessando as [configurações de criação de Token (classic)](https://github.com/settings/tokens/new).
Lembre-se de conceder uma data de expiração válida (ou duração permanente). Necessita apenas marcar "public_repo" para repositórios públicos, ou "repo" para os privados.
Anote o valor do Token.

### Crie um segredo dentro do repositório

Vá na lista de segredos do seu repositório ('https://github.com/<NOME_DO_USUARIO>/<NOME_DO_REPOSITORIO>/settings/secrets/actions') e crie um novo segredo.
O nome do segredo será 'REPO_GHA_PAT' e o valor será o valor do Token do tópico anterior.

## Funcionamento dos workflows

Todos os workflows (exceto o último) devem ter, em último step, o seguinte snippet:

```yaml

- name: Trigger next workflow
    if: "success()"
    uses: peter-evans/repository-dispatch@v1
    with:
        token: ${{ secrets.REPO_GHA_PAT }}
        repository: ${{ github.repository }}
        event-type: actions-release
        client-payload: '{"ref": "${{ github.ref }}", "sha": "${{ github.sha }}"}'

```

Na linha `event-type`, coloque o nome do próximo evento (no exemplo, 'actions-release').

O ÚLTIMO workflow deve ter como primeiro parâmetro condicional para sua execução, a propriedade `repository_dispatch`, inserindo o valor conforme abaixo:

```yaml

on:
  repository_dispatch:
    types: [actions-release]

```

Onde 'actions-release' é o valor do trigger contido no workflow anterior.

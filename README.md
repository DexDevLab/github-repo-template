<div align="center">
<img src="./assets/thumb.jpg" height='300px' width='600px' alt="thumb">
</div>

<h1 align="center">Github Repository Template</h1>
<p align=center><i align="center">Template de Repositório do Github com arquivos essenciais e modelos customizáveis</i></p>

<br>

<div align="center">

<a href="https://www.markdownguide.org"><img src="https://img.shields.io/badge/Markdown-%23000000.svg?logo=markdown&logoColor=white" height="22" alt="Markdown"/></a>
<a href="https://docs.github.com/pt/actions"><img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=plastic&logo=githubactions&logoColor=white" height="22" alt="GithubActions"/></a>

<a href=""><img src="https://img.shields.io/badge/maintenance-actively--developed-brightgreen.svg" height="22" alt="Maintenance-actively-developed"/></a>
<a href=""><img src="https://img.shields.io/github/last-commit/dexdevlab/github-repo-template" height="22" alt="LastCommit"></a>
<a href=""><img src="https://snyk.io/test/github/dexdevlab/github-repo-template/badge.svg" height="22" alt="Snyk"/></a>

<a href=""><img src="https://img.shields.io/github/repo-size/dexdevlab/github-repo-template" height="22" alt="RepoSize"/></a>
<a href=""><img src="https://img.shields.io/github/languages/code-size/dexdevlab/github-repo-template" height="22" alt="CodeSize"/></a>
<a href=""><img src="https://img.shields.io/github/contributors/dexdevlab/github-repo-template" height="22" alt="Contributors"></a>

<a href=""><img src="https://img.shields.io/github/forks/dexdevlab/github-repo-template" height="22" alt="Fork"></a>
<a href=""><img src="https://img.shields.io/github/v/release/dexdevlab/github-repo-template" height="22" alt="Version"/></a>
<a href="https://github.com/dexdevlab/github-repo-template/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dexdevlab/github-repo-template?&" height="22" alt="License"></a>

|| [Conteúdo](#section-conteudo) || [Instruções](#section-instrucoes) || [Notas de versão](#section-changelog) ||

|| [Autores](#section-autores) || [Contato](#section-contato) || [Licença](#section-licenca) ||

</div>

<hr>

<a name="section-conteudo">

## Conteúdo

</a>

<br>

Este repositório tem como objetivo apresentar um template para criar facilmente a estrutura básica de qualquer repositório com o mínimo de documentação, organização e automação possíveis, respeitando as regras essenciais de linting e os critérios para manipular os dados de um repositório.
Além disso, contém referências para badges, arquivos de licença e modelos de README, bem como scripts de automação do GitHub Actions para facilitar o trabalho do desenvolvedor durante a publicação e organização das versões e releases.

<hr>

<a name="section-instrucoes">

## Instruções

</a>

<br>

### Utilizando o repositório como projeto para testar templates e scripts

1 - Faça um git clone ou o download do repositório, da forma que preferir

```bash

git clone https://github.com/dexdevlab/github-repo-template.git

```

<br>

### Testando os scripts do GitHub Actions

Você pode testar qualquer script contido no diretório ['GitHub Actions']('https://github.com/dexdevlab/github-repo-template/blob/main/templates/GitHub_Actions') colando o template
desejado em ['.github/workflows'](https://github.com/dexdevlab/github-repo-template/blob/main/.github/workflows) e poderá ver seu funcionamento no próximo commit que você aplicar no
seu repositório clonado.

<br>

### Configuração mandatória para executar os scripts

É obrigatório realizar este ajuste em qualquer repositório onde deseja que seu workflow funcione, para se certificar de que ele tenha as permissões necessárias para executar suas etapas.

Vá nas Configurações Gerais de Ações do repositório (`<https://github.com/><NOME_DO_USUARIO>/<NOME_DO_REPOSITORIO>/settings/actions`) e faça os seguintes ajustes:

1 - Marque 'Allow all actions and reusable workflows' em 'Actions permissions'

2 - Marque 'Read and write permissions' em 'Workflow permissions'

<hr>

<a name="section-changelog">

## Notas de versão

</a>

<br>

### v2.0.0-240307

- Adição dos scripts do GitHub Actions e atualização de sintaxe dos mesmos
- Atualização da documentação
- Adição de scripts de limpeza do Yarn
- Adição de script de limpeza do Git para arquivos que continuam sendo monitorados mesmo depois de desmarcados
- Atualização do gitignore, que também pode ser usado como template
- Alteração do badge de versão e release
- Atualização no template de licenças e readme
- Alteração da sintaxe do script do GitHub Actions

### v1.2.1-230412

- Atualização da documentação

### v1.2.0-230412

- Alteração do estilo dos badges

### v1.1.0-230411

- Inclusão de espaço para thumbnail com centralização e ajustes de tamanho e proporção
- Atualização da documentação

### v1.0.4-230310

- Atualização da documentação

### v1.0.3-230309

- Atualização da documentação

### v1.0.2-230309

- Atualização da documentação

### v1.0.1-230309

- Ajuste no estilo de layout dos badges

### v1.0.0-230309

- Publicação do repositório.

<hr>

<a name="section-autores">

## Autores

</a>

<br>

<a href="https://github.com/dexdevlab/github-repo-template/graphs/contributors">
  <img alt= 'contrib' src="https://contrib.rocks/image?repo=dexdevlab/github-repo-template" />
</a>

<hr>

<a name="section-contato">

## Contato

</a>

<br>

Se você gostou deste projeto, dê uma <a href="https://github.com/dexdevlab/github-repo-template" data-icon="octicon-star" aria-label="Star dexdevlab/github-repo-template on GitHub">estrela</a>. <br>
Para contato, envie um email a: <a href="mailto:dex.houshi@hotmail.com">dex.houshi@hotmail.com</a>

<hr>

<a name="section-licenca">

## Licença

</a>

Licenciado sob a [MIT License](https://github.com/dexdevlab/github-repo-template/blob/main/LICENSE).

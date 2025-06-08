<div align="center">
<img src="./assets/thumb.png" height='300px' width='600px' alt="thumb">
</div>

<h1 align="center">github-repo-template</h1>
<p align=center><i align="center">Template de repositório para o Github</i></p>

<br>

<div align="center">

<a href="https://www.w3.org/Style/CSS/Overview.en.html"><img src="https://img.shields.io/badge/CSS3-%231572B6.svg?logo=css3&logoColor=white" height="22" alt="CSS3"/></a>&nbsp;
<a href="https://html.com"><img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?logo=html5&logoColor=white" height="22" alt="HTML5"/></a>&nbsp;
<a href="https://sass-lang.com"><img src="https://img.shields.io/badge/SASS-hotpink.svg?logo=SASS&logoColor=white" height="22" alt="SASS"/></a>&nbsp;
<a href="https://www.javascript.com"><img src="https://img.shields.io/badge/JavaScript-%23323330.svg?logo=javascript&logoColor=%23F7DF1E" height="22" alt="JavaScript"/></a>&nbsp;
<a href="https://www.java.com/pt-BR/"><img src="https://badges.aleen42.com/src/java.svg" height="22" alt="Java"/></a>
<br>
<a href="https://nodejs.org/en/"><img src="https://img.shields.io/badge/Node.js-6DA55F?logo=node.js&logoColor=white" height="22" alt="NodeJS"/></a>&nbsp;
<a href="https://getbootstrap.com"><img src="https://img.shields.io/badge/Bootstrap-%23563D7C.svg?logo=bootstrap&logoColor=white" height="22" alt="Bootstrap"/></a>&nbsp;
<a href="https://jquery.com"><img src="https://img.shields.io/badge/JQuery-%230769AD.svg?logo=jquery&logoColor=white" height="22" alt="jQuery"/></a>&nbsp;
<a href="https://gulpjs.com"><img src="https://img.shields.io/badge/Gulp-%23CF4647.svg?logo=gulp&logoColor=white" height="22" alt="Gulp"/></a>&nbsp;
<a href="https://babeljs.io"><img src="https://img.shields.io/badge/Babel-F9DC3e?logo=babel&logoColor=black" height="22" alt="Babel"/></a>
<br>
<a href=""><img src="https://img.shields.io/badge/maintenance-actively--developed-brightgreen.svg" height="22" alt="Maintenance-actively-developed"/></a>&nbsp;
<a href=""><img src="https://img.shields.io/github/last-commit/dexdevlab/github-repo-template" height="22" alt="LastCommit"></a>&nbsp;
<a href=""><img src="https://img.shields.io/github/v/release/dexdevlab/github-repo-template" height="22" alt="Version"></a>&nbsp;
<a href=""><img src="https://snyk.io/test/github/dexdevlab/github-repo-template/badge.svg" height="22" alt="Snyk"/></a>&nbsp;
<br>
<a href=""><img src="https://img.shields.io/github/repo-size/dexdevlab/github-repo-template" height="22" alt="RepoSize"/></a>&nbsp;
<a href=""><img src="https://img.shields.io/github/languages/code-size/dexdevlab/github-repo-template" height="22" alt="CodeSize"/></a>&nbsp;
<a href=""><img src="https://img.shields.io/github/contributors/dexdevlab/github-repo-template" height="22" alt="Contributors"></a>&nbsp;
<a href="https://github.com/dexdevlab/github-repo-template/blob/main/LICENSE"><img src="https://img.shields.io/github/license/dexdevlab/github-repo-template" height="22" alt="License"></a>&nbsp;

</div>

<br>

## Conteúdo

Este repositório tem como objetivo apresentar um template para criar facilmente a estrutura básica de qualquer repositório com o mínimo de documentação, organização e automação possíveis, respeitando as regras essenciais de linting e os critérios para manipular os dados de um repositório.

- Lorem ipsum dolor sit amet;

<br>

## Documentação

- [Lorem](https://miro.com/app/board/uXjdfgsdgVPWCiaDo=/?share_link_id=713196550342)

Documentação adicional pode ser encontrada [aqui](https://dexdevlab.github.io/github-repo-template/).

<br>

## Instruções

### Utilizando o repositório como projeto

1 - Faça um git clone ou o download do repositório, da forma que preferir

```bash
git clone https://github.com/dexdevlab/github-repo-template.git
```

### Variáveis de Ambiente

Para usar a aplicação, crie um arquivo '.env' com as seguintes variáveis de ambiente:

| Variável      | Uso   | Tipo | Valor Padrão |
|---------------|-------|-------|-------------|
|`DATABASE_URL` | Lorem ipsum dolor sit amet | String | "lorem ipsum" |

### Testes de API

#### Método GET

Fornece a lista de Pokémon.

```json
// http://localhost:3000/
[
  {
    "_id": 0,
    "pid": 83,
    "name": "Farfetch'd",
    "evolution": 1
  },
  {
    "_id": 1,
    "pid": 304,
    "name": "Aron",
    "evolution": 1
  },
  {
    "_id": 2,
    "pid": 158,
    "name": "Totodile",
    "evolution": 1
  },
  {
    "_id": 3,
    "pid": 1008,
    "name": "Miraidon",
    "evolution": 1
  }
]
```

#### Método PUT

Modifica um Pokémon da lista, baseado no ID contido no Banco de Dados

Query Params:

| Parâmetro | Valor | Tipo | Exemplo |
| --- | ----------- |-------|--------|
| id | ID do Pokémon contido no Banco de Dados.| Number | 2 |

Body (JSON):

Adicione no corpo os valores a serem modificados, mas não suprima nenhum dos campos.

```json
// http://localhost:3000/update-pokemon/:id
{
  "pid": 84,
  "name": "Farfetch'd",
  "evolution": 1
}
```

<br>

## Notas de versão

### v1.0.0-221208

- Lorem ipsum dolor sit amet;

### v0.0.34-221208

- Lorem ipsum dolor sit amet;

### v0.0.33-220916

- Lorem ipsum dolor sit amet;

<br>

## Autores

<a href="https://github.com/dexdevlab/github-repo-template/graphs/contributors">
  <img alt="authors" src="https://contrib.rocks/image?repo=dexdevlab/github-repo-template" />
</a>

<br>

## Contato

Se você gostou deste projeto, dê uma <a href="https://github.com/dexdevlab/github-repo-template" data-icon="octicon-star" aria-label="Star dexdevlab/github-repo-template on GitHub">estrela</a>. <br>
Para contato, envie um email a: <a href="mailto:dex.houshi@hotmail.com">dex.houshi@hotmail.com</a>

<br>

## Licença

Licenciado sob a [MIT License](https://github.com/dexdevlab/github-repo-template/blob/main/LICENSE).

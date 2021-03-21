# Folha de Estilo

## Histórico de Revisão
|Data|Versão|Descrição|Autor(es)|
|---|---|---|---|
|14/03/2021|0.1| Adicionado eslint/prettier | Philipe Serafim |
|21/03/2021|0.2| Adicionado Pylint          | Wesley Santos |

<br>

## Sumário
[1. Introdução]()   

[2. Lint]()   

[2.1 Eslint/Preetier]()  

[2.1.1 Configuração do Eslint/Prettier]()

[3. Padrão de escrita e commits]()   

[Referências]()

## 1. Introdução


## 2. Lint
De modo geral, lint é um programa que checa um código **estático** procurando possíveis erros comuns e de estética do código. O uso de um programa lint permite a padronização da escrita e indentação do código produzido em equipe.

## 2.1 ESLint/Preetier
ESLint é um dos programas linters utilizados para a linguagem ReactJS, enquanto o Preetier é uma extenção do VS Code que produz *warnings* relacionados à estilística do código. 

Utilizar Eslint e Preetier, em conjunto, possibilita que o *linter* faça uma checagem do código enquanto ele é escrito e ao ser salvo.

### 2.1.1 Configuração do Eslint/Prettier
Está sendo utilizado o Eslint-Airbnb, a configuração mais recomendada para React. Para utilizar Prettier em conjunto com linter é necessário especificar o plugin.

``` js
module.exports = {
  env: {
    browser: true,
    es2021: true,
  },
  extends: ["airbnb-base", "prettier"],
  parserOptions: {
    ecmaFeatures: {
      jsx: true,
    },
    ecmaVersion: 12,
    sourceType: "module",
  },
  plugins: ["prettier", "react"],
  rules: {
    "prettier/prettier": "error",
    "no-param-reassign": "off",
    "class-methods-use-this": "off"
  },
};
```

Também é possível especificar as regras de estilística através do arquivo de configuração do Prettier.

```json
{
  "trailingComma": "es5",
  "useTabs": false,
  "tabWidth": 4,
  "semi": true,
  "singleQuote": true
}
```
Vale ressaltar que as regras especificadas manualmente podem sobrescrever as utilizadas pelo padrão Eslint-Airbnb, fungindo do padrão escolhido e do objetivo do programa linter.


## 2.2 Pylint 

Pylint é um verificador de bugs que auxilia o desenvolvedor a manter a padronização do código, mantê-lo coeso. Seguindo a PEP-8 que são as definições de padrões de desenvolvimento dentro da linguagem Python. Definições como boas práticas de linhas de comando, importações de módulos, classes, arquitetura de projetos web, erros de sintaxe, e também a verificação de uma possível refatoração no código. É altamente configurável, tendo programas especiais para controlar seus erros e avisos de dentro do código.


## 3. Padrão de escrita e commits

Foi determinado que o código deveria ser escrito em inglês enquanto os commits deveriam ser escritos em PT-BR e no particípio, como por exemplo:

> Adicionado component Home do frontend

> Atualizado documento de arquitetura

## Referências

* [Lint. O que é isso afinal?](https://medium.com/@emerson_pereira/lint-o-que-%C3%A9-isso-afinal-83b3dc0dec59)

* [ESLint](https://eslint.org/docs/user-guide/getting-started) 

* [Prettier](https://prettier.io/docs/en/install.html)

* [Pylint](https://pypi.org/project/pylint/) 

* [PEP](https://www.python.org/dev/peps/pep-0008/) 
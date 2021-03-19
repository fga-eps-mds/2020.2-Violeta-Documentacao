# Documento de Arquitetura de Software


## Histórico de Revisão
|Data|Versão|Descrição|Autor(es)|
|---|---|---|---|
|08/03/2021|0.1|Adicionado template do documento| Victor |
|18/03/2021|0.2||Philipe Serafim|



## Sumário
[1. Introdução]()   

[1.1 Objetivo]()   

[1.2 Escopo]()   

[1.3 Definições, Acrônimos e Abreviações]()   

[1.4 Referências]()   

[1.5 Visão Geral]()   

[2. Representação Arquitetural]()   

[2.1 API]()   

[2.1.1 Frontend]() 

[2.1.2 Questionário]() 

[2.1.3 Depoimentos]() 

[2.1.4 Frases]() 

[2.1.5 Autenticador]() 

[2.2 Framework ReactJs]()   

[2.3 Framework Django]()   

[2.4 Banco de Dados]()   

[3. Restrições e Metas Arquiteturais]()   

[4. Visão Lógica]()   

[5. Visão de Implementação]()   



## 1. Introdução

## 1.1 Objetivo
Este documento disponibiliza uma visão arquitetural do sistema, usando algumas visões de arquitetura para representar os diferentes aspectos do sistema. Ele pretende evidenciar decisões arquiteturais significativas tomadas em relação ao sistema.

## 1.2 Escopo
Por meio deste documento, será possível entender o funcionamento do sistema do aplicativo web Violeta, bem como a metodologia do seu desenvolvimento. Desse modo, será possível ter uma compreensão da arquitetura do projeto.

## 1.3 Definições, Acrônimos e Abreviações
- UnB: Universidade de Brasília
- FGA: Faculdade do Gama - Campus da Universidade de Brasília
- API: Application Programming Interface (Interface de Programação de Aplicativos)

## 1.4 Referências

## 1.5 Visão Geral
|**Tópico**|**Definição**|
|---|---|
|Introdução|Descreve informações sobre este documento.|
|Representação Arquitetural|Detalha a arquitetura de software utilizada para melhor compreensão de sua estrutura e funcionamento.|
|Metas e Restrições|Descreve os requisitos e objetivos do software e seus impactos na arquitetura.|
|Visão Lógica|Detalha componentes e escolhas relevantes ligadas à arquitetura do projeto.|
|Visão de Implementação|**FALTANDO**|


## 2 Representação Arquitetural
A arquitetura do Violeta é composta por cinco microsserviços que são executados em contêineres individuais através do Docker. Os microsserviços são divididos em dois grupos,  backend e frontend, que comunicam-se através de rotas http.
![arquitetura](../img/diagrama_de_arquitetura.png)

Desse modo, os serviços são executados isolados evitando comportamentos inesperados, como por exemplo, serviços acessando recursos que não deveria. 

## 2.1 API

### 2.1.1 Frontend

### 2.1.2 Questionário

### 2.1.3 Depoimentos

### 2.1.4 Frases

### 2.1.5 Autenticador

## 2.2 Framework ReactJs
É um framework de código aberto voltado para a aplicação de criação de páginas web. A mesma se utiliza de HTML, CSS e JavaScript para ser aplicada. Por meio destes é possível desenvolver interfaces divididas em componentes reutilizáveis. No Violeta essa tecnologia é aplicada seguindo um layout de landing Page.

## 2.3 Framework Django
O framework Django é um forma de aplicação web gratuita e de código aberto escrito em Python. Seguindo o princípio DRY (Don't Repeat Yourself). Permitindo assim otimizar ainda mais a fase de desenvolvimento.
No Violeta o Django é aplicado através do Django REST framework para viabilizar os micro serviços presentes no projeto por meio de API’s.

## 2.4 Banco de Dados
O banco de dados do projeto é gerenciado pelo PostgreSQL. O PostgreSQL é um sistema de gerenciador de bancos de dados de código aberto com mais de 30 anos de constante desenvolviemento. O desenvolvimento ativo trouxe consigo história e confiança no mercado acarretando assim credibilidade. 

## 3. Restrições e Metas Arquiteturais
 A partir da Lean-inception feita pela equipe, foi tomado o levantamento de restrições para o desenvolvimento do software e o usuário destino. Sendo assim, para melhor atender os requisitos definidos e utilizar das melhores tecnologias disponíveis, foram selecionadas as metas e restrições de arquitetura.
 
### 3.1 Metas
 As metas arquiteturais definem como o sistema precisa responder às mudanças ao longo do tempo, direcionadas pelos requisitos de software. Por tanto, a usabilidade da aplicação estará presente para o cumprimento de seu objetivo, acessada pelos navegadores. A eficiência da WebApp irá conceder os dados e suas informações de forma clara e rápida ao usuário, para que assim possa gerenciar e acompanhar os processos de forma consistente.

### 3.2 Restrições 
 As restrições do projeto estão relacionadas às ferramentas e tecnologias escolhidas para o desenvolvimento do software.     
    - Django: Web Framework baseada em Python;
    - Django Rest Framework: caixa de ferramentas e API's para o Django;
    - Python: Linguagem utilizada no Django;
    - Java Script: Linguagem utilizada, em conjunto com o HTML e CSS, para desenvolvimento WEB;
    - HTML: Linguagem base utilizado em desenvolvimento WEB;
    - CSS: Linguagem usada em conjunto HTML para estilizar a página;
    - Docker: Plataforma open source que facilita a criação e administração de ambientes isolados;
    - PostgreSQL: Sistema gerenciador de banco de dados objeto relacional;
    - ReactJS: Biblioteca JavaScript declarativa, eficiente e flexível para a criação de interfaces de usuário 
 
 Além disso, existem restrições operacionais referentes à aplicação devido a vários fatores, tais como:

    - Topologia de rede
    - Ambiente WEB (configurações de servidor, firewall, dmzs, etc.)
    - Servidores (modelo de hardware, sistema operacional)

## 4. Visão Lógica

### 4.1 Visção Geral
O Violeta é uma aplicação WebApp composta da linguagem JavaScrip juntamente com o framework Reactjs como forma de implementação do front-end seguido do auxiolio de HTML e CSS para maior fidelidade do prototipo. Na que se refere ao back-end a linguagem python juntamente com framework Django voltado para modelagem de dados. Os dados seram armazenados é gerenciados pelo framework PostgreSQL. O PostgreSQL possibilida que depoimentos e as arvores de decisão seão salvas de forma pratica e eficiente.

## 5. Visão de Implementação


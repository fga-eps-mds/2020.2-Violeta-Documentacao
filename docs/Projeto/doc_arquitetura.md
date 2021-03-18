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

## 2.3 Framework Django

## 2.4 Banco de Dados

## 3. Restrições e Metas Arquiteturais

## 4. Visão Lógica

## 5. Visão de Implementação


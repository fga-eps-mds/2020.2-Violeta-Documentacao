# Gerenciamento de Risco

### Histórico da Revisão
| Data | Versão | Descrição | Autor |
|---|---|---|---|
| 17/05/2021| 0.1 |Criação do documento | Ana Carolina Carvalho |
| 25/05/2021| 0.1 |Atualizando os links | Ana Carolina Carvalho |

## Documento de gerenciamento de risco

O gerenciamento dos riscos do projeto inclui os processos de condução do planejamento, identificação, análise, planejamento de respostas, implementação das respostas e monitoramento dos riscos em um projeto.

Ocorre que durante a elaboração e desenvolvimento de software, podem ocorrer muitos problemas. Precisamos estar prontos para esse tipo de situação e ter uma resposta rápida. A fim de evitar desperdício, atrasos e prejuízo. Esses problemas podem abranger diversos aspectos do produto e do projeto. E tais problemas podem vir a impactar o resultado final do produto, abalar o time, além de aspectos do projeto como os prazos estipulados.

## Método

### Identificação dos riscos

Para identificar os riscos do projeto o time aproveitou um pareamento para discutir possíveis eventos que podem atingir o projeto de forma negativa. Com o time de EPS orientando MDS. Como a maioria do time ainda não havia mapeado riscos ou participado de grandes projetos, levamos em conta a realidade e consideramos eventos de risco tarefas bem próximas de seu dia a dia.

### Métricas

Para metrificar todos os riscos identificados pelo time do projeto, utilizaremos o burndown de riscos, sendo este um artefato ágil, o burndown mostra o quão relevante um risco é ao decorrer das sprints e nos mostra se os riscos estão aumentando ou diminuindo no decorrer do desenvolvimento. 

Levando em consideração que alterações no escopo, saída de participantes, problemas nos equipamentos no final do projeto tem muito mais impacto, já que o prazo para entrega está mais próxima, fica difícil replanejar as tarefas, fica mais custoso refatorar.

Para se saber metificar o quão relevância é o risco, será necessário estipular a o impacto e a probabilidade do risco acontecer. Ambos terão um intervalor de 0 a 5. 

E a relevância do risco no projeto é calculada como Probabilidade x Impacto (P*I).

- Probabilidade: A probabilidade representa a chance (%) desse risco ocorrer, tal indicação é feita em cada sprint.

- Impacto: O impacto representa o prejuízo que cada risco oferece ao projeto caso ocorra.

O resultado estará apresentado no gráfico do burndown de risco, onde mostra como se comporta essa métrica de risco no decorrer das sprints do projeto.

Nas tabelas abaixo, foram representados como foram feitas as estimações de cada fator e o que ela representa.

|Probabilidade|Descrição|Valor|
|--|--|--|
|Nenhum|Nenhuma chance de acontecer|0|
Raro|Menor que 20% de chance de acontecer|1|
Improvável|Entre 21% e 40% de chance de acontecer|2|
Pouco Provável|Entre 41% e 60% de chance de acontecer|3|
Provável|Entre 61% e 80% de chance de acontecer|4|
Muito provável|Entre 81% e 100% de chance de acontecer|5|

<br>

|Impacto|Descrição|Valor|
|--|--|--|
|Nenhum|Nenhum impacto|0|
Baixíssimo|Pouquíssimo impactos ao projeto|1|
Baixo|Impacto pequeno ao projeto|2|
Médio|Impacto que começa a apresentar algumas consequências ao projeto|3|
Alto|Impacto que compromete o andamento do projeto|4|
Altíssimo|Impacto que paraliza o projeto caso não seja resolvido|5|

## Burndown de Riscos

Os riscos foram categorizados pela equipe em relação à **Probabilidade** e **Impacto**, como já dito mais acima no documento, e em uma planilha atualizada toda sprint do projeto. 

<iframe width="957" height="591" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ3RZt8eVxtcDjPJdVDlRGNyTrfQ8p2OuYU3PIqy8JbTTeeamSvOL9yilIHkCJjU1sxvVo5as4muZL7/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

Com essa pontuação é feito o gráfico de Burndown de Riscos. Onde podemos ver o indicador se os riscos estão aumentando ou abaixando, quais sprints apresentam ou apresentaram maior risco para o projeto.

<iframe width="654" height="412" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ3RZt8eVxtcDjPJdVDlRGNyTrfQ8p2OuYU3PIqy8JbTTeeamSvOL9yilIHkCJjU1sxvVo5as4muZL7/pubchart?oid=1162260752&amp;format=interactive"></iframe>

Acumulando todos os riscos do projeto por sprint. E mapeamos o individual de cada risco também na planilha a seguir. Com essas informações, verificamos se a equipe está conseguindo lidar com os riscos de forma eficaz e se estamos sendo eficientes, observando se os valores dos riscos estão diminuindo individualmente e quais são os maiores riscos por sprint e assim mitiga-lo antes que ele ocorra.

<iframe width="957" height="591" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ3RZt8eVxtcDjPJdVDlRGNyTrfQ8p2OuYU3PIqy8JbTTeeamSvOL9yilIHkCJjU1sxvVo5as4muZL7/pubhtml?gid=1563957406&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

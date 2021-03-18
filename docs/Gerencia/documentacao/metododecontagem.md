## Método de contagem

### Histórico da Revisão
| Data | Versão | Descrição | Autor |
|---|---|---|---|
| 14/03/2021| 1.0 |Criação do documento | Ana Carolina Carvalho |
| 16/03/2021| 1.0 |Métricas | Ana Carolina Carvalho |
| 17/03/2021| 1.0 |Métricas no projeto | Ana Carolina Carvalho |

## Métricas

Métricas de software são parâmetros para a medição do desempenho do software, mas não apenas desempenho em tempo de execução. A métrica é o padrão de medida que um sistema ou processo de uma dada propriedade. Por mais que uma métrica não seja exatamente uma medida, os termos acabam sendo usados como sinônimos, já que estão diretamente relacionados.
No processo de engenharia de software, que é nosso contexto, as métricas podem ser diretas ou indiretas. 
As métricas diretas são aquelas obtidas diretamente de um dado e não a partir de um conjunto de métricas, melhor explicado mais a frente, as diretas são o custo e o esforço aplicado ao desenvolvimento e sustentação do software e produto gerado a partir. Outros exemplos são a quantidade de linhas de código, LOC, ou o total de defeitos "bugs" que surgiram em um determinado período de tempo. 
As tarefas do projeto Violeta utilizam uma métrica direta para medir o tempo que cada card no board leva para ser concluída. 
Diferente das métricas diretas, as métricas indiretas só podem ser medidas indiretamente, como por exemplo qualidade, funcionalidade e manutenabilidade. Sendo estas mais difíceis de serem avaliadas. 
O gerenciamento de projetos depende de métricas de software para realizar uma das atividades mais fundamentais, o planejamento. Podendo-se identificar a quantidade de esforço, custo e tempo. 

## Como medir as tarefas no projeto Violeta

No projeto, usamos algumas metodologias ágeis. Adotamos as práticas que fazem mais sentido para o contexto atual do projeto. Dentre as metodologias adotadas, temos o Kanban e o Scrum. Brevemente, o Kanban é um sistema de controle de atividades e gestão de fluxo que utiliza recursos visuais. Já o Scrum é uma metodologia ágil para gestão e planejamento, onde os projetos são dividos em ciclos os quais chamamos de sprints. A sprint é, de forma geral, um time box o qual um conjunto de atividades devem ser executadas.

Algumas métricas do Kanban foram adotadas e validadas junto ao professor responsável pela matéria. Desta forma, iremos documentar quais serão usadas e como elas são levantadas.

### Throughtput
O Throughtput é a quantidade de cards de um quadro no Kanban entregues em um tempo determinado. No nosso caso, em uma sprint e/ou release. Neste momento temos a união do Kanban e Scrum. 
Um detalhe importante é que o Throughtput não leva em consideração o tamanho dos cards. Apenas a vida útil do card/issue.

### Lead Time
O Lead Time leva em consideração todo o tempo que o card permanece ativo no quadro, ou seja, antes dele entrar em 'done'. 
O objetivo desta métrica é justamente considerar a percepção do gestor em relação ao tempo que o time leva pra executar determinadas tarefas. A ideia do time é, a partir desta, prever o tempo que uma demanda pode levar para ser concluída. A contar do momento que ela saiu do backlog. 

### WIP - Work In Progress
O WIP tem como objetivo contabilizar a quantidade de cards que o time trabalha em simultaneo. No nosso projeto, determinamos que uma pessoa não deve se comprometer a trabalhar em mais de 3 tarefas paralelamente. Que é uma prática muito comum do Kanban. 
É perceptível que, quanto mais issues são trabalhadas em simultâneo mais tempo se leva para entregar cada uma dessas issues. 

## Como está aplicado

No momento, no rito de Planning, priorizamos as tarefas que foram definidas para aquela sprint, de acordo com a onda correspondente feita no Lean Inception, após todas as tarefas priorizadas, realizamos um planning poker. 

Nosso planning poker não é feito com a contagem tradicional de história de usuário. Nós utilizamos o Lead Time. O time prevê, com base em sprints anteriores, quanto tempo a issue deve demorar para ser concluída. 

O Scrum Master acompanha o WIP do time, para que não aconteça um engarrafamento de atividades.

Ou seja, pontuamos nossas issues em dias. Quantos dias são necessários para realizar uma tarefa X.
Por conta disso, na produção do nosso EVM, o custo está atrelado a quantidades de dias que o time levou para desenvolver as tarefas propostas. 

Em relação a nossa documentação, cada artefato feito é pontuado com 1 dia. Entendemos que tempo e pessoas foram destinadas a tal tarefa, por este motivo, houve custo e deve ser considerado no cálculo final.


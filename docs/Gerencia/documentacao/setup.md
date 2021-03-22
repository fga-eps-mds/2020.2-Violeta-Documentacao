## Setup 

### Histórico da Revisão
| Data | Versão | Descrição | Autor |
|---|---|---|---|
| 18/03/2021| 0.1 |Criação do documento | Ana Carolina Carvalho |

## Documento de início de projeto

A finalidade deste documento é de registrar as primeiras e principais decisões do time Violeta.

### Apresentação do time de EPS e MDS
Apresentação dos membros e alinhamento de expectativas quanto as disciplinas de MDS e EPS. Nesta reunião, o time de EPS se apresentou para o time de MDS e alinhou as expectativas, apresentou a proposta da disciplina e definiu alguns combinados. 
Dentre os combinados estão: 

1. Transparência na comunicação;</br>
2. Abertura para a tirada de dúvidas;</br>
3. Comprometimento nas entregas;</br>
4. Disponibilidade dos finais de semana;</br>
5. Feedbacks contínuos.</br>

### Definir tema do projeto
Definir qual será o tema do projeto junto ao professor Hilmer. Neste momento, alguns temas foram lenvatados com base nos cards da ONU.
<br><b>Card 3:</b> Saúde e Bem-Estar: Aplicativo de monitoramento e melhoria de hábitos </br>
<b>Card 4:</b> Educação de Qualidade: Plataforma de aulas da UnB </br>
<b>Card 8:</b> Trabalho decente e crescimento econômico: Plataforma de publicação de vagas de empregos </br>

Nenhum desses temas teve a aprovação do professor, por este motivo, novos temas foram levatados: 

1. Um webapp onde coloca o tipo de planta que você tem e vai marcando os sintomas e ele dá uma parcial do que pode ser o problema com sua Planta.

2. Aplicativo onde a mulher coloca todos os aspectos que aconteceram com ela depois dela sentir que foi violentada ou injustiçada de alguma forma. Ali ela preenche todas as etapas do formulario e ao final o webapp dá o veredito juridico das coisas que ela pode fazer e o caminho a recorrer.

3. Webapp que mostra todas as micro e pequenas empresas próximas para incentivar a produção e mercado local.

A ideia aprovada pelo professor foi o tópico 2 da segunda rodada de sugestões. Foi essa a inspiração para o escopo do projeto Violeta.

### Definir tecnologia usada no projeto
Definir com os times de EPS e MDS qual tecnologia se encaixa no projeto. Quais tecnologias atendem as necessidades do escopo.

Após decidirmos qual seria o escopo do projeto pudemos pensar em qual tecnologia se encaixaria nas nossas necessidades de desenvolvimento. Além de levar em consideração o requisito de microsserviços levantado pelo professor da matéria. 

Neste momento, ainda não era a hora de criar o documento de arquitetura. Apenas escolhemos quais linguagens seriam usadas, até mesmo para o time de MDS já ir estudando e o time de EPS preparar Dojos.

Por isso, para o back-end, escolhemos Django REST para a construção da nossa API. O Django Rest Framework (DRF)é uma biblioteca para o Framework Django que disponibiliza funcionalidades para implementar APIs Rest de forma extremamente rápida.
Para o front-end, escolhemos React JS. O React, que também é conhecido como React.js ou ReactJS, é uma biblioteca JavaScript opensource com foco em criar interfaces de usuário em páginas web.

O tema é melhor abordado no documento de arquitetura.

### Definir ritos de metodologia ágil
Definir qual ou quais frameworks ágeis usar e quais ritos aplicar com o time durante o decorrer da disciplina.

Os métodos ágeis são uma abordagem de modelo de gestão que diferente do tradicional, onde tínhamos o desenvolvimento de um produto divido por etapas bem definidas e inflexíveis, o ágil se organiza em iterações curtas, onde o produto é constantemente incrementado e o resultado é medido conforme essas entregas. 

Em outro documento abordaremos melhor as metodologias ágeis. Num geral, escolhemos usar abordagens do XP (Extreme Programming), Kanban, Scrum e Lean Inception. Além disso, o Lean também foi aplicado, sendo este um conceito. Ainda sobre o Lean, ele não pode ser considerado simplesmente como uma metodologia ágil. Seria mais preciso classificá-lo como uma filosofia que foi aplicada na construção de metodologias como o Agile e o Kanban.

<b>Do XP adotamos:</b></br>

- Programação pareada (pair programming): o desenvolvimento do código feito em duplas, preferencialmente composta por alguém pouco mais experiente e outra pessoa sem experiência, no mesmo computador. No nosso caso, as duplas estão sendo alteradas toda sprint.</br>
- Padronização do código (coding standards): o time de desenvolvimento de MDS definiu padrões para a construção do código, pois isso fará com que o código fique uniformizado e mais compreensível. Para isso foi criado uma folha de estilo do projeto.</br>
- Integração contínua (continuous integration): depois que uma funcionalidade for testada ela deve ser imediatamente sincronizada entre a equipe, evitando conflitos.</br>
- Design simples (simple design): entregar apenas o que o cliente pediu, em vez de tentar reinventar a roda.</br>
- Jogo de planejamento (planning game): priorizar quais funcionalidades serão desenvolvidas antes de cada ciclo, também realizamos a pontuação da tarefa neste momento de priorização. O qual chamamos de Planning Poker. </br>
- História de usuário (User Story): Uma história de usuário é uma narrativa escrita sobre a utilização de um sistema na visão de um determinado usuário.</br>

<b>Do Scrum adotamos:</b></br>

-  Sprint: As iterações do Scrum são chamadas de Sprints, ciclos completos de desenvolvimento que percorrem do planejamento à entrega (idealmente), incluindo ainda inspeção e adaptação de processos para garantir a melhoria contínua. </br>
- As cerimônias: </br>
    - Sprint Planning: A Sprint Planning é o rito de planejamento da Sprint, que deve ocorrer no primeiro dia da mesma. Nesta cerimônia defini-se o objetivo da sprint, o escopo de trabalho e alinha-se como que este trabalho será realizado. </br>
    - Daily Meeting: A Daily Scrum é uma cerimônia de alinhamento. Ela possui algumas regras que garantem a sua celeridade, o seu objetivo e ao aproveitamento de todos, são elas:</br>
        - Ela acontece todos os dias;</br>
        - No máximo deve durar 15 minutos e todos devem estar em pé;</br>
        - Sempre acontece no mesmo lugar e no mesmo horário, combinado com todos;</br>
        - cada pessoa tem a sua vez de falar e os demais ouvem;</br>
        - Cada pessoa fala para os demais membros do time, não há um chefe aqui e isso não é uma "prestação de contas";</br>
        - Não discute-se detalhes de nenhuma atividade durante a Daily, apenas depois.</br>
    Daily consiste em cada membro do time responder a apenas três perguntas:</br>
        - o que eu fiz desde a última Daily?</br>
        - o que eu vou fazer depois da Daily?</br>
        - tem algo bloqueando o trabalho?</br>
    - Sprint Review: É a apresentação do trabalho planejado x trabalho realizado e quais serão os próximos passos do Time de Desenvolvimento, alé do que o Product Owner está planejando para a próxima sprint.</br>
    - Sprint Retrospective: A Sprint Retrospective é um rito que deve acontecer sempre no último dia da sprint ou release, no caso da Violeta acontece ao final da Release, para "fechar" a mesma. É uma cerimônia com duração máxima de três horas para cada trinta dias de sprint e é facilitada pelo Scrum Master. Nesta cerimônia que todo o Time Scrum deve participar, o objetivo é analisar tudo o que aconteceu nesta sprint que está encerrando e propor melhorias para a próxima.</br>
- Os papéis:</br>
    - O <b>Product owner</b> é o responsável por gerenciar o backlog do produto, isto é, o conjunto de funcionalidades e características que o produto deve ter.</br>
    - O <b>scrum master</b> é o responsável por disseminar o scrum pela organização, garantindo que ele esteja sendo aplicado de forma correta. Portanto, atua como um facilitador.</br>
    - O <b>development team</b> é a equipe de desenvolvedores responsável por entregar as funcionalidades do produto e o produto final.</br>

Uma importante observação nos papéis do projeto, nosso Scrum Master é, na verdade, um agile coach. Já o Agile Coach é um profissional, que não só entende do framework ágil Scrum, mas como outros frameworks ágeis como, por exemplo, Kanban e XP.</br>

<b>Do Kanban adotamos:</b></br>

- Quadro de status das tarefas. Ele possui 04 princípios: </br>
    - Visibilidade. Deve deixar visível o trabalho em progresso, os limites, as prioridades, atrasos e bloqueios. </br>
    - Fluxo puxado. Comece a terminar e pare de começar, você deve terminar tudo que começa e somente depois iniciará novas tarefas.</br>
    - Colaboração. É necessário que as pessoas colaborem para o andamento das tarefas dentro do fluxo do quadro. </br>
    - Melhoria contínua. Entregas constantes e evolução nas entregas com os feedbacks gerados.</br>
- Cartão. O cartão é a menor parte do kanban. Trata-se de uma tarefa ou ação que precisa ser tomada para que o resultado final seja entregue. </br>
- Colunas. As colunas representam os status dos cartões. Um kanban geralmente possui três colunas: A Fazer, Em Execução e Feito, mas essas colunas podem mudar de acordo com a necessidade da equipe de trabalho. No caso do nosso time, adicionamos o backlog, review, icebox e closed.</br>
- Métricas de contagem para as atividades do projeto.</br>
    - Apresentado no documento de métricas do projeto.</br>

### Quadro de conhecimento
Preparação do quadro de conhecimento que será aplicado ao time de MDS.
O objetivo é o time de EPS compreender o nível de conhecimento em determinadas áreas do time de MDS, podendo criar estratégias e ajudá-los a alcançar o conhecimento necessário para se desenvolver bem no decorrer da disciplina.

Link do quadro de conhecimento: https://docs.google.com/spreadsheets/d/1xdwLbPowugM50JLVIR9dDqhSS_JmXJTy8zT5Fq9tGqU/edit#gid=0

### Criar tabela para acompanhar horas trabalhadas de MDS
Criação de uma planilha para mapear a quantidade de horas que cada membro do time de MDS está dedicando à disciplina.
Tabela foi criada pelo time de MDS

https://docs.google.com/spreadsheets/d/1z720pFwdU7ZzPJK8j9-ugRUWoRUai1vWbkM4DXLDNA4/edit?usp=sharing








# Estudos de caso

Aqui estão listados alguns estudos de caso como exemplo de aplicação do Scrum em diversas situações como:

#### 1. Sistema de gestão de estoque - RU da UFSCar
O estudo de caso foi realizado na Universidade Federal de São Carlos (UFSCar) com o objetivo de apresentar, num contexto de um ambiente acadêmico, a aplicação da metodologia ágil Scrum, descrevendo as atividades realizadas, sua implantação e sua adaptação, destacando os principais desafios, dificuldades, benefícios, e lições aprendidas na aplicação do framework.

Foi proposto o desenvolvimento um sistema que automatizasse os processos de gestão de estoque do Restaurante Universitário (RU) da UFSCar que eram realizados de forma manual. O sistema desenvolvido foi parte do trabalho de conclusão do curso de especialização em desenvolvimento de software para Web ministrado na universidade, tendo como requerimento a aplicação do Scrum.

O time era composto por alunos que não tinham conhecimentos aprofundados do assunto, e por isso antes de iniciar o projeto, disciplinas para compreender essas técnicas foram ministradas. Ao iniciar o projeto algumas adaptações precisaram ser realizadas por se tratar de um ambiente acadêmico, dentre elas podemos destacar:

* Ampliação do período de realização das Sprints, por determinação da coordenação do curso.
* Rotatividade do papel de scrum master, para que cada integrante pudesse lidar com as responsabilidades e aprender sobre esse papel.
* As reuniões presenciais diárias deram lugar, a reuniões semanais realizadas através do Skype.
* As ferramentas utilizadas foram depositadas no google drive, e compartilhadas com os demais integrantes do grupo.
* A comunicação entre a equipe e o Product Owner, foi realizada, em sua maioria, através de e-mails.

Ao longo de 7 Sprints o time desenvolveu o projeto de forma contínua e evolutiva. A cada Sprint o time registrava suas dificuldades e lições aprendidas, e analisando tais registros é possível notar o quanto o time se desenvolveu e aprendeu ao longo do tempo.

Concluiu-se então que a principal contribuição deste trabalho refere-se à identificação de empecilhos e possíveis soluções ao implantar o Scrum, tendo como colaboradores elementos inexperientes no que concerne a abordagem. Foram indicadas situações ocasionadas pela imperícia dos envolvidos, o que pode ser comum a equipes nas mesmas circunstâncias; por conseguinte, determinaram-se alternativas cabíveis a fim de evitar ou contornar os cenários problemáticos.

Projetos futuros podem estender a utilização do framework para outras áreas da universidade, investigando quais os contratempos encontrados e compará-los aos apresentados neste artigo. Além disso, outros pontos relevantes indicados no presente estudo, como o autogerenciamento, a motivação e a inexperiência técnica, podem se tornar objetos de análises para avaliação de produtividade e qualidade de software.

#### 2. Fábrica de Desenvolvimento Distribuído de Software 

O estudo de caso aqui apresentado foi realizado por uma fábrica de desenvolvimento de software open source [O3S 2007]. Esta fábrica é formada por dez alunos do curso de Pós-Graduação do Centro de Informática da Universidade Federal de Pernambuco. Todos os integrantes são do curso de mestrado e fazem parte da estrutura organizacional da fábrica. 

Essa estrutura é composta por um Comitê Gestor, responsável pelas principais decisões estratégicas da Fábrica e cinco Unidades de Produção, cada uma com atribuições bem definidas e complementares, trabalhando
juntas com os clientes e a comunidade externa. O projeto executado está inserido na área de saúde coletiva/pública, denominado ANKOS (A New Kind Of Simulator) [ANKOS 2007], que surge como um sistema capaz de organizar as informações coletadas por pesquisadores em áreas de estudo da esquistossomose, bem como as imagens de satélite da região, em um banco de dados gerenciável e com possibilidade de consultas, recuperação e indexação da informação, formando uma base sólida para a aplicação de autômatos celulares que possibilitem a geração de cenários capazes de levar a tomada de ações estratégicas de combate e prevenção da doenças.

O processo foi descrito baseado em políticas [Johnson K 2001] que definem as diretrizes básicas a serem adotados por todos os projetos da fábrica de software. Elas estão voltadas para o desenvolvimento de software com características open source, ou seja, código compartilhado, equipe distribuída, desenvolvimento colaborativo e descentralizado:
* O projeto de software deve ser modular para facilitar o desenvolvimento
concorrente;
* A prototipação deve ser fechada: um pequeno grupo desenvolve a versão
inicial do produto antes de liberar para a comunidade externa;
* A melhoria do produto é iterativa e incremental;
* O desenvolvimento é concorrente em vários níveis. Várias atividades de
fases diferentes podem ser realizadas em paralelo;
* A revisão de código deve ser realizada em larga escala. Vários usuários
revisam e inspecionam o código de outros usuários;
* Os requisitos também podem ser oriundos da comunidade. Os usuários e
desenvolvedores definem, coletivamente, as funcionalidades do software; 
* Ferramentas de controle de versão e controle de mudanças são necessárias
para a boa comunicação entre a equipe. Todo projeto deve ter um repositório, sob gerência de configuração, para armazenar a documentação e o código
fonte;
* A forma de comunicação principal é assíncrona;
* A informação deve ser compartilhada: código fonte, listas de discussões,
reportagem de erros, solicitação de novos requisitos etc;
* A colaboração é descentralizada;
* A liderança deve ser compartilhada;
* A motivação para contribuição deve ser incentivada pelo desejo de
aprendizado, pela criação de uma comunidade, pela disseminação de
tecnologia e inovação.
 Diversos aspectos do Scrum puderam ser utilizados para o desenvolvimento
distribuído. Primeiramente, o comitê da fábrica de software realizou o estudo de viabilidade baseada na visão apresentada pelo cliente (product owner). Em seguida, uma proposta comercial foi descrita com todo o product backlog inicialmente negociado com a lista dos requisitos da aplicação.

Este product backlog foi priorizado e dividido nas sprints do projeto. Cada sprint foi dividida em quinze dias, onde, ao final de cada uma, um conjunto de novo produto era disponibilizado. Dentro de cada sprint, eram realizadas reuniões assíncronas com o product owner para que este indicasse os itens do backlog com maior valor de negócio. Em seguida, a equipe analisava colaborativamente através de fóruns e lista de discussões, qual a complexidade desses itens e o que caberia dentro da sprint em função de sua
capacidade de produção. A técnica de estimativa de Pontos de Casos de Uso foi utilizada sempre considerando uma produtividade média das últimas sprints realizadas.
 Em seguida, os requisitos eram detalhados e, então, a partir daí o time
selecionava os itens de backlog priorizados, dividindo-os em tarefas de até 1 semana por participante. Essas tarefas eram cadastradas numa ferramenta de planejamento e acompanhamento de projetos para projetos que utilizam métodos ágeis [XPlanner 2002].

 Durante os quinze dias da sprint, a equipe fazia uso do fórum e lista de
discussões para simular o Daily Scrum Meeting. De tal forma que, diariamente, todos do time sabiam o andamento das atividades e os impedimentos encontrados até o momento. Era responsabilidade de um integrante do comitê da fábrica exercer o papel do Scrum Master no sentido de resolver todos os impedimentos reportados por qualquer membro
do time.

Este trabalho apresentou um estudo de caso sobre a aplicação de métodos ágeis, particularmente baseado na abordagem proposta pelo Scrum, em um processo para desenvolvimento de software open source com fortes características de desenvolvimento distribuído.

Ao longo do desenvolvimento do projeto foi percebido que nem todas as práticas do Scrum eram diretamente aplicadas ao contexto de desenvolvimento distribuído de software. Os seguintes aspectos apresentaram os maiores desafios para o uso das práticas ágeis:
* O Scrum defende a unidade da equipe de desenvolvimento. Isso está fortemente relacionado com a presença física do time e com as iterações diárias. Na experiência aqui relatada, o time geograficamente distribuído conseguiu superar este desafio com o uso sistemático do fórum, listas de discussões e ferramentas de chat que permitiam uma boa iteração da equipe;
* As reuniões diárias de quinze minutos previstas no Scrum para que todos
respondam às três perguntas básicas foram substituídas pela comunicação
assíncrona semelhante ao item anterior;
* O Scrum é focado em equipes auto-organizadas e auto-gerenciáveis, além de
prever a questão motivacional como principal aspecto de sucesso do projeto.
Esses mesmos aspectos puderam ser percebidos no desenvolvimento distribuído, onde a equipe poderia ser formada por qualquer membro da comunidade open source que por vontade própria quisesse fazer parte do projeto. Cada integrante é quem escolhia qual atividade do backlog iria desenvolver;
* No Scrum, o product owner deve participar ativamente de vários pontos do
processo: visão, sprint planning, release etc. No desenvolvimento distribuído, nem sempre é possível ter essa participação sistemática devido ao alto índice de comunicação assíncrona. Em alguns casos, foi necessário que o time tivesse uma postura pró-ativa para tomar algumas decisões sem envolver o product owner;
* Outro ponto de adaptação foi em relação às responsabilidades do Scrum Master que, neste contexto, além de ter parte de seu tempo dedicado ao gerenciamento dos impedimentos reportados pelo time, também fazia parte do time de desenvolvedores. 

Apesar do Scrum não cobrir todas as características específicas para equipes
geograficamente distribuídas, foi possível fazermos uso de diversos aspectos de desenvolvimento ágil sem, no entanto, comprometer as particularidades exigidas por esses tipos de projetos. 

#
#
##### Referências
http://www.revistatis.dc.ufscar.br/index.php/revista/article/view/81
https://www.researchgate.net/profile/Yguarata_Cavalcanti/publication/230660778_Adocao_de_SCRUM_em_uma_Fabrica_de_Desenvolvimento_Distribuido_de_Software/links/0deec5322df9c0f3d4000000/Adocao-de-SCRUM-em-uma-Fabrica-de-Desenvolvimento-Distribuido-de-Software.pdf

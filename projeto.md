## Projeto de Pesquisa e Planejamento de Atividades

<br>

|   |   |
|---|---|
| Aluno: Rodrigo Del Fiume Zambon  |  Data início curso: XX/XX/XXXX |
| Orientador: Renatha Accioly Negreiros | Defesa em: XX/XXXX
| Curso: MBA Data Science e Analytics - Modalidade: Distância | Turma: 212 |

<br>

### 1. Título do projeto (Inicial)

<br>

Métricas Ágeis - análise de um dataset de pontos de histórias e lead time.

<br>

### 2. Introdução

<br>

Utilizando a metáfora usada pelos professores Takeuchi e Nonaka (1986) no famoso artigo The New New Product Development Game, os autores compararmm o desenvolvimento de produtos feito até então com uma corrida de bastão, onde cada um faz sua parte e passa adiante, com um jogo de rugby onde a equipe avança junto como uma unidade para ganhar terreno.

Nesta comparação, os autores perceberam que cada vez mais a abordagem antiga e sequencial para o desenvolvimento de novos produtos simplesmente não fará o trabalho.

A estabilidade mantida pelas empresas na década de 80 deu lugar a mudanças frequentes e com ciclos menores. Se as mudanças acontecem mais rápido do lado de fora da sua organização, do que do lado de dentro, o fim de sua organização está próximo, a única questão é saber quando (Jack Welsh). A criação de novos produtos deu lugar as práticas adaptáveis que geralmente testam-se hipóteses para saber o apetite do mercado, ao invés de altos investimentos que podem nos levar ao fracasso sem a possibilidade de nos reerguermos.

A construção de uma organização responsiva passa pela adaptabilidade e colocar o cliente no centro do desenvolvimento de novos produtos. 

A criação do Scrum e consequentemente o desenvolvimento das metodologias ágeis foi uma mudança radical em relação às metodologias prescritivas. O Scrum é semelhante a sistemas autocorretivos, evolucionários e adaptativos(Sutherland 2014).

Scrum não é um processo prescritivo. Ele não nos diz o que fazer em cada circunstância. O Scrum é para ser usado em trabalhos complexos onde seja impossível de prever tudo que irá ocorrer. Scrum é simples de aprender e complexo para se por em prática (Schwaber 2004)

Caso a alta administração espere que os projetos sejam entregues dentro da visão de produto e das restrições de tempo e custo especificados, a todo momento e sem falhar, então eles devem estar conduzindo uma linha de montagem e não desenvolvendo projetos. (Highsmit 2012)

<br>

### 3. Objetivo

<br>

O objetivo primário do trabalho é fazer uma análise dos tempos de lead time no desenvolvimento de um sistema de processo eletrônico construído no estado do Espírito Santo. Contempla ainda esta objetivo demostrar como os outliers, ou seja, tarefas que demoraram mais tempo que o normal, influenciam na qualidade das métricas.

Também é objetivo demostrar que ao realizar as reuniões de planejamento em que se são planejados os itens de backlog para a próxima sprint, as estimativas feitas com o número de fibbonacci não tem relação com a conclusão das histórias. Trata-se de usar o tempo da reunião de planejamento da sprint para criar conversas produtivas sobre os itens e evitar o desperdício de se tentar estimar histórias que nem sempre correspondem com a realidade.

Será demostrado no decorrer do desenvolvimento do trabalho que há correlação entre os valores estimados das histórias de usuários e o tempo que levam para serem concluídas não são correspondentes.

A base de dados foi extraída de um backlog do desenvolvimento de um Sistema de Processo Eletrônico do Estado do Espírito Santo durante um ano de produtividade. É importante salientar algumas características da equipe: não houve modificação nas pessoas do time, permanecendo os mesmos 5 desenvolvedores sendo 1 full stack, 2 de backend e 2 de frontend; além da quantidade de histórias por sprint que eram contabilizadas, vamos apresentar também a quantidade de pontos de histórias por sprint.

No início da medição a equipe trabalhava com 3 histórias de usuários em um sprint de 21 dias e no final de um ano já estavam selecionando 8 histórias. A maturidade da equipe aumenta com o tempo à medida que trabalham juntas sem rotatividade de pessoal.

A estimativa por pontos de histórias era feita para estimar a quantidade de itens que poderiam ser selecionado para a sprint seguinte. O objetivo é demonstrar que histórias com uma estimativa de esforço alta eram solucionadas em poucos dias e o contrário também era verdadeiro, histórias com pouco esforço levavam muitos dias para serem concluídas, ou seja, não há correlação forte entre as estimativas e o tempo que levavam para serem concluídas. Outro objetivo é demostrar como é o tratamento dos outliers na amostra de lead time.

Quando pedimos a alguém para estimar qualquer feature em um projeto, a estimativa muitas vezes é feita levando-se em conta apenas o tempo touch. E ainda com um perfeito hand-off entre os times, com especialistas disponíveis. Isso nunca acontece. O trabalho entra em filas, as pessoas trabalham em mais de um pojeto ao mesmo tempo, as pessoas tiram férias. Nós temos que estimar o trabalho para passar por todo o sistema levando-se em consideração todas as caracteristicas deste sistema. (Duarte 2015)

<br>

### 4. Material e Métodos

<br>

Os dados serão obtidos por meio do sistema de gerenciamento de produtos do time pesquisado. Será extraída do sistema uma tabela em formato CSV (valores separados por vírgulas) com duas colunas, uma de estimativa dos pontos de histórias e o respectivo lead time. 

A amostra será tratada e será feita todo o processo de adequação dos dados para poderem ser usados no trabalho. Serão mantidos os outliers da amostra para a devida análise e tratamento destes valores em um time ágil. Na prática estes valores são importantes primeiro para uma contagem absoluta dos dados e principalmente para descobrirmos as causas destes ocorrências.

Martin, Samarov e Vandacle (1981), argumentaram que, se os dados forem contaminados por observações atípicas (outliers), as previsões baseadas nesses dados históricos podem ser enviesadas. Portanto, uma parte de qualquer programa de monitoramento de previsão deve ser direcionada à detecção de outliers. Os times devem ter total atenção quando esses valores aparecem e principalmente observar e estudar suas causas para que não voltem a acontecer, caso sejam por descuido na forma como trabalham, repriorizações constantes e indefinição do que deve ser feito.

<br>

### 5. Resultados Esperados

<br>

É esperado apresentar as melhores visualizações destes tipo de dados e apresentar não haver relação entre pontos de histórias e o respectivo lead time.

Importante frisar que quanto mais tempo os itens ficam no estado em andamento, ou seja, quanto mais tempo ficam no quadro, mais valor eles perdem. Uma atividade prevista para 8 e que lava 40 dias para ser entregue tem sua eficácia colocada em dúvida para ser entregue ou não.

David Anderson (2014) coloca que a relação entre WIP e qualidade são inversamente proporcionais. Quanto mais tempo em andamento, menos qualidade no final.

<br>

### 6. Cronograma de Atividades

<br>

| Atividades planejadas |   |   |   |   |   |   |   |   |   |   |
|---                    |---|---|---|---|---|---|---|---|---|---|
|                                   | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
| Definição do Projeto de Pesquisa  | X | X |   |   |   |   |   |   |   |   |
| Coleta de Dados                   |   |   | X |   |   |   |   |   |   |   |
| Elaboração do Projeto             |   |   | X | X | X |   |   |   |   |   |
| Validação                         |   |   |   |   |   | X |   |   |   |   |
| Entrega do TCC                    |   |   |   |   |   |   | X | X | X |   |
| Entrega da Apresentação da Defesa |   |   |   |   |   |   |   |   |   | X |

<br>

### 7. Referências Bibliográficas

<br>

ANDERSON, David J.. Kanban: mudanca evolucionaria de sucesso para seu negocio de tecnologia: mudança evolucionária de sucesso para seu negócio de tecnologia. Sequim, Wa, Usa: Blue Hole Press, 2011. 290 p.

DUARTE, Vasco. **No estimates**: how to measure project progress without estimating. [S. L.]: Oikosofy Series, 2015.

HIGHSMITH, Jim. **Gerenciamento Ágil de Projeto**. Rio de Janeiro: Alta Books, 2012.

MARTIN, R Douglas, Alexander M Samarov, and Walter Vandaele. 1981. **Robust Methods for ARIMA Models.** Center for Computational Research in Economics; Management Science

SUTHERLAND, Jeff. **SCRUM**: a arte de fazer o dobro do trabalho na metade do tempo. São Paulo: Leya, 2014.

SCHWABER, Ken. **Agile Project Management with Scrum.** Redmond, Washington: Microsoft Press, 2004.

TAKEUCHI, Hirotaka; NONAKA, Ikujiro. **The New New Product Development Game**. 1986. Harvard Bussiness Review - From the Magazine. Disponível em: https://hbr.org/1986/01/the-new-new-product-development-game. Acesso em: 26 ago. 2022.
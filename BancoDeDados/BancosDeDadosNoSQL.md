# Bancos de dados NoSQL

## Tópicos Abordados

- Introdução aos Bancos de Dados NoSQL
    - Definição e principais características
    - Modelos de dados e modelos lógicos de bancos de dados NoSQL
        - Orientado a documentos
        - Chave/Valor
        - Orientado a grafos
        - Orientado a coluna
    - Complexidade de bancos de dados NoSQL
- Principais SGBDS e seus recursos de gerenciamento de dados
    - DynamoDB: orientado a chave/valor
    - MongoDB: orientado a documentos
    - ArangoDB: orientado a grafos
    - Cassandra Database: orientado a colunas
    - Data manipulation: comands SQL para modelos relacionais
    - Outros bancos de dados NoSQL

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Leia o excerto a seguir: “O modelo de banco de dados baseado em colunas é mais complexo que o modelo chave-valor. Este modelo é baseado em uma estrutura com três itens: a linha, coluna e timestamp, que serve para determinar as diferentes versões de um dado.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre modelo baseado em colunas, analise as asserções a seguir e a relação proposta entre elas: I. No modelo baseado em colunas, uma das principais características é que é possível comprimir os dados. Porque: II. Os dados são armazenados em colunas separadas. A seguir, analise a alternativa correta:
    - R : Letra D.  As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I. 
- Q_i
    - P : Leia o excerto a seguir: “Os bancos de dados NoSQL (Not Only SQL) são uma ‘proposta com o objetivo de atender aos requisitos de gerenciamento de grandes volumes de dados, semiestruturados ou não estruturados, que necessitam de alta disponibilidade e escalabilidade.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, analise as asserções a seguir e a relação proposta entre elas. I. Os bancos de dados NoSQL surgiram como consequência da ineficiência dos bancos de dados relacionais. Porque: II. Os bancos de dados relacionais possuem um desempenho ruim ao lidar com escalabilidade e disponibilidade, duas características fortes nos bancos NoSQL. A seguir, assinale a alternativa correta:
    - R : Letra C. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I. 
- Q_i
    - P : Leia o excerto a seguir: “O Dynamo é um banco de dados NoSQL de alta disponibilidade baseado no armazenamento de chave-valor (Key-value) usado nos servidores da Amazon para prover uma experiência ‘always-on’ (sempre ativo). A desvantagem deste modelo é que não permite a recuperação de objetos por meio de consultas mais complexas.” Fonte: OLIVEIRA, S. S. Bancos de dados Não-Relacionais: um novo paradigma para armazenamento de dados em sistemas de ensino colaborativo. Revista da Escola de Administração Pública do Amapá, V. 2, n. 1, p. 184-194, 2014. Considerando essas informações e o conteúdo estudado sobre modelo de bancos de dados orientado a chave-valor, pode-se afirmar que o Dynamo DB.
    - R : Letra E. é composto de tabelas, itens e atributos.

- Q_i
    - P : Leia o excerto a seguir: “Este modelo é considerado bastante simples e permite a visualização do banco de dados como uma grande tabela hash. De maneira bem simples, o banco de dados é composto por um conjunto de chaves, às quais estão associadas um único valor, que pode ser uma string ou um binário.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre modelo de bancos de dados chave-valor, pode-se afirmar que:
    - R : Letra A.  a DynamoDB é um banco de dados do tipo chave-valor 
- Q_i
    - P : Leia o excerto a seguir: “O modelo orientado a grafos possui três componentes básicos: os nós (são os vértices do grafo), os relacionamentos (são as arestas) e as propriedades (ou atributos) dos nós e relacionamentos. Neste caso, o banco de dados pode ser visto como um multigrafo rotulado e direcionado, onde cada par de nós pode ser conectado por mais de uma aresta.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre modelo de bancos de dados orientado a grafos, pode-se afirmar que:
    - R : Letra D. Um banco de dados orientado a grafos pode ser classificado pelo tipo do vértice.

- Q_i
    - P : Leia o excerto a seguir: “O modelo baseado em documentos armazena coleções de documentos. Um documento, em geral, é um objeto com um identificador único e um conjunto de campos, que podem ser strings, listas ou documentos. Esse modelo se assemelha em alguns aspectos ao modelo chave-valor.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, analise as asserções a seguir e a relação proposta entre elas: I. Os bancos de dados NoSQL do tipo orientados a documentos são fáceis de serem implementados. Porque: II. Os bancos de dados orientados a documentos usam basicamente documentos do tipo xml ou JSON. A seguir, assinale a alternativa correta:
    - R : Letra B. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I

- Q_i
    - P : Leia o excerto a seguir: “O grande volume de dados gerado por aplicações Web, juntamente com os requisitos diferenciados destas aplicações, como a escalabilidade sob demanda e o elevado grau de disponibilidade, têm contribuído para o surgimento de novos paradigmas e tecnologias. As redes sociais, por exemplo, requerem o gerenciamento de grandes quantidades de dados não estruturados, os quais são gerados diariamente por milhões de usuários em busca do compartilhamento de informações, conhecimentos e interesses.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre os conceitos básicos de bancos de dados, analise as afirmativas a seguir. I. Os bancos de dados relacionais são os mais adequados para lidar com grandes quantidades de dados, como acontece em uma rede social. II. Os bancos de dados NoSQL fazem parte de um paradigma adequado para lidar com uma grande quantidade de dados. III. Os bancos de dados relacionais são usados na maioria das redes sociais para lidar com a grande quantidade de dados desses sistemas. IV. Os bancos NoSQL garantem escalabilidade, um requisito essencial para redes sociais, que lidam com grandes quantidades de dados. Está correto apenas o que se afirma em:
    - R : Letra D. II e IV
- Q_i
    - P : Leia o excerto a seguir: “Uma das principais características do modelo orientado a documentos é que ele possui um esquema simples, diferente do esquema relacional que precisa de uma estrutura fixa e rígida no modelo.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, analise as asserções a seguir e a relação proposta entre elas. I. O modelo baseado em documentos é flexível, permitindo a inserção de novos campos. Porque: II. O modelo baseado em documentos permite a atualização dos documentos. A seguir, assinale a alternativa correta:
    - R : Letra A. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.
- Q_i
    - P : Leia o excerto a seguir: “Atualmente a diversidade de tipos de modelos e números de banco de dados não relacionais (NoSQL) é grande, cada um possuindo conceitos e particularidades diferentes proporcionando ao desenvolvedor uma gama enorme, podendo atender a necessidades distintas.” Fonte: TOTH, R. M. Abordagem NoSQL – uma real alternativa. Universidade Federal de São Carlos. Sorocaba, 2011. (Adaptado). Considerando essas informações e o conteúdo estudado sobre o tópipco, pode-se afirmar que são modelos de dados NoSQL:
    - R : Letra E. o modelo chave-valor, o modelo orientado a documentos, modelo orientado a grafos e modelo baseado em colunas.
- Q_i
    - P : Leia o excerto a seguir: “Uma característica evidente dos bancos de dados NoSQL é a ausência completa ou quase total do esquema que define a estrutura dos dados modelados. Esta ausência de esquema facilita tanto a escalabilidade quanto contribui para um maior aumento da disponibilidade.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre NoSQL, pode-se afirmar que:
    - R : Letra E. A ausência de estrutura permite flexibilidade aos bancos NoSQL. 


### Questionário II

- Q_i
    - P : Leia o trecho a seguir: “O modelo orientado a grafos possui três componentes básicos: os nós (são os vértices do grafo), os relacionamentos (são as arestas) e as propriedades (ou atributos) dos nós e relacionamentos. Neste caso, o banco de dados pode ser visto como um multigrafo rotulado e direcionado, onde cada par de nós pode ser conectado por mais de uma aresta”. Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R. de; PONTES, J. C. de S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre o tópico, pode-se afirmar, em relação ao vértice, que os bancos de dados baseados em grafos podem ser classificados como:
    - R : Letra C. nó com rótulo e nó com atributo.
- Q_i
    - P : Leia o excerto a seguir: “Após seis anos de sua criação, o Facebook possui, atualmente, cerca de 3,5 bilhões de conteúdos (links, posts etc.) compartilhados por semana. Para evitar problemas com a escalabilidade e disponibilidade dos dados, a empresa desenvolveu o Cassandra, uma solução NoSQL.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, v. 10, n. 1, p. 11, 2011. Assim como existe a linguagem SQL para os modelos relacionais, um banco de dados Cassandra pode utilizar a CQL (Cassandra Query Language). Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, pode-se afirmar que.
    - R : Letra D. SELECT é um comando comum às duas linguagens. 
- Q_i
    - P : Leia o excerto a seguir: “Aplicativos de alta disponibilidade, onde a minimização da inatividade é fundamental, podem utilizar um banco de dados orientado a colunas, como o Cassandra. A importância de conhecer cada solução e adotar aquela que for mais adequada poderá contribuir para a diminuição do custo de criação do banco de dados.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre Cassandra DB, analise as asserções a seguir e a relação proposta entre elas: I. O banco de dados Cassandra DB permite repetições de dados. Porque: II. O armazenamento de dados atualmente é bem mais barato. A seguir, assinale a afirmativa correta:
    - R : Letra B. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.
- Q_i
    - P : Leia o excerto a seguir: “Aplicações que exigem alto desempenho em consultas com muitas junções podem adotar um banco orientado a grafos. A vantagem de utilização do modelo baseado em grafos fica bastante clara quando consultas complexas são exigidas pelo usuário. Comparado ao modelo relacional, que para estas situações pode ser muito custoso.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. ArangoDB é um sistema de banco de dados criado em 2014 que suporta diversos modelos NoSQL. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, pode-se afirmar que:
    - R : Letra D. o ArangoDB suporta os modelos de dados chave/valor, baseado em documentos e em grafos.
- Q_i
    - P : Leia o excerto a seguir: “A criação da tabela em CQL (Cassandra Query Language) define um conjunto de colunas e uma chave primária. Para cada coluna é assinalado um tipo, que pode ser primitivo, como int ou text, ou complexo, como conjunto, lista ou mapa. Uma coluna pode ser definida como estática para definir um valor que será compartilhado por todas as linhas de uma mesma partição. Isso só é útil para tabelas com múltiplas linhas por partição.” Fonte: DIANA, M.; GEROSA, M. A. NoSQL na web 2.0: Um estudo comparativo de bancos não-relacionais para armazenamento de dados na web 2.0. In: IX Workshop de Teses e Dissertações em Banco de Dados, Departamento de Ciências da Computação, Universidade de São Paulo, São Paulo, 2010. Disponível em: . Acesso em: 10 out. 2019. Considerando essas informações e o conteúdo estudado sobre Cassandra DB, pode-se afirmar que:
    - R : Letra E
- Q_i
    - P : Leia o excerto a seguir: “No modelo relacional os dados são estruturados, armazenados, manipulados e recuperados em forma de tabelas normalizadas, e todas as transações seguem propriedades de forte consistência chamadas ACID (Atomicidade, Consistência, Isolamento, Durabilidade).” Fonte: DE SOUZA, V. C. O.; DOS SANTOS, M. V. C. Maturing, consolidation and performance of NoSQL databases-comparative study. In: Proceedings of the Annual Conference on Brazilian Symposium on Information Systems: Information Systems: A Computer Socio-Technical Perspective. 2015. p. 32. Os bancos de dados NoSQL se baseiam em outras propriedades, definidas como BASE. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, pode-se afirmar que BASE significa
    - R : Letra B. Basically available (basicamente disponível), Soft-state (estado leve), Eventual Consistency (eventualmente consistente) 
- Q_i
    - P : Uma característica evidente dos bancos de dados NoSQL é a ausência completa ou quase total do esquema que define a estrutura dos dados modelados, diferente do modelo relacional que necessita de uma estrutura. Considerando essas informações e o conteúdo estudado sobre bancos de dados NoSQL, analise as asserções a seguir e a relação proposta entre elas: I. Nos modelos NoSQL não há garantias de integridade dos dados, tal como ocorre no modelo relacional. Porque: II. A ausência de esquema definido prejudica a integridade dos dados. A seguir, assinale a alternativa correta.
    - R : Letra E. As asserções I e e II são proposições verdadeiras, e a II é uma justificativa correta da I.
- Q_i
    - P : Leia o excerto a seguir: “Os bancos de dados NoSQL têm sido amplamente adotados em empresas como Facebook, Amazon e Google com o intuito de atender a suas demandas de escalabilidade, alta disponibilidade e dados não estruturados. Além disso, atualmente, diversos bancos de dados NoSQL de código livre estão disponíveis.” Fonte: LÓSCIO, B. F.; OLIVEIRA, H. R.; PONTES, J. C. S. NoSQL no desenvolvimento de aplicações Web colaborativas. VIII Simpósio Brasileiro de Sistemas Colaborativos, V. 10, n. 1, p. 11, 2011. Considerando essas informações e o conteúdo estudado sobre modelo de bancos de dados NoSQL, pode-se afirmar que:
    - R : Letra C. o objetivo da disponibilidade é manter os serviços ativos o máximo de tempo possível.
- Q_i
    - P : O MongoDB é um banco de dados orientado a documentos, sendo possível utilizá-lo em diferentes sistemas operacionais. Foi implementado em C++ e permite tanto concorrência como replicação de dados, característica importante nos bancos de dados NoSQL. Considerando essas informações e o conteúdo estudado sobre MongoDB, pode-se afirmar que:
    - R : Letra D. uma coleção em banco de dados MongoDB é uma estrutura que armazena um conjunto de documentos.
- Q_i
    - P : Leia o excerto a seguir: “Um banco de dados pode possuir diversos tamanhos e diferentes complexidades, em que para bancos de dados muito grandes e complexos é inviável que apenas um DBA cuide de sua totalidade. Sendo assim, é possível dividir as funções do DBA em uma equipe mais especializada, que irá trabalhar em conjunto para conseguir obter um maior êxito na administração do banco de dados.” Fonte: LEITE, H. P.; BONOMO, I. da S. Análise comparativa de projeto e administração de banco de dados entre os SGBDs Cassandra e MySQL. Universidade de Brasília, 2016. Disponível em: . Acesso em: 10 out. 2019. Considerando essas informações e o conteúdo estudado sobre os conceitos básicos de bancos de dados, analise as afirmativas a seguir. I. A complexidade de um banco de dados pode ser analisada em termos da complexidade de seus dados. II. A complexidade de um banco de dados pode ser analisada em termos da complexidade de seus relacionamentos. III. A complexidade de um banco de dados pode ser analisada em termos de velocidade de desenvolvimento do programador. IV. A complexidade de um banco de dados pode ser analisada em termos das métricas do banco de dados. Está correto apenas o que se afirma em:
    - R : Letra A.  I e II. 
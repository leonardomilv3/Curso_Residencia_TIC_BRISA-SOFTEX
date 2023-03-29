# Linguagens SQL, NoSQL e NewSQL.

## Tópicos Abordados

- Linguagens SQL, Subconjuntos e Principais Comandos
    - DDL (create, drop, alter)
    - DML (insert, update, delete)
    - DQL (select)
    - DCL (grant e revoke)
- Banco de Dados NoSQL
    - Coleções
    - Documentos
    - Criando um banco de dados
    - Inserção de dados
    - Query
    - Projection
- Banco de Dados NewSQL 


## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Leia o trecho a seguir: “A restrição de vazio determina que a identificação de uma linha de uma tabela não pode ser feita por um valor desconhecido, motivo pelo qual a chave primária de uma tabela não pode possuir nenhum elemento de sua composição com valor nulo, como o nome de um usuário, por exemplo.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre os conceitos básicos de bancos de dados, analise as afirmativas a seguir: I. Ao utilizar NOT NULL define-se que o valor de um atributo pode ser excluído da estrutura. II. A restrição de domínio pode definir os valores ideais e necessários para um atributo. III. A restrição de integridade referencial é capaz de definir os valores ideais e necessários para um atributo e se um atributo pode ser nulo. IV. As restrições semânticas são chamadas também de regras de negócio. Está correto apenas o que se afirma em:
    - R : Letra C. II e IV
- Q_i
    - P : Leia o trecho a seguir: “Um sistema de banco de dados fornece uma linguagem de definição de dados para especificar o esquema de banco de dados e uma linguagem de manipulação de dados para expressar as consultas e atualizações de banco de dados. Na prática, as linguagens de definição de dados e de manipulação de dados não são duas linguagens separadas, mas simplesmente formam partes de uma única linguagem de banco de dados, como a amplamente usada linguagem SQL.” Fonte: SILBERSCHATZ, A. et al. Sistema de banco de dados. São Paulo: Elsevier Brasil, 2016. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que:
    - R : Letra E. a linguagem de manipulação de dados é responsável por realizar operações como inserção de dados nas tabelas, sua atualização e exclusão.
- Q_i
    - P : Leia o trecho a seguir: “A restrição de vazio determina que a identificação de uma linha de uma tabela não pode ser feita por um valor desconhecido, motivo pelo qual a chave primária de uma tabela não pode possuir nenhum elemento de sua composição com valor nulo [...] o nome de um usuário, por exemplo.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre linguagem SQL e integridade de dados, analise as asserções a seguir e a relação proposta entre elas. I. Uma chave primária deve ser uma coluna obrigatória. Porque: II. Colunas obrigatórias são colunas nas quais não são admitidos valores nulos. A seguir, assinale a alternativa correta:
    - R : Letra E. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.  
- Q_i
    - P : Leia o trecho a seguir: “O comando ALTER permite realizar alterações em um determinado objeto de um banco de dados. Por exemplo, em uma tabela que já foi criada com seus atributos, caso seja necessário adicionar mais um atributo, esse comando pode ser utilizado.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que a forma correta de adicionar um novo atributo em uma tabela é: 
    - R : Letra D. ALTER TABLE funcionario ADD tipo_de_vinculo
- Q_i 
    - P : Leia o trecho a seguir: “O mais importante dos comandos usados em SQL é o SELECT, pois consultas são realizadas a todo instante. Ele permite a consulta de um conjunto de registros de uma ou mais tabelas. Além disso, contém cláusulas opcionais que servem para filtrar e tratar adequadamente a informação retornada.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o comando para selecionar todos os dados de uma tabela é: 
    - R : Letra A. SELECT *
- Q_i
    - P : Leia o trecho a seguir: “A instrução GROUP BY agrupa os resultados de uma consulta de mesmos valores em linhas resumidas, como ‘selecione o número de clientes em cada país’. A instrução GROUP BY pode ser usada com funções agregadas (COUNT, MAX, MIN, SUM, AVG).” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o comando GROUP BY foi usado corretamente em:
    - R : Letra C.  SELECT * FROM produtos WHERE Preco>50 GROUP BY tipo
- Q_i
    - P : Leia o trecho a seguir: “Através do SQL se pode realizar diversas operações, como criação, inserção, atualização e exclusão de dados. Para realizar essas operações existem subconjuntos da linguagem SQL que são a definição de dados (DDL), manipulação de dados (DML), controle de dados (DCL), transação de dados (DTL) e consulta (DQL).” Fonte: BEAULIEU, A. Aprendendo SQL: Dominando os Fundamentos de SQL. São Paulo: Novatec, 2010. Considerando essas informações e o conteúdo estudado sobre linguagem SQL, analise as asserções a seguir e a relação proposta entre elas. I. O comando CREATE TABLE faz parte da linguagem de definição de dados. Porque: II. Comandos do tipo CREATE servem para definir dados, bem como criar qualquer objeto dentro do banco de dados como, por exemplo, uma tabela. A seguir, assinale a alternativa correta:
    - R : Letra B. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.
- Q_i
    - P : Leia o trecho a seguir: “Em SQL, INSERT é o comando utilizado para inserir dados em uma tabela. Esse comando pode ser utilizado para inserir uma linha de dados de cada vez ou mesmo para inserir várias linhas de dados ao mesmo tempo.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que é possível inserir:
    - R : Letra E.  dados em uma tabela com base no resultado de um SELECT.
- Q_i
    - P : Leia o trecho a seguir: “Em toda e qualquer tabela existente em um banco de dados relacional haverá sempre uma coluna ou um conjunto de colunas concatenadas, cujos valores são únicos na tabela, isto é, aquele valor nunca se repete em nenhuma outra linha da tabela. Essa coluna ou conjunto de colunas concatenadas identifica uma única linha da tabela. Então dizemos que essa coluna ou conjunto de colunas forma a chave primária da tabela.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, São Paulo, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que uma chave primária pode ser definida em SQL como:
    - R : Letra C. PRIMARY KEY (nome_do_atributo)
- Q_i
    - P : Leia o trecho a seguir: “O comando DELETE permite excluir qualquer dado adicionado no banco de dados através do INSERT. Da mesma forma que o SELECT, algumas condições podem ser definidas pelo administrador do banco de dados para que as exclusões aconteçam.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que:
    - R : Letra B. DELETE FROM Empregados WHERE codigo = 125 é uma forma correta de utilizar o comando DELETE.


### Questionário II

- Q_i
    - P : Leia o trecho a seguir: “O MongoDB (derivado da palavra humongous, que em inglês quer dizer gigantesco) é um tipo relativamente novo de banco de dados, que não tem conceitos de tabelas, esquemas, SQL ou linhas. Não há transações, conformidade com ACID, joins (junções), chaves estrangeiras nem vários outros recursos característicos de linguagens relacionais.” Fonte: HOWS, D. et al. Introdução ao MongoDB. São Paulo: Novatec, 2015. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o comando para consultar dados no MongoDB é:
    - R : Letra D.  db.collection.find (query, projection) 
- Q_i
    - P : Leia o trecho a seguir: “O comando SQL ORDER BY serve para ordenar o resultado da sua consulta de acordo com uma ordem específica determinada pelo desenvolvedor do banco. Ele pode ser utilizado para classificar os dados de forma crescente ou decrescente.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que as palavras-chave para ordenar de maneira ascendente e descendente são:
    - R : Letra D. ASC e DESC. 
- Q_i
    - P : Leia o trecho a seguir: “O comando BETWEEN é usado em SQL para realizar uma consulta que possui valores dentro de um certo intervalo. Pode ser um período de tempo ou, por exemplo, selecionar nome e salário dos funcionários que recebem entre 1500 e 3500 reais.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o comando BETWEEN foi usado corretamente em:
    - R : Letra B. SELECT nome, salario FROM funcionarios WHERE salario BETWEEN 1500 and 3500.
- Q_i
    - P : Leia o trecho a seguir: “DCL, em inglês Data Control Language, que significa Linguagem de Controle de Dados, é o subconjunto de comando do SQL que define o que é relacionado a autorizações de dados. A DCL também determina quais os usuários que têm acesso aos bancos de dados e possuem poderes de criação e manipulação dos dados.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que os comandos da DCL são:
    - R : Letra 
<!-- Colocar ESSA QUESTAO no FÓRUM -->
- Q_i
    - P : Leia o trecho a seguir: “DCL, em inglês Data Control Language, que significa Linguagem de Controle de Dados, é o subconjunto de comando do SQL que define o que é relacionado a autorizações de dados. A DCL também determina quais os usuários que têm acesso aos bancos de dados e possuem poderes de criação e manipulação dos dados.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que os comandos da DCL são:
    - R : Letra C. GRANT e REVOKE
- Q_i
    - P : Leia o trecho a seguir: “Na linguagem SQL, o filtro LIKE é utilizado para realizar comparações com os dados e retornar resultados relacionados ao filtro. Por exemplo: consulte o CPF, nome e salário de todas as pessoas que possuem o nome ‘Luciana’ na tabela clientes.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre linguagem SQL, analise as afirmativas a seguir: I. 'c_mente' retornaria a palavra comente pelo filtro LIKE. II. '%maria': retornaria a palavra Mariana pelo filtro LIKE. III. 'c_ma%': retornaria a palavra comando pelo filtro LIKE. IV. 'Francisc_: retornaria as palavras Francisco e Francisca pelo filtro LIKE. Está correto apenas o que se afirma em:
    - R : Letra A. I, III e IV. 
- Q_i
    - P : Leia o trecho a seguir: “No MongoDB, um banco de dados é composto por coleções de documentos no formato BSON, uma versão binária dos documentos JSON. As coleções e documentos lembram, respectivamente, os conceitos de tabelas e linhas dos sistemas relacionais.” Fonte: QUEIROZ, G. et al. Bancos de dados geográficos e sistemas NoSQL: onde estamos e para onde vamos. Revista Brasileira de Cartografia, Uberlândia, v. 3, n. 65, 2013. Considerando essas informações e o conteúdo estudado sobre o MongoDB, analise as asserções a seguir e a relação proposta entre elas. I. Os documentos de uma coleção podem ter campos muito diferentes uns dos outros. Porque: II. No MongoDB, os documentos de uma coleção não precisam obrigatoriamente ter o mesmo esquema. A seguir, assinale a alternativa correta:
    - R : Letra D. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I 
- Q_i
    - P : Leia o fragmento a seguir: “Na linguagem SQL é possível realizar consultas que unem resultados de tabelas. Para realizar esta operação, é necessário concatenar o nome da tabela com o nome do atributo que deseja se trazer na busca, além de fazer o mesmo com a outra tabela da qual você quer juntar os dados.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que uma forma correta de selecionar dois atributos de duas tabelas para realizar uma junção é:
    - R : Letra E. SELECT produto.descricao, notafiscal.valor.

- Q_i
    - P : Leia o trecho a seguir: “O comando DROP é utilizado em SQL para realizar operações de exclusão de itens da estrutura do banco de dados. Por exemplo, é possível excluir uma tabela do banco de dados ou até mesmo o próprio banco de dados usando esse comando.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o DROP está excluindo corretamente uma tabela ao usar o comando:
    - R : Letra A.  DROP TABLE disciplina. 
- Q_i
    - P : Leia o trecho a seguir: “O MongoDB (derivado da palavra humongous, que em inglês quer dizer gigantesco) é um tipo relativamente novo de banco de dados, que não tem conceitos de tabelas, esquemas, SQL ou linhas. Não há transações, conformidade com ACID, joins (junções), chaves estrangeiras nem vários outros recursos característicos de linguagens relacionais.” Fonte: HOWS, D. et al. Introdução ao MongoDB. São Paulo: Novatec, 2015. (Adaptado). Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que o comando para inserir mais de um dado no MongoDB é:
    - R : Letra E.  db.collection.insertMany() 

- Q_i:
    - P : Leia o trecho a seguir: “A linguagem de transação de dados é responsável por gerenciar as diversas transações que podem ocorrer através da DML (Linguagem de Manipulação de Dados). Um dos comandos usados na DML é o BEGIN WORK, que serve para dar início a uma transação no banco de dados.” Fonte: MACHADO, F. Banco de Dados – Projeto e Implementação. São Paulo: Saraiva, 2018. Considerando essas informações e o conteúdo estudado sobre a linguagem SQL, pode-se afirmar que também são comandos da DTL:
    - R : Letra A. COMMIT E ROLLBACK. 

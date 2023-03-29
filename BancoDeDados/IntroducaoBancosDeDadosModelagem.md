# Introdução aos Bancos de Dados e sua Modelagem

## Tópicos Abordados

- Conceito de Banco de Dados
- Modelagem de Banco de Dados
    - ME-R
    - DE-R
    - DLD (Modelo Lógico)
    - Scripts (Modelo Físico)
- Modelos de Banco de Dados
    - Modelo Relacional
    - Banco de Dados Orientado à Objetos
- Data Warehouse


## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Leia o trecho a seguir: “Toda coluna que faz parte da chave primária e que não é uma chave estrangeira corresponde a um atributo identificador da entidade ou relacionamento. O atributo identificador serve portanto, para caracterizar uma entidade de forma única”. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 39. Considerando essas informações e o conteúdo estudado sobre os conceitos básicos de bancos de dados, analise as afirmativas a seguir. I. Matrícula, código e CPF podem ser considerados como atributos identificadores. II. Matricula, nota e salário podem ser considerados como atributos identificadores. III. Código, salário e nome podem ser considerados como atributos identificadores. IV. ID da compra, código do cliente e CPF podem ser considerados como atributos identificadores. A seguir, assinale a alternativa correta:
    - R : Letra E. I e IV. 
- Q_i
    - P : Leia o trecho a seguir: “Um atributo corresponde a alguma propriedade de interesse que ajuda a descrever uma entidade, como o nome do funcionário ou seu salário. [...] Por exemplo, uma entidade empregado pode ser descrita pelo nome do empregado, idade, endereço, salário e trabalho (função). Uma dada entidade terá um valor para cada um de seus atributos.” Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 20. Considerando essas informações e o conteúdo estudado sobre modelo conceitual, pode-se afirmar que:
    - R : Letra E. atributos podem ser classificados como simples, compostos, monovalorados e multivalorados. 
- Q_i
    - P : Leia o trecho a seguir: “Os bancos de dados e os sistemas de bancos de dados se tornaram componentes essenciais no cotidiano da sociedade moderna. No decorrer do dia, a maioria de nós se depara com atividades que envolvem alguma interação com os bancos de dados. Por exemplo, se formos ao banco para efetuarmos um depósito ou retirar dinheiro, se fizermos reservas em um hotel ou se comprarmos produtos [...] de um fornecedor por intermédio de sua página Web, muito provavelmente essas atividades envolverão uma pessoa ou um programa de computador que acessará um banco de dados.” Fonte: ELMASRI, R. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 2. Para que os bancos de dados possam ser utilizados pelas aplicações, é necessário um processo de elaboração e criação desses bancos. Considerando essas informações e o conteúdo estudado, pode-se afirmar que uma das ferramentas mais importantes na criação de um banco é:
    - R : Letra E. o sistema gerenciador de banco de dados (sgbd).

- Q_i 
    - P : Leia o trecho a seguir: “A especialização é o processo de definir um conjunto de subclasses de um tipo entidade; esse tipo entidade é chamado superclasse da especialização. O conjunto de subclasses que forma uma especialização é definido com base em algumas características de distinção das entidades da superclasse. Por exemplo, o conjunto de subclasses {SECRETÁRIA, ENGENHEIRO, TÉCNICO} é uma especialização da superclasse EMPREGADO, que distingue cada entidade empregado com base em seu tipo de trabalho.” Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 62. Considerando essas informações e o conteúdo estudado sobre modelo conceitual de dados, analise as afirmativas a seguir. I. As entidades “Secretária” e “Motorista” podem ser especializações de “Funcionário”. II. “Cantora” e “Contrato” podem ser especializações da entidade “Gravadora”; III. “Salário” e “Funcionário” podem ser especializações da entidade “Supermercado”; IV. “Fone” e “Vitrola” são especializações de “Equipamento”. A seguir, assinale a alternativa correta:
    - R : Letra C.  I e IV.
- Q_i
    - P : Leia o trecho a seguir: Vários modelos de dados têm sido propostos e eles são classificados de acordo com os tipos de conceitos usados para descrever a estrutura do banco de dados. Os de alto nível, ou modelos de dados conceituais, possuem conceitos que descrevem os dados como os usuários os percebem, enquanto os de baixo nível, ou modelos de dados físicos, contêm conceitos que descrevem os detalhes de como os dados estão armazenados no computador. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 20. Considerando essas informações e o conteúdo estudado sobre modelagem de banco de dados, analise as afirmativas a seguir e a relação proposta entre elas. I. O modelo conceitual de banco de dados é a fase inicial de elaboração do banco de dados. Ele serve de base para as etapas seguintes, como um link de comunicação com o cliente. Porque: II. Ao identificar possíveis erros na modelagem inicial (conceitual), custos adicionais e retrabalho no desenvolvimento do banco são evitados. A seguir, assinale a alternativa correta:
    - R : Letra D.  As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I 
- Q_i
    - P : Leia o trecho a seguir: “Para fins de projeto de banco de dados, uma propriedade importante de um relacionamento é a de quantas ocorrências de uma entidade podem estar associadas a uma determinada ocorrência através do relacionamento. Esta propriedade é chamada de cardinalidade de uma entidade em um relacionamento.” Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 46. Considerando essas informações e o conteúdo estudado sobre modelo entidade-relacionamento, pode-se afirmar que:
    - R : Letra B. um relacionamento um para muitos acontece quando uma das entidades pode estar relacionada a várias ocorrências da outra.
- Q_i
    - P : Leia o trecho a seguir: “Ao utilizar o modelo conceitual de dados com a técnica de entidades e relacionamentos, obtemos esquemas puramente conceituais sobre a essência de um sistema, ou melhor, para o negócio que estamos desenvolvendo um projeto de banco de dados”. Fonte: MACHADO, F.; DE ABREU, M. Projeto de banco de dados: uma visão prática. São Paulo: Saraiva Educação, 1996. Considerando essas informações e conteúdo estudado, pode-se afirmar que as entidades de um modelo conceitual podem ser definidas como:
    - R : Letra A. qualquer coisa do mundo real, seja ela física ou conceitual. 
- Q_i
    - P : Leia o excerto a seguir: “O objeto básico que o modelo ER (Entidade-Relacionamento) representa é uma entidade, 'algo' do mundo real, com uma existência independente. Uma entidade pode ser um objeto com uma existência física (por exemplo, uma pessoa, um carro, uma casa ou um funcionário) ou um objeto com uma existência conceitual (por exemplo, uma empresa, um trabalho ou um curso universitário). Cada entidade tem atributos — propriedades particulares que a descrevem”. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 39. Considerando essas informações e o conteúdo estudado sobre modelagem conceitual de dados, uma entidade forte pode ser definida como:
    - R : Letra E. uma entidade que não depende de outras para existir.
- Q_i
    - P : Leia o trecho a seguir: “Um banco de dados representa alguns aspectos do mundo real, sendo chamado, às vezes, de minimundo. As mudanças no minimundo são refletidas em um banco de dados”. Considere, portanto, que apenas os aspectos importantes do mundo real são representados no minimundo e, consequentemente, no banco de dados. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 3. Considerando essas informações e o conteúdo estudado sobre os conceitos básicos de bancos de dados, analise as alternativas a seguir. I. Para um banco de dados de um restaurante, nome do cliente, valor da conta e pratos favoritos são itens relevantes no minimundo. II. Para um banco de dados de um restaurante, gosto musical, pratos favoritos e tamanho de vestuário são atributos relevantes para o minimundo. III. Para um banco de dados de um restaurante, bebidas preferidas e tempo de permanência no local são atributos relevantes para o minimundo. IV. Para um banco de dados de um restaurante, preferência de pagamento e sugestões de pratos promocionais são atributos relevantes para o minimundo. A seguir, assinale a alternativa correta:
    - R : Letra A; I e III
- Q_i
    - P : Leia o trecho a seguir: “O dado no banco de dados pode ser alterado frequentemente. Por exemplo, em um banco de dados de uma escola, ele muda todas as vezes que adicionamos um aluno ou registramos uma nova nota para um aluno. Os dados desse banco, em um determinado momento, são chamados de estado do banco de dados ou instantâneo (snapshot). Também chamado o conjunto corrente de ocorrências ou instâncias no banco de dados.” Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 21. Considerando essas informações e o conteúdo estudado sobre modelo conceitual de dados, pode-se afirmar que uma ocorrência de um banco de dados também pode ser definida como:
    - R : Letra A. um registro em uma tabela de um banco de dados relacional.

### Questionário II

- Q_i
    - P : No modelo físico, a linguagem SQL (standard query language — linguagem de consulta padrão) é utilizada na realização várias operações no banco de dados, que vão desde a criação do banco até suas tabelas, atributos e relacionamentos. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 149. Considerando essas informações e o conteúdo estudado sobre Modelagem física de dados, analise as afirmativas a seguir e a relação proposta entre elas. I. O phpMyAdmin é um software que pode ser usado para criar o banco de dados físico. Porque: II. Através dele, é possível utilizar comandos SQL que permitem criar a estrutura do banco de dados. A seguir, assinale a alternativa correta:
    - R : Letra E. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I
- Q_i
    - P : Leia o trecho a seguir: “A modelagem de dados usada em um Data Warehouse é chamada de modelagem dimensional, e é uma técnica de concepção de um modelo de dados baseado em métricas que descrevem aspectos relevantes de um determinado negócio.” Fonte: MACHADO, F. Tecnologia e projeto de data warehouse: uma visão multidimensional. São Paulo: Erica, 2006. p. 27. Considerando essas informações e o conteúdo estudado sobre (insira o tema da questão), pode-se afirmar que:
    - R : Letra E. a modelagem dimensional tem como principais itens: fato, métricas e dimensões. 
- Q_i
    - P : As dimensões utilizadas em um Data Warehouse representam as possíveis formas de visualizar os dados. Em outras palavras, as dimensões podem ser consideradas perspectivas de observação (ou seja, pontos de vista diferentes) de um determinado fato (um tópico de interesse, como vendas) para um negócio. Considerando essas informações e o conteúdo estudado sobre Data Warehouse, pode-se afirmar que:
    - R : Letra B. ano e região são dimensões em um modelo dimensional.
- Q_i
    - P : Leia o trecho a seguir: “Um Data Warehouse é um armazém de dados, um repositório integrado que permite o armazenamento de informação relevante para a tomada de decisão. Estes repositórios podem ser analisados utilizando ferramentas On-Line Analytical Processing (OLAP) e/ou ferramentas de Data Mining.” Fonte: SANTOS, M.; RAMOS, I. Business Intelligence: Tecnologias da informação na gestão de conhecimento. [s.l.], 2006. p. 47. I. A análise de grandes quantidades de dados para transformá-los em informações relevantes é uma atividade de Data Warehouse importante para as empresas. Porque: II. O processo de tomada de decisão que pode vir a identificar possíveis tendências de mercado pode ser realizado com o auxílio da ferramenta OLAP. A seguir, assinale a alternativa correta:
    - R : Letra E. A proposição I está correta, pois Data Warehouses são armazéns de dados que analisam grandes quantidades de dados e são muito relevantes no mundo empresaria. A proposição II também está correta e complementa a proposição I, pois os Data Warehouses tem o objetivo de realizar consultas mais sofisticadas em ferramentas OLAP que tragam mais valor para o nível gerencial de empresas. Levando a dimensão “tempo” em consideração, os Data Warehouses conseguem tirar dos dados informações que podem definir
- Q_i
    - P : Uma das maneiras de representar um Banco de Dados relacional é utilizando um esquema relacional. O esquema é usado para representar a tabela, seus atributos, chaves-primárias e chaves estrangeiras (as quais são usadas para definir os relacionamentos). Considerando essas informações e o conteúdo estudado sobre modelagem relacional de dados, pode-se afirmar que:
    - R : Letra D. Aluno (nome_completo, CPF, matrícula, data_de_nascimento, #codigo_curso) é um exemplo de esquema relacional.
- Q_i
    - P : No modelo relacional, utiliza-se o conceito de conjuntos de valores (domínios) de Atributos. “Cada atributo simples de um tipo entidade está associado a um conjunto de valor (ou domínio de valores) que determina o conjunto de valores válidos para os atributos de cada entidade.” Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 92. Considerando essas informações e o conteúdo estudado, pode-se afirmar que:
    - R : Letra A. o domínio do atributo nome pode ser um conjunto de caracteres do alfabeto brasileiro com, no máximo, 50 caracteres

- Q_i
    - P : Leia o trecho a seguir: “Uma relação é definida como um conjunto de tuplas. Por definição, todos os elementos de um conjunto são distintos, por isso, todas as tuplas da relação também devem ser distintas”. Nesse contexto, a chave primária é um dos conceitos mais importantes em Banco de Dados. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 94. Considerando essas informações e o conteúdo estudado sobre bancos de dados relacionais, pode-se afirmar que:
    - R : Letra A. a chave primária identifica uma tupla de forma única

- Q_i
    - P : No modelo relacional, todos os valores em uma coluna são do mesmo tipo de dado. Na terminologia formal, uma linha é chamada tupla, um cabeçalho de coluna é conhecido como atributo, e a tabela é chamada relação. O tipo de dado que descreve os tipos de valores que podem aparecer em cada coluna é representado pelo domínio de valores possíveis. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 89. Considerando essas informações e o conteúdo estudado sobre modelo relacional, pode-se afirmar que:
    - R : Letra B.  Miguel”, 0999189, 12/09/1998 representam uma tupla.
- Q_i
    - P : Leia o trecho a seguir: A estrutura complexa das bases de dados relacionais faz com que a atenção dos gestores de empresas esteja centrada nos obstáculos encontrados nas tabelas e na programação em SQL para obter informações importantes sobre seus negócios. Nesse contexto, surgiram os Data Warehouse, que são considerados armazéns de dados que guardam informações históricas e relevantes sobre as atividades de uma determinada empresa. Fonte: CALDEIRA, C. Data Warehousing: conceitos e modelos. [s.l.], 2012. p. 19. Considerando essas informações e o conteúdo estudado sobre Data Warehouse, pode-se afirmar que:
    - R : Letra A. Data Warehouse permite a análise de grandes volumes de dados de uma empresa e auxilia no processo de tomada de decisão através das ferramentas de análise OLAP (Online analytical Process). Essas ferramentas observam os fatos (por exemplo, vendas) sob várias perspectivas (dimensões). Assim, o fato vendas pode ser analisado pela ferramenta de acordo com uma região específica ou de acordo com um período de tempo específico.
- Q_i
    - P : As chaves estrangeiras são um dos conceitos mais importantes de um Banco de Dados. “Elas são um tipo de atributo usado para representar os relacionamentos”. Fazendo com que duas tabelas estejam ligadas. Fonte: ELMASRI, Ramez et al. Sistemas de banco de dados. São Paulo: Pearson, 2005. p. 97. Considerando essas informações e o conteúdo estudado sobre bancos de dados relacionais, pode-se afirmar que:
    - R : Letra C. a chave estrangeira é uma referência a um atributo de outra tabela

# Tipos de Dados e Estrutura de Dados

## Tópicos Abordados

- Tipos de Dados Primitivos
    - Variáveis
- Linguagem Java 
        - Inserindo Classes
    - Estruturas Compostas Homogêneas
        - Vetor
        - Matriz
    - Estruturas Compostas Heterogêneas
        - Instanciação
        -  Atribuição
    - Tipos Abstratos de Dados (TADs)
        - Lista, Pilha e Fila
        - Tipos de Armazenamento
        - Coleções
        - Exemplo do Uso de Coleções

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Um algoritmo pode ser também definido como um conjunto de passos para a resolução de um problema ou para a execução de uma tarefa. Existem diversas formas de classificar algoritmos, por exemplo: pseudocódigo, fluxogramas, descrição narrativa e linguagem de programação. Considerando o que foi estudado na unidade, observe uma representação de algoritmo abaixo: 1 - Entre na sala 2 - Busque o interruptor 3 - Acenda a luz, através do ligamento da chave do interruptor. De acordo com o texto-base, a representação de algoritmo lida acima pode ser classificada como:
    - R : Letra D.  Descrição narrativa.
- Q_i
    - P : A linguagem Java é uma das principais linguagens utilizadas comercialmente, e seu formato possui características que facilitam a programação, fazendo com que ela seja multiplataforma e utilizada em mais de 3 bilhões de dispositivos no mundo. Ainda que seja uma linguagem utilizada em diversas organizações, ela possui padrões, como toda linguagem. No caso específico de Java, seu padrão orientado a objetos traz propriedades de herança, polimorfismo e encapsulamento. Considerando essas informações e o conteúdo estudado, podemos afirmar que a forma correta do código-fonte do Objeto que implementa encapsulamento é
    - R : Letra E. class Obj{ private int x; public void setX(int aux){x=aux;} public int getX(){return x;} } 
- Q_i
    - P : O jogo de damas é um jogo de tabuleiro muito popular, que possui diversas regras dependendo da localidade. Seu tabuleiro possui formato 8x8, com 64 casas que variam entre pretas e brancas. Uma das características do tabuleiro são as duas grandes linhas transversais que vão de uma ponta a outra. A linha transversal da esquerda é preta e a da direita é branca. Considerando essas informações e o conteúdo estudado, qual comando em Java poderia ser utilizado para criar uma matriz que pudesse representar um tabuleiro no computador.
    - R : Letra A. int tabuleiro[][]=new int[8][8]
- Q_i
    - P : Em Java, uma Collection é uma API que contém diversos objetos que podem ser usados, tais como Pilha, Fila, Árvore, Arrays e Mapas. Embora todas essas estruturas contenham alguns comportamentos padrões, como add, remove, contains, cada uma funciona de maneira diferente. Os Maps contêm complexidades diferenciadas dos demais, pois requerem uma chave (key) para poder trabalhar qualquer operação. Considerando essas informações e o conteúdo estudado, podemos afirmar que o pacote correspondente ao import da Collection dentro do Java é:
    - R : Letra C. java.util
- Q_i
    - P : Um vetor é uma estrutura que possui apenas uma tipagem primitiva com profundidade ‘n’, podendo armazenar diversos dados do mesmo tipo. Ele é usado para representar estruturas estáticas, e uma das suas principais vantagens é a possibilidade de saber a quantidade dos elementos e a posição onde cada um se encontra armazenado. A partir das informações trazidas no texto-base e do conteúdo estudado, se considerarmos um vetor do tipo int para armazenar números relativos à quantidade, podemos afirmar que a estrutura composta desse tipo de dado é:
    - R : Letra A.  Homogênea.
- Q_i
    - P : Uma matriz é uma estrutura que inicia-se a partir de duas dimensões, ou seja, dois colchetes (“[][]”). Nos casos em que há apenas um (“[]”), trata-se de vetor. As matrizes possuem as mesmas propriedades de vetor e sua navegação se dá por loops dentro de suas posições. Seu loop geralmente se inicia pelo primeiro colchete, avançando um por vez para os próximos colchetes, que navegam de item a item. Para navegar em uma matriz de duas dimensões, primeiro se navega em suas linhas, depois em suas colunas. No caso de uma matriz de 3 dimensões, como “matriz[x][y][z];”, o número de laços de repetição aninhados que o algoritmo deve possuir para navegá-la é:
    - R : Letra B. 3
- Q_i
    - P : O tipo de dado colocado em uma estrutura é o que pode definir todo o algoritmo em termos de velocidade no processador. Dependendo do dado a ser trabalhado, no entanto, não há muitas possibilidades de escolha. A Cadeia, por exemplo, é usada para armazenar letras e caracteres especiais, e não há substituto para ela em situações nas quais se deve armazenar nomes, palavras ou letras. Esse tipo de dado, porém, é naturalmente mais lento, considerando que para o computador formar cada letra é necessário que ele faça um conjunto de cálculos. A escolha do tipo de dado em uma estrutura leva em consideração alguns aspectos. Tendo isso em vista, associe cada aspecto abaixo a seu correspondente. 1) Identificador. 2) Tipo de armazenamento. 3) Velocidade em inserir dados. 4) Algoritmo de ordenação e localização de dados. ( ) O nome pelo qual a estrutura será identificada geralmente possui ligação com sua aplicação do mundo real. ( ) Se serão armazenados números, letras, valores lógicos etc. ( ) Velocidade medida geralmente em milissegundos, podendo variar dependendo do tipo de estrutura escolhida. ( ) Existem muitos algoritmos específicos para cada tipo de estrutura, que dependem da sua aplicação. Embora, às vezes, estruturas demorem mais em ordenar, elas também podem ser mais velozes em localizar os dados. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B. 1, 2, 3, 4.
- Q_i
    - P : As variáveis são espaços em memória, com identificador, que podem ser utilizadas por um conjunto de instruções. Dependendo da instrução, pode-se qualificar esse espaço de memória em um formato capaz de receber os dados provenientes desse espaço. Há, por exemplo, a variável com alocação inteira, que tem como característica aceitar somente números exatos, não-fracionados. Esse tipo de variável é muito utilizado para quantidades e representações numéricas do mundo real Considerando as variáveis da linguagem de programação Java, pode-se classificar uma variável int como:
    - R : Letra B. Tipo primitivo 
- Q_i
    - P : As linguagens orientadas a objetos, como Java, possuem instruções que buscam simular aspectos da vida real, transformando cada item em entidades computáveis nas quais são denominadas classes. Essas entidades possuem ações que na programação chamamos de funções ou métodos, além de propriedades denominadas de atributos ou variáveis, mas que, na memória, transformam-se em conjunto de instruções. Considerando uma sintaxe simples, com uma apresentação na tela da palavra “Teste!”, pode-se afirmar que o método iniciado ao executar a classe e apresentar essa palavra é:
    - R : Letra B. main
- Q_i
    - P : Uma classe em POO é um conjunto de instruções que primeiramente são abstraídas do mundo real. Uma situação como a primeira aula de uma escola, por exemplo, pode ser nomeada como AulaPrimeira, PrimeiraAula ou Aula1 em uma classe a partir de um primeiro contato com programação. Conforme se aprofunda em POO, torna-se possível transformar a nomenclatura para vetor de Aula ou para uma Collection de Aula em vez de usar Aula1. De acordo com essa abstração de aula, veja o código abaixo. public < comando2> { < comando3> static < comando4> < comando5> (String []args) { //comandos } } A partir das informações contidas no texto-base, a ordem das palavras a serem inseridas no código que descreve a abstração de aula é:
    - R : Letra C. class Aula1 public void main.
- Q_i
    - P : Os sistemas de informações podem ajudar uma organização a se posicionar no mercado, operando a partir de um conjunto de pessoas, dados, regras procedimentos, processos e outros sistemas. Há um conceito que representa a menor quantidade de informação contida em um computador, em sua forma mais primitiva: o binário. Ele opera através da conversão do sinal analógico para o digital, podendo ser composto por um conjunto de bits, números, letras ou caractere especial, tomando como forma a menor partícula da informação. De acordo com as informações apresentadas no texto base, pode-se afirmar que o conceito descrito acima chama-se:
    - R : Letra C. Dado
- Q_i
    - P : A sintaxe (conjunto de regras e padrões de uma linguagem) do Java é baseada em um padrão de linguagens de programação e script chamado ECMA 262, um padrão que outras linguagens utilizam. O ECMA opera de maneira similar ao modo como um ISO ou W3C definem normas e regras. Embora tenha esse padrão em algumas plataformas, ele pode ser programado de maneira individual, como no uso de uma API específico do Sistema Operacional Microsoft Windows ou Linux. Nesse caso, mesmo estando no padrão ECMA, deve-se obedecer a plataforma que está sendo usada. Para uma declaração de variável, sua instrução é padrão e deve seguir uma sequência específica na ordem: String nome = “Josué” ; Considerando essas informações e o conteúdo estudado, ordene as etapas a seguir: ( ) É o tipo primitivo da linguagem. ( ) É o identificador da variável ou nome da variável. ( ) Símbolo de atribuição. ( ) Valor a ser atribuído na variável idade. ( ) Delimitador, ou seja, o final da instrução. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D. 1, 2, 3, 4, 5.
- Q_i
    - P : Dados, informação e conhecimento possuem, na computação, aspectos diferentes que podem fazer com que uma estrutura possa se comportar de maneira diferenciada dependendo da forma. Por exemplo: o dado é a menor partícula da computação e trabalha desde o binário até formar uma letra ou palavra. Após concluída essa etapa, organiza-se um conjunto de dados para formar uma informação que a partir de uma frase ou um parágrafo. O conhecimento é o cruzamento e relação entre diferentes frases, parágrafos e palavras. Veja os exemplos abaixo: 1- “José” – 123 – 00FF33 2- 3.141516 – true - false 3- “Há dez anos, no mês de janeiro, chove a partir de 5 centímetros neste alqueire de Saint Petersburg.” Considerando o texto-base, os exemplos listados de 1 a 3 acima podem ser classificados, respectivamente, como:
    - R : Letra C. dado, dado e conhecimento.
- Q_i
    - P : Leia o trecho a seguir: “A média de um conjunto de valores numéricos é calculada somando-se todos estes valores e dividindo-se o resul que é igual ao número de elementos do conjunto, ou seja, a média de n números é sua soma dividida por n.” Fonte: Só Matemática. Média aritmética simples. 2019. Disponível em . Acesso em: abr. 2019. De acordo com a definição de média, observe abaixo um exemplo de algoritmo que recebe dois valores e fornece sua média: Algoritmo Media Declarações n1,n2,Media: Real INICIO Leia (n1) Leia (n2) Media< - ??????????? Escreva( Media) FIM Considerando o algoritmo acima, a instrução correspondente à média aritmética para a variável Média é:
    - R : Letra A. Media<- (n1 + n2 ) / 2 
- Q_i
    - P : Cada linguagem de programação possui sua sintaxe, ou seja, as regras responsáveis por gerar um código objeto para ser executado no processador. No caso de Java, seu código objeto é executado pela JVM (Java Virtual Machine), é uma máquina virtual que executa diretamente os programas elaborados em Java. Considerando essas informações e o conteúdo estudado, pode-se afirmar que o código para uma declaração de variável em Java, do tipo inteiro e que receba o número 33, é:
    - R : Letra A. int idade = 33 
- Q_i
    - P : Uma matriz é uma estrutura composta homogênea, que possui no mínimo duas dimensões. Nesse caso, a quantidade de dimensões pode variar dependendo da linguagem de programação. A matriz, assim como o vetor, possui uma tipagem. Além disso, basicamente todas as propriedades de vetor cabem em matriz, mas em escala maior. Ou seja, enquanto o vetor possui apenas uma dimensão, a matriz possui de duas até ‘n’ dimensões, e a cada dimensão há um colchete “[]” para representá-la. Considerando essas informações e o conteúdo estudado, é correto afirmar que a forma correta de inserir dados na matriz, na linguagem de programação Java, é:
    - R : Letra E. matriz[linha][coluna]=valor; 
- Q_i
    - P : O vetor é uma das estruturas mais simples de se utilizar para armazenamento de dados. Porém, em contrapartida, para uma comparação ou busca de seus elementos deve-se verificar todos os itens nele armazenados. Para verificar todos os itens utiliza-se a navegação, termo da computação que busca entrar em uma estrutura de dados e mostrar seus itens. Para navegar em uma estrutura vetorial utiliza-se o loop, pois se trata de um elemento que contém um início e um fim. Observe o exemplo: for(int cont=0;cont <=10;cont++) { vet[cont]=cont+1; System.out.println(vet[i]); } Considerando as informações do texto-base e o conteúdo estudado, podemos afirmar que, ao executar o loop acima, o que ocorrerá com o vetor na posição 3 quando a variável cont estiver com valor 3 é:
    - R : Letra A.  vet[3] = 4;
- Q_i
    - P : Um tabuleiro de xadrez possui 8x8 de casas, variando entre pretas e brancas. Uma das características do tabuleiro é a existência de duas grandes linhas transversais que vão de uma ponta à outra. A linha transversal da esquerda é preta e a da direita é branca. Embora o desenvolvimento do tabuleiro possa ser aplicado em um vetor, também é possível aplica-lo em uma matriz. No caso de uma matriz, sua declaração seria matriz[8][8]. Pensando em termos de cor, para identificar que uma casa é preta armazenaríamos 1 e, para branco, 0. No caso da linha transversal da esquerda, as linhas e as colunas, nas posições abaixo, iriam gravar 0, os elementos da matriz a serem gravadas 0 são: tabuleiro[0][0], tabuleiro [1][1], tabuleiro[2][2], tabuleiro[3][3], tabuleiro[4][4], tabuleiro[5][5], tabuleiro[6][6] e tabuleiro[7][7]. De acordo com o texto-base, a operação que poderia ser usada no loop para armazenar as cores brancas, considerando o i como o início do loop que navega na linha, é
    - R : Letra E. tabuleiro[i][i]=0
- Q_i
    - P : Em geral, os programas contêm dados armazenados que podem corresponder a tipos diversos de acordo com a necessidade. Sendo assim, cada dado possui um formato e uma regra específica, considerando o que será alocado em memória. Nesse caso, são pensados que tipo de caracteres, letras e números podem ser usados na classificação Cadeia. Para dados que podem assumir apenas dois valores, como por exemplo “Verdadeiro” e “Falso”, o tipo mais utilizado é o Lógico. A partir das informações trazidas no texto-base, afirma-se que um cadastro de dados envolvendo números flutuantes ou fracionados terá como classificação de variável e dado o termo:
    - R : Letra C. Real
- Q_i
    - P : Todo objeto ou entidade do mundo real possui diversas características numéricas e alfanuméricas. Não se pode, em uma estrutura de dados, trabalhar sempre com o mesmo tipo de informação. A partir disso, analise a seguinte situação: Considere um cadastro de clientes que envolva o seguinte conjunto de dados: nome do tipo String; idade do tipo int. e e-mail do tipo String. Considerando as informações do texto-base e o conteúdo estudado, pode-se afirmar que o seguinte tipo de dado seria ideal para armazenar essa entidade:
    - R : Letra E. Estrutura heterogênea de dados.
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
- Q_i
    - P : 
    - R : Letra
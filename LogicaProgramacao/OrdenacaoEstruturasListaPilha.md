# Técnicas de Ordenação, Estruturas de Lista e Pilha

## Tópicos Abordados

- Algoritmos Recursivos
- Técnicas de Ordenação
    - Bubble Sort
    - Insertion Sort
    - Selection Sort
    - Quick Sort
- Estruturas Lineares
    - Listas
        - Lista Estática
        - Lista Ligada
            - Código Lista Ligada
        - Lista Duplamente Ligada
            - Código Lista Duplamente Ligada
        - Lista Collection
    - Pilhas
        - Código de Pilha com Alocação Estática
        - Collection Classe Stack
    - Ordenando Collection


## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Os métodos de alocação dentro dos sistemas muitas vezes determinam a performance e a quantidade de recursos para o uso. Além disso, a questão do algoritmo a ser utilizado pode variar muito. A forma tradicional se utiliza de vetores que são estruturas indexadas, enquanto a outra forma utiliza Nós, que são estruturas referenciáveis, de acordo com as quais não se determina sua quantidade. De tal modo, há uma forma de alocação que permite que qualquer estrutura tenha um tamanho máximo para inserção de elementos. Para que possa manter a estrutura do vetor, quando entra em contato com essa forma, o programador é, em geral, levado a buscar soluções momentâneas. Considerando o texto-base e os conteúdos estudados, é possível afirmar que a alocação descrita no exemplo acima denomina-se:
    - R : Letra B. estática
- Q_i
    - P : O vetor é uma estrutura de dados que recebe os dados de forma aberta e sem critério. Esse formato faz com que, em geral, dados sejam desordenados conforme são inseridos, de modo que os dados devam ser ordenados posteriormente. Veja abaixo um exemplo de comportamento de um algoritmo: Tem por objetivo a ordenação dos dados a partir de 2 em 2, trocando sempre o maior valor pelo menor valor e percorrendo o vetor por diversas vezes. De acordo com o texto-base e os conteúdos estudados, é possível afirmar que o nome do algoritmo descrito no exemplo é:
    - R : Letra A. Método Bubble Sort.
- Q_i
    - P : Para imprimir os valores da lista ligada, é necessário fazer um LOOP dentro da primeira estrutura até a última, entrando em um Nó especifico. Por meio da referência do próximo, navega-se até a última referência, que é o null, através do método getProximo(). Considerando o texto-base e os conteúdos estudados, é correto afirmar que o nó específico utilizado para navegar em toda a estrutura é:
    - R : Letra E. primeiroNo 
- Q_i
    - P : A Lista Ligada e Duplamente Ligada possui a função isEmpty(), uma função cuja convenção mundial de programadores determina que é uma nomenclatura que significa, literalmente, “está Limpa ?”. Nesse caso, ela retorna true para sim, e false para não, considerando que “limpa” ou “não limpa” determina se ela está cheia. No caso da isEmpty, por representar um atributo booleano, é a única exceção, dentro da programação orientada a objetos, que não utiliza geter’s e seter’s no encapsulamento. Agora analise o código da função a seguir, sabendo que primeiroNo é uma classe Node. public boolean isEmpty() { return primeiroNo; } A partir dessas informações e dos conteúdos estudados, analise as alternativas a seguir sobre o código acima. I. A linha do return poderia ser substituída por (primeiroNo == null) ? true : false. II. O objeto primeiroNo é uma instância da classe Lista. III. O tipo de retorno de isEmpty() está de acordo com o tipo do valor que armazena a estrutura. IV. O objeto primeiroNo representa a ocorrência de algum nó na estrutura. V. A função retorna a quantidade de elementos da estrutura.
    - R : Letra I e IV.
- Q_i
    - P : Na API Collection, da Linguagem Java à Lista Ligada, existe uma Classe escrita chamada LinkedList, que possui os mesmos comportamentos que a Lista Ligada. Seu código, porém, é todo encapsulado, tornando acessíveis apenas os métodos. Embora em todas as classes na Collection os comportamentos possuam o mesmo nome, em cada classe ou estrutura seu funcionamento é diferente. Assim, considerando as informações apresentadas e os conteúdos estudados, analise as operações a seguir e associe-as com suas respectivas características: 1) contains. 2) add. 3) remove. 4) clear. 5) size. ( ) Remove elementos da estrutura. ( ) Insere elementos na estrutura. ( ) Busca elemento na estrutura. ( ) Retorna quantidade de elementos na estrutura ( ) Limpa a estrutura , removendo todos os seus elementos Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra A. 3, 2, 1, 5, 4.
- Q_i

            P : Considere uma situação em que ocorre a utilização do método bubble sort em um vetor int desordenado com os seguintes números: 10-9-7-4 Agora, observe o código-fonte a seguir: 
                int vetor[]= new int[4]; 
                for(int contadorL=0; contadorL< vetor.length-1 ; contadorL++) { 
                    for(int contadorC=contadorL+1; contadorC< vetor.length ; contadorC++) { 
                        if(vetor[contadorL]> vetor[contadorC]) { 
                            int aux= vetor[contadorL]; 
                            vetor[contadorL]=vetor[contadorC]; 
                            vetor[contadorC]=aux; 
                        } 
                    } 
                }
            Com base nessas informações e no conteúdo estudado, ao 
            acontecer a primeira troca, o estado atual do vetor será:

    - R : Letra E. 9-10-7-4.
- Q_i
    - P : A Pilha em formato de alocação estática implementa fortemente o vetor, trazendo suas características. De forma geral, os métodos que são acessados, tanto na alocação estática, quanto na dinâmica, possuem o mesmo nome e fornecem o mesmo resultado. A diferença se dá na sua estrutura. Observe o código da função peek ou topo a seguir: public class Pilha { private int vetorPilha[]; private int topo; public int peek() { // COMANDO ________________________ } ... } Considerando essas informações e seus conhecimentos sobre a alocação estática da Pilha, pode-se afirmar que o código que completa a função peek ou topo é:
    - R : Letra D. return vetorPilha[topo]; 
- Q_i
    - P : A Pilha é uma estrutura de dados que possui o formato de organizações de dados LIFO – Last In First Out, ou seja, o último que entra é o primeiro que sai. Esse formato de organização permite que essa estrutura se comporte como uma pilha no mundo real e, na programação, seu comportamento é denominado como “operação” em algumas literaturas. Assim, considerando as informações apresentadas e os conteúdos estudados, analise as operações a seguir e associe-as com suas respectivas características: 1) isFull() 2) pop() 3) peek() 4) isEmpty() 5) push(X) ( ) Acessa o topo da Pilha sem removê-lo. ( ) Aloca ou adiciona o valor na estrutura Pilha. ( ) Retorna ao estado atual da Pilha. Se possuir itens alocados, utiliza-se false, se não possuir, retorna true. ( ) Desempilha ou remove o valor do topo da Pilha, retornando o valor pela função. ( ) Em uma situação de Pilha estática retorna true, se estiver com todos os seus elementos alocados, e false, se ainda tiver espaços. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B.  3, 5, 4, 2, 1. 
- Q_i
    - P : A recursão é uma técnica da programação que faz com que uma função se referencie. Muitos algoritmos não usam recursão, utilizando loops no lugar. Porém, tudo que pode ser recursivo pode ser um loop. Uma das aplicações de recursão se dá no algoritmo que está contido na descrição abaixo: Esses algoritmos consistem na aplicação do método dividir e conquistar. Aplicando recursão, divide-se o vetor em partes, buscando um valor arbitrário chamado de pivô. Os valores ordenados à direita são maiores que o pivô, enquanto os valores à esquerda do pivô são menores, o que é chamado de forma recursiva. Faz-se, assim, a mesma ordenação entre as Subarrays. Considerando o texto-base e os conteúdos estudados, pode-se afirmar que o nome do algoritmo descrito é:
    - R : Letra D. Quick Sort.    
- Q_i
    - P : A Lista Duplamente Ligada possui muitas similaridades com a Lista Ligada. A função buscar recebe o valor do tipo da lista via argumento e faz uma varredura dentro da estrutura do Node, procurando o valor que foi recebido. Caso encontre o valor do Node, ele imprime o valor em tela “Encontrado:”, e retorna true, afirmando que foi encontrado o valor. Caso contrário, aparecerá “Não Encontrado:” o valor, e retornará false. Observe o código fonte a seguir: public boolean buscar(int aux) { No atual = primeiroNo; while (atual != null) { if ( _____________ ) { System.out.println("Encontrado:"+aux); return true; } atual = atual.getProximo(); } System.out.println("Não Encontrado:"+aux); return false; } Com base nessas informações e nos conteúdos estudados, pode-se afirmar que a função que entra no comando if é:
    - R : Letra C. aux == atual.getValor()
- Q_i
    - P : A ordenação está presente em diversas linguagens de programação e é um dos tópicos de Estrutura de Dados, que visa ordenar dados desordenados. Existem muitos algoritmos para ordenação de dados, e esses algoritmos se comportam de maneiras diferentes: há algoritmos que utilizam recursão, funções, loops e buscas. Assim, e considerando os conteúdos estudados no livro da disciplina, analise as afirmativas a seguir sobre as características dos métodos de ordenação de algoritmos. I. O tempo é importante para a ordenação. II. A ordenação pode conter troca de dados. III. Alguns algoritmos usam recursão, enquanto outros usam somente loops, ou a mescla entre eles. IV. O uso de objeto Collection é padrão para todas as linguagens. Está correto apenas o que se afirma em:
    - R : Letra E. I, II e III
- Q_i
    - P : A ordenação está presente em diversas linguagens de programação e é um dos tópicos de Estrutura de Dados, que visa ordenar dados desordenados. Existem muitos algoritmos para ordenação de dados, e esses algoritmos se comportam de maneiras diferentes: há algoritmos que utilizam recursão, funções, loops e buscas. Assim, e considerando os conteúdos estudados no livro da disciplina, analise as afirmativas a seguir sobre as características dos métodos de ordenação de algoritmos. I. O tempo é importante para a ordenação. II. A ordenação pode conter troca de dados. III. Alguns algoritmos usam recursão, enquanto outros usam somente loops, ou a mescla entre eles. IV. O uso de objeto Collection é padrão para todas as linguagens. Está correto apenas o que se afirma em:
    - R : Letra B. p [ A ] 
- Q_i
    - P : Na linguagem de programação, um loop é dividido em início, condição, contador e instrução. Através de referências a suas extremidades, ele executa os códigos que estão dentro de seus domínios, ficando a cargo do compilador identificar o início e o fim do loop. Isso ocorre, sobretudo, ao fazer seu incremento ou decremento (seu passo) para verificar se há condição para executá-lo ou não. Uma função ou método recursivo é um método muito parecido com o loop, salvo algumas distinções: os loops são instruções ou palavras reservadas e toda recursão é uma função, porém que referencia a ela mesma. Observe o código a seguir: public void imprimir(int aux) { if(aux == 0) return; else System.out.println( aux ); impressao(aux--); } De acordo com o texto-base e o conteúdo estudado, é correto afirmar em relação ao código que:
    - R : Letra C.  essa função não é recursiva. 
- Q_i
    - P : A Lista Duplamente Ligada é uma lista de alocação dinâmica baseada na Lista Ligada, porém ela tem como característica possuir referências do seu Nó próximo e Nó anterior. A cada inserção ou remoção de elementos, os atributos anterior e próximo devem ser editados. Para realizar uma navegação nos itens de uma Lista Ligada, alguns procedimentos devem ser realizados. Considerando os conteúdos estudados no livro da disciplina, analise as afirmativas a seguir que descrevem esses procedimentos. I. Cria-se uma recursão para navegar nas estruturas. II. Cria-se uma variável auxiliar do mesmo elemento do primeiro Nó. III. Cria-se um loop até ser menor que o número de elementos contidos. IV. Seta-se o Nó auxiliar para seu próximo Nó. V. Seta-se o Nó auxiliar para seu Nó anterior. VI. Cria-se um loop até o Nó auxiliar ser nulo. Está correto apenas o que se afirma em:
    - R : Letra E. II, IV e VI.
- Q_i
    - P : Ao entrar em uma estrutura da API Collection nas estruturas sequenciais, consegue-se navegar por IDs. Quando se tem as estruturas de conjuntos e mapas, elas navegam via for-each, a partir do padrão de projeto iterator. Considerando uma LinkedList de nome “lista do tipo int.”, a instrução de navegação com o iterator em uma LinkedList nesde formato é:
    - R : Letra D. for(int x: lista){ System.out.println( x);} 
- Q_i
    - P : Uma Pilha de alocação estática possui em sua propriedade uma função, que verifica se seus espaços estão alocados ou não. Esse método, por ser tratar de uma função booleana, retornará true para todos alocados e false para espaço ou espaços em branco. Implementando vetor, a alocação estática tem a vantagem de poder tratar os elementos de forma indexada, fazendo seu acesso ser mais veloz. No formato veloz, por outro lado, não tem essa possibilidade, e deve-se navegar nos elementos para acesso. De acordo com a alocação estática na estrutura Pilha, é possível afirmar que o nome da função que possui essas características é:
    - R : Letra C. isFull() 
- Q_i
    - P : Antes de adicionar elementos à Lista Duplamente Ligada, deve-se, primeiramente, saber em qual extremidade serão inseridos esses elementos. Caso sejam inseridos no início da lista, é preciso haver uma instrução diferente do último item da lista. Com base nessas informações e no conteúdo estudado, pode-se afirmar que correspondem à inserção na última extremidade da Lista Ligada: I. primeiroNode = ultimoNode = new Node(valor, null,null); II. primeiroNode = new Node(valor, primeiroNode,null); III. ultimoNode.setProximo( new Node(valor, null,ultimoNode)); IV. ultimoNode = ultimoNode.getProximo(); Está correto apenas o que se afirma em:
    - R : Letra D. III e IV. 
- Q_i
    - P : O percurso em um Nó é feito sempre pelo seu atributo próximo, independente da sua topologia ou interligações, de acordo com uma varredura em uma Lista Ligada, na qual um elemento referencia outro. Leia o código a seguir: No aux=primeiroNo ; while ( aux !=null ) aux= aux.getProximo(); Assim, e considerando os conteúdos estudados no livro da disciplina, analise as afirmativas a seguir sobre o percurso de um Nó. I. No aux é o último Nó. II. O null representa o último Nó. III. No aux é o primeiro Nó. IV. Esses comandos executam erro. V. Esses comandos não executam erro. Está correto apenas o que se afirma em:
    - R : Letra C. II, III e V.
- Q_i
    - P : Um Nó ou Node é uma estrutura referenciável dentro de uma Lista Ligada, Pilha, Fila ou Árvore. Todo o Node é caracterizado por dois atributos: valor e próximo. Em algumas estruturas ele é diferenciado em direita e esquerda, enquanto em outras há uma lista de referências que pode fazer ligações n com diversos nodes ao mesmo tempo, formando algumas ligações que remetem a topologias como as de rede, por exemplo. Em formato de Programação Orientado a Objetos, um Node é uma classe que utiliza conceitos de encapsulamento. De acordo com os conteúdos estudados e o texto-base, é correto afirmar que uma estrutura caracterizada por auxiliar um elemento de uma lista node a acessar outra lista Node é exemplificada por:
    - R : Letra B. public Node getProximo()
- Q_i
    - P : Algumas técnicas de programação são necessárias para que uma determinada lógica possa ser executada. De forma geral, a lógica de programação utiliza as condições, os loops e funções para poder executar quase todos os algoritmos. Há também uma técnica na programação que permite ao programa criar funções que se auto referenciam, passando argumentos que façam com que a função tenha um critério de parada. Isso ocorre para que possa ser finalizado o ciclo de chamadas pois, caso contrário, ele se transforma em um ciclo sem fim, tornando–se um loop infinito. De acordo com as informações apresentadas no texto base, é possível afirmar que o conceito descrito se chama:
    - R : Letra B. recursao



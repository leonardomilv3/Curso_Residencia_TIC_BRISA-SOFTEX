# Grafos, Pesquisa de Dados e Hash

## Tópicos Abordados

- Grafos
    - Conceitos
    - Matriz de Adjacência
        - Implemetação em Java
    - Lista de Adjacência
        - Implemetação em Java
    - Buscas
        - Busca por profundidade - DFS (Depth-First Search) com PILHA
            - Implemetação em Java
        - Busca em largura - BFS ( Breadth-First Search) com FILA
            - Implemetação em Java
- Pesquisa de Dados (Sequencial e Binária)
    - Busca Sequencial
    - Busca Binária
- Hash (Espalhamento) - Cálculo do Endereço
    - Hashing
    - Hash para Strings
    - HashSet na Collection 

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : 
    - R : Letra C. F-X-G
- Q_i
    - P : A busca binária, é uma busca que tem por objetivo receber uma estrutura ordenada e fazer uma comparação parcial do dado que é tratado com o tamanho da metade da sua estrutura, caso o dado seja maior que a metade da estrutura o algoritmo faz um loop na segunda metade da estrutura, caso seja menor faz um loop na metade da estrutura, esse formato elimina de um total de valores praticamente metade de comparações, tendo como tamanho O(n/2), pois independente de ter o dado ou não na estrutura somente vai percorrer uma metade. Agora, leia o código-fonte a seguir: public static boolean buscaBinaria(int[] vetor, int pesquisar) { if ( … ) { for (int pos = 0; pos < vetor.length; pos++) { if (pesquisar == vetor[pos]) { System.out.println("Localizado"); return true; } } } else { for (int pos = vetor.length; pos > 0; pos--) { if (pesquisar == vetor[pos]) { System.out.println("Localizado"); return true; } } } return false; } Considerando essas informações e o conteúdo estudado, a alternativa que corresponde ao comando IF do código acima é:
    - R : Letra  C. pesquisar >= vetor[(int) (vetor.length / 2)].
- Q_i
    - P : O HashMap é uma estrutura hash diferenciada, pois nela você é obrigado a setar o valor junto com sua posição de memória, no entanto ao instanciar um hashmap, deve-se passar via parâtro da declaração a tipagem do índice e a tipagem do valor, no caso do exemplo abaixo, o índice é integer e o dado também, podendo assumir diversos tipos inclusive um objeto tanto como índice como quanto valor. Por conta da particularidade da inserção do índice junto com o valor a add, no hashmap não é usado e sim o put(indice,valor) para poder alocar, e o uso do constains é diferenciado pois pode-se buscar tanto por chave usando a containsKey quanto por valor containsValue.Por este motivo o hashmap é democrático pois você pode criar as posições que desejar e assim trazer mais agilidade ao programa caso necessite Analise a situação a seguir: import java.util.HashMap; import java.util.Map; public class Prj_HashMap { public static void main(String args[]) { Map mapa=new HashMap(); mapa.put(1, 100); mapa.put(2, 200); System.out.println("remover:"+mapa.remove(2)); System.out.println("contains por chave:"+ mapa.get(1)); System.out.println("contains por chave:"+ mapa.containsKey(1)); System.out.println("contains por valor:"+ mapa.containsValue(100)); for(Integer aux: mapa.keySet() ) { System.out.println(aux + "-" + aux.hashCode() + "-"+ mapa.get(aux) ); } } } Com base nessas informações e no conteúdo estudado, analise as afirmativas a seguir e identifique qual dela(s) corresponde(m) ao padrão iterator na navegação da estrutura Mapa. I. Integer aux: mapa.keySet() II. new HashMap();. III. mapa. IV. mapa.get(aux). V. mapa.getClass(). Está correto apenas o que se afirma em:
    - R : A. Letra I e IV.
- Q_i
    - P : Os vértices ou “nós” são os componentes de um grafo que designam o sentido de uma aresta. Se um grafo não possui vértices, ele não possui arestas. Os vértices, na programação, são classes que não se referenciam, porém possuem algumas propriedades que designam rótulo, focando em alguns algoritmos, no índice ou Ids. Em programação orientada a objetos, temos o encapsulamento que, como o nome diz, encapsula essas propriedades em métodos getters e setters, para cada propriedade, que em classe se torna um atributo. Analise a situação a seguir: class Vertice { private static int indice; private static String nome; boolean static visitado=false;} Com base nessas informações e no conteúdo estudado, podemos dizer que o encapsulamento do atributo índice corresponde a:
    - R : Letra C. public void setIndice (int aux) {...} public int getIndice () {...}
- Q_i
    - P : A pilha é uma estrutura de dados homogênea, que se comporta mais ou menos da mesma forma que uma pilha do mundo real, tendo seus dados organizados na estrutura LIFO (Last in First Out). Uma das aplicações das pilhas é no algoritmo de busca de grafos, no DFS que busca por profundidade, onde sua busca aplica-se em receber um vértice e retornar todos os caminhos atrelados a partir dele. Analise a situação a seguir: public void buscaDFS(Grafo_MA adj) { /*Grafo_MA adj é matriz de adjacência*/ this.resetar(adj); Stack pilha = new Stack<>(); adj.getNo(0).setVisitado(true); pilha.add(adj.getNo(0)); System.out.print(adj.getNo(0).getNome()); while (!pilha.isEmpty()) { /*chamada da função getIDVizinhos com argumentos de matriz de adjacência e o índice do topo da pilha*/ DECLARAÇÃO IDVIZINHO if (idVizinho == -1) { pilha.pop(); } else { adj.getNo(idVizinho).setVisitado(true); pilha.push(adj.getNo(idVizinho)); System.out.print("," + adj.getNo(idVizinho).getNome()); } } } Com base nessas informações e no conteúdo estudado, o código que corresponde à declaração de idVizinho no DFS é:
    - R : Letra E. int idVizinho = this.getIDVizinhos (adj, pilha.peek ().getIndice ());
- Q_i
    - P : Uma das principais aplicações de grafos em um problema de logística é achar o menor caminho para várias entregas. No caso, cada ponto de entrega seria um vértice e cada rua, avenida ou caminho, seriam as arestas. Por ser um problema recorrente em grafos, existem diversos algoritmos para isso. Um deles se destaca por ser um dos mais simples para resolver este problema. Trata-se da árvore geradora mínima ou MST (Minimum Spanning Tree), que percorre os vizinhos até o fim e verifica se algum deles possui uma conectividade com os nós do grafo. Com base nessas informações e no conteúdo estudado, podemos dizer que o algoritmo usado no MST como forma de criar uma árvore geradora mínima é:
    - R : Letra B. DFS ou busca por profundidade.
- Q_i
    - P : Uma das formas de navegar no grafo é através da lista de adjacência, que possui dois atributos: o vértice e a lista de vizinhos. Em vez de armazenar as arestas, armazena os vizinhos. Uma das vantagens da lista de adjacência é que ela não utiliza uma matriz como base e, portanto, pode ter tamanho indefinido. Analise a situação a seguir: public ArrayList buscarVizinhos (Vertice noaux) { return new ArrayList <> (arestas [noaux.getIndice () ]); } No código-fonte acima, há uma criação estática, ou seja, com quantidades fixas de vértices. Foi utilizado um vetor de arestas para poder alocar os vizinhos. Com base nessas informações e no conteúdo estudado, podemos dizer que o comando utilizado para buscar o vizinho de um nó é:
    - R : Letra E.  buscarVizinhos (new Vertice ("A",1)); 
- Q_i
    - P : A estrutura hash possui um dos melhores desempenhos dentro de uma grande estrutura de dados, pois sua notação de big O(1) é uma constante. Ou seja, para N dados, temos apenas um conjunto de instruções a se buscar. Porém, com a grande quantidade de dados, surge o problema da colisão, quando dados diferentes assumem o mesmo valor de hash. Existem formas de trabalhar o hashing para que isso não ocorra, porém, é preciso usar uma outra estrutura de dados para poder considerar um hash repetido de dados distintos. Uma das estruturas possíveis é a linkedlist, que faz a alocação do dado repetido ou aproximado dentro de um mesmo hash. Com base nessas informações e no conteúdo estudado, podemos dizer que a técnica utilizada para a colisão é:
    - R : Letra A.  o encadeamento separado 
- Q_i
    - P : A pesquisa de dados é um tópico da estrutura de dados que envolve o estudo dos algoritmos para sequências numéricas, seja ordenada ou desordenada, em ordem crescente ou decrescente. Neste aspecto surge, dentro da pesquisa de dados, uma ferramenta chamada análise assintótica, que recebe um algoritmo e, pelas próprias instruções, nos fornece uma fórmula matemática para analisar graficamente o comportamento deste algoritmo, em seu pior caso, no computador. Com base nessas informações e no conteúdo estudado, podemos dizer que o melhor algoritmo em pesquisa de dados, de acordo com sua fórmula, é:
    - R : Letra D. O(1). 

<!-- COLOCAR COMO DÚVIDA FÓRUM 

Grafos, Pesquisa de Dados e Hash

-->
- Q_i
    - P : As arestas são a principal forma de manipular e modelar o grafo e, dependendo da aresta, até de classificá-lo como um todo. É um modelo que foca mais nas ligações do que nos dados em si. Em resumo, a aresta é a ligação dos vértices ou nós que, em conjunto, formam um caminho e uma estrutura organizada sem topologia ou ordem de dados.
    - R : Letra E.  A, B e C são orientadas, enquanto D com A não são orientadas. 
- Q_i
    - P : Uma ArrayList é uma estrutura da Api Collection que trabalha com alocação dinâmica, possui aplicação em diversas situações e regras de negócio. No caso dos grafos, sua aplicação pode se dar na representação da lista de adjacência. A lista de adjacência é um formato de representação de grafo, que recebe do grafo um nó e as ligações (ou vizinho) de um nó e os aloca. Quando se trata da alocação de vizinhos, que pode ser fixa ou variável, a lista encadeada ou uma estrutura dinâmica é necessária para poder alocar os vizinhos de um nó. Com base nessas informações e no conteúdo estudado, podemos dizer que o comando usado para adicionar os vizinhos em uma lista de adjacência é:
    - R : Letra B. setAresta (0, new ArrayList <> (Arrays.asList (new Vertice []{new Vertice ("B",1)})));
- Q_i
    - P : s estruturas de dados homogêneas são estruturas que possuem indexação por profundidade, porém com apenas uma tipagem. No caso de matrizes e vetores, independentemente do tamanho “N” que possuam, eles sempre terão a mesma tipagem. Por isso, existem diversas aplicações para essas estruturas, sendo uma delas na forma computacional de manipular um grafo. Na classe grafo, temos os vértices e a matriz de adjacência, que deve ser populada para possuir as arestas. Porém, o grafo em si é iniciado ao executar o construtor, pois este define os tamanhos da matriz da classe. Analise a situação a seguir: class Grafo { private Vertice nos []; private int matriz [] []; public Grafo (Vertice nosaux []) { ... } } Com base nessas informações e no conteúdo estudado, podemos dizer que a linha que corresponde ao comando do construtor do código acima é:
    - R : Letra D.  nos = nosaux; matriz = new int [nosaux.length] [nosaux.length];
- Q_i
    - P : O grafo é uma estrutura que contempla vértices e arestas. Sua estrutura não possui topologia ou ordem específica de inserção, remoção ou edição, pois um dos objetivos primordiais dos grafos é modelar um problema do mundo real. Por esse motivo, diversos tipos de grafos acabam coexistindo, cada um com suas características particulares. Analise a situação a seguir: As escalas da higienização de trens de 5 estações têm sido um grande problema para uma empresa de prestação de serviços. Foi sugerido que seu sistema corporativo tivesse uma funcionalidade que gerasse essas escalas automaticamente, de acordo com as seguintes regras: deve ser em horários de menor movimento, todos os vagões de um trem devem estar a 4 estações de igual tempo de distância um do outro. Com base nessas informações e no conteúdo estudado, uma das possibilidades de grafo para modelar esse case seria um:
    - R : Letra B. grafo orientado.
- Q_i
    - P : As tabelas hash podem ser desenvolvidas à mão, porém, no Java existe a chamada API Collection, que auxilia na aplicação desta estrutura sem necessariamente precisar criar do zero, através da interface SET com a instanciação da classe HashSet (). Embora esteja usando a interface SET, os comandos para inserir, editar, pesquisar e remover possuem, basicamente, a mesma sintaxe para quase todas as coleções. Analise a situação a seguir: import java.util.HashSet; import java.util.Set; public class Prj_Hash { public static void main(String args[]) { Set hasht=new HashSet(); hasht.add(100); System.out.println("remover:"+hasht.remove(100)); System.out.println("contains:"+ hasht.contains(100)); } } Assim, considerando as informações apresentadas e os conteúdos estudados, analise as operações a seguir e associe-as às suas respectivas características: 1) add 2) remove 3) contains 4) iterator 5) isEmpty I. ( ) Remove elementos da estrutura II. ( ) Retorna um objeto navegável através de um padrão de projeto III. ( ) Retorna se contém elementos na estrutura ou não IV. ( ) Busca elementos na estrutura V. ( ) Insere elementos na estrutura Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D.  2, 4, 5, 3, 1.
- Q_i
    - P : A busca sequencial é uma das formas mais simples de trabalhar a estrutura de dados. Seu algoritmo geralmente é um loop e não possui critérios com relação a busca em si. O que temos é somente uma condição para encontrar o dado dentro do algoritmo. Este formato de busca chama-se sequencial, pois percorre todos os elementos da estrutura de forma estática e pode ser usado em vetores e matrizes de forma dinâmica, percorrendo posições de memória ou retornando endereços de objetos diferentes de nulo. Analise a situação a seguir: for(int i=0;i< 5; i++) for(int j=i+1;j< 10; j++) if( ... ) System.out.println("Dado:"+buscar+" localizado"); Com base nessas informações e no conteúdo estudado, podemos dizer que a alternativa que corresponde ao comando IF acima é:
    - R : Letra A. buscar == numeros[i][j]. 

<!-- FIla é FIFO (First In First Out) -->

- Q_i
    - P : A fila é uma estrutura de dados homogênea, que tem por objetivo organizar e alocar os elementos da sua estrutura na forma de LIFO (Last in First Out), fazendo com que o primeiro a ser inserido seja removido. Sua função nos grafos se encontra dentro da busca por largura, removendo o nó visitado e buscando primeiro seus vizinhos em nível, assim, adicionando os vizinhos até chegar nos nós finais. Analise a situação a seguir: A-B-C-D A-E A-F-G-H Com base nessas informações e no conteúdo estudado, podemos dizer que o uso da fila em BFS, nesse caso, é: 
    - R : Letra E.  B-E-F, C-G, D-H. 
- Q_i
    - P : A função hash tem como objetivo tratar os dados como posição de memória. Sendo assim, um dado que não tenha comparações, possuirá apenas uma operação para busca em N dados. Essa função é muito utilizada em dicionários de palavras e outras coisas que precisam analisar muitos dados. Ao utilizar o hash na linguagem Java, cada variável ou objeto possuirá uma posição específica, pois essa numeração surge dos cálculos da JVM (Java Virtual Machine). Com base nessas informações e no conteúdo estudado, podemos dizer que a função para pegar o valor hash de um Objeto Pilha com a tipagem Integer da classe Stack é:
    - R : Letra B. new Stack().hashCode();

- Q_i
    - P : A busca por largura BFS (Breadth-First Search), é um algoritmo de busca em grafos que retorna os níveis dos vizinhos deste o primeiro até o último vértice. Primeiro, ele mostra os vizinhos do nó, depois os vizinhos dos vizinhos e assim até chegar no final. Este formato de busca é ideal para mostrar os níveis de um nó, pois, diferente do DFS, ele mostra todo o caminho de um vizinho até chegar no próximo. Esses dois principais algoritmos de busca como DFS e BFS precisam que a propriedade “visitado” dos nós ou vértices estejam false, pois isso significa que este nó não foi percorrido e, portanto, poderá ser contabilizado. Analise a situação a seguir: public void resetar (Grafo_MA adj) { for (int i = 0; i < adj.size (); i++) { ... } } A função resetar recebe uma matriz de adjacência e transforma em false a propriedade visitado de todos os vértices, através do comando adj.getNo (i), que visita o nó do índice i. Com base nessas informações e no conteúdo estudado, pode-se afirmar que a linha que corresponde à ação de setar como false no código acima é
    - R : Letra D. adj.getNo(i).setVisitado(false);

- Q_i
    - P : O hash é uma estrutura de dados que se fundamenta no conceito de hashing, que, resumindo, trata-se de uma série de cálculos de dados juntamente com a quantidade de espaços disponíveis em memória. Esta técnica é muito utilizada em criptografia de textos, números, dados em geral e até bits. As principais formas de criptografia provêm de uma variação do hashing que carrega não somente o dado, mas a quantidade de bits e constantes (variáveis estáticas), para poder criptografar um dado de forma única. Analise a situação a seguir: public static int getHashCode(int valor, int tamanho){ ---------------- return hashcode; } Com base nessas informações e no conteúdo estudado, podemos dizer que o cálculo do hashing do código acima é:
    - R : Letra E. int hashcode = valor % tamanho;
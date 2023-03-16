# Filas e Árvores: Implementações e Generalizações 

## Tópicos Abordados

- Filas - Implementações
- Collection Class Queue - Fila Dinâmica
- Árvores e suas generalizações
- Árvores Binárias
    - Árvores de Busca
- Árvores Binárias e de Busca
    - Comandos da Árvore de Busca Binária
- Collection Class Tree


## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Quando tratamos de árvores de busca, temos algumas variações. De acordo com a utilidade, podemos ter variações mais velozes e outras mais lentas, porém com eficácia melhor. Tratando-se de buscas, temos as formas de percurso que navegam em toda a estrutura, mas na árvore splay temos um formato diferenciado. De acordo com essas informações e o conteúdo estudado, qual é o maior fator de balanceamento e rotação dentro da árvore que implementa o algoritmo splay?
    - R : Letra E.  muitas buscas.
- Q_i
    - P : A busca em árvore binária é o principal propósito da estrutura, a função de busca denominada buscar, no código abaixo, primeiramente recebe um valor e verifica se a chave do elemento é igual ao valor que está sendo buscado, depois ele retorna o que localizou através da variável true. Leia o código abaixo: public boolean buscar(int valor) { Node aux = this.raiz; while ( aux != null ){ if( aux.chave == valor ) return true; aux = ( ___________ )? aux.esquerda : aux.direita; } return false; } Com base nessas informações e no conteúdo estudado, é correto afirmar que poderia ser utilizado na linha aux:
    - R : Letra B. aux.chave > valor 
- Q_i
    - P : A estrutura de árvore entre parênteses aninhados possibilita que seja representada e escrita em diversos arquivos de textos, no formato demonstrado abaixo. Parece-se com algumas notações que usamos no Microsoft Excel, por exemplo. Mesmo nesse formato, a Raiz é o elemento principal da árvore, fazendo com que seja o “menu” de acesso a todos os elementos. Considere a árvore: (A (B (E)) (D (H (I)) ) ) e o conteúdo estudado, identifique quem é o Pai de B e D:
    - R : Letra A. A
- Q_i
    - P : A Fila Dinâmica da interface Queue possui muitas similaridades com as estruturas dinâmicas de armazenamento. A função buscar recebe o valor do tipo da fila via argumento e faz uma varredura dentro da estrutura de Fila, procurando o valor recebido. Caso encontre o valor, ela o imprime na tela “Encontrado:” o valor e retorna true, fornecendo que foi encontrado o valor; caso contrário, aparecerá “Não Encontrado:” o valor e retorna-se false. Agora, leia o código-fonte abaixo: public boolean buscar(int aux) { Iterator filaIterator = fila.iterator(); while( filaIterator.hasNext()) { if( ________________ ) { System.out.println("Encontrado"); return true; } } System.out.println("Não Encontrado:"+aux); return false; } Com base nessas informações e no conteúdo estudado, assinale a alternativa que completa o comando IF do código acima:
    - R : Letra B.  filaIterator.next()==aux
- Q_i
    - P : A árvore rubro-negra (ou red-black) possui o atributo cor em seus Nodes, por meio do qual o filho se diferencia do pai. Nesse modelo, através do atributo cor, podemos aprofundar-nos nos níveis da árvore. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s): I. ( ) A raiz é black. II. ( ) O valor da chave pode interferir no atributo cor. III. ( ) Os nós terminais são red. IV. ( ) Os nós terminais não seguem a cor do pai. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D. V, F, F, V. 
- Q_i
    - P : A árvore possui muitos elementos interligados conhecidos como Nodes, que são objetos autorreferenciáveis que podem prover diversas formas de representar uma topologia ou interligação de objetos. Uma árvore geralmente armazena seus filhos e um valor que, em terminologia de árvore, pode chamar-se chave. Com base nessas informações e no conteúdo estudado, assinale a alternativa contendo os atributos dos Nodes de uma árvore:
    - R : Letra B.  chave, esquerda e direita. 
- Q_i
    - P : A Fila, tanto estática quanto dinâmica, fornece ao programador o seu estado em relação à quantidade de dados inseridas nela; caso esteja “limpa” ou “vazia”, seu estado é de que não contém elementos. Para o programador saber esse estado, a Fila contém a função isEmpty(), que significa literalmente “está limpa?”. Essa função que determina que se retorne true para sim, e false para não, determinando se ela está cheia. Agora analise a função abaixo, sabendo que qtdElementos é contador de itens da Fila. public boolean isEmpty(){ return (qtdElementos==-1); } Com base nessas informações e no conteúdo estudado, analise as afirmativas a seguir em relação ao código: I. A linha do return poderia ser substituída por (qtdElementos==-1)? true : false; II. O objeto qtdElementos é uma instância da classe Fila. III. O tipo de retorno de isEmpty() é de acordo com o tipo do valor que armazena a estrutura. IV. A qtdElementos fornece a quantidade de elementos da estrutura. Está correto o que se afirma em:
    - R : Letra A.I e IV.
- Q_i
    - P : As filas estáticas são estruturas de alocação estática, ou seja, de tamanho fixo, pois implementam vetor na sua estrutura. No caso dos códigos, usa-se o queue e dequeue como operações que alteram o estado da fila, ou seja, a queue adiciona itens e a queue remove itens da estrutura. Leia as operações abaixo, considerando a estrutura fila: fila.queue(1); fila.queue(2); fila.isEmpty(); fila.queue(3); fila.isFull(); fila.queue(4); fila.peek(); fila.dequeue(); fila.imprimir(); Considerando essas informações e o conteúdo estudado, qual é o estado atual da fila após executar todas as operações?
    - R : Letra B. 2,3 e 4.
- Q_i
    - P : A Fila é um formato de armazenamento ou organização humana que tem por objetivo organizar itens de forma que o primeiro a ser organizado ou “enfileirado” é o primeiro a sair da organização. Considerando essas informações e o conteúdo estudado, é correto afirmar que esse formato de organização é conhecido como:
    - R : Letra C. FIFO. 
- Q_i
    - P : A árvore AVL tem como premissa o balanceamento após as operações de inserção e remoção, fazendo com que cada estado da estrutura seja ideal para os dados armazenados. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) A AVL busca ajustar as estruturas das subárvores, deixando com tamanhos próximos. II. ( ) A AVL maximiza o percurso para buscas. III. ( ) A AVL é lenta em relação a operações de busca. IV. ( ) A AVL é lenta em relação a operações de inserção e remoção. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B.  V, V, F, V. 
- Q_i
    - P : Geralmente as árvores em si possuem formato de alocação dinâmica, mas em sistemas nos quais é preciso trabalhar com alocações estáticas é preciso utilizar uma estrutura composta homogênea em formato de vetor. Com base nessas informações e no conteúdo estudado sobre árvores, analise as afirmativas a seguir: I. A estrutura Node referencia o filho da direita e da esquerda. II. Os filhos à direita de um elemento são referenciados através da multiplicação de sua posição. III. Os filhos à esquerda de um elemento são referenciados através da multiplicação da sua posição mais seu incremento. IV. Os vetores não podem representar uma árvore estática. Está correto apenas o que se afirma em:
    - R : Letra B
- Q_i
    - P : As árvores possuem muitas propriedades e suas propriedades podem ser usadas por muitos algoritmos. Elas são importantes pois, através delas, podemos ter um panorama real de como a estrutura da árvore se encontra. Considerando as informações acima e o conteúdo estudado, analise as afirmativas sobre o(s) item(ns) que corresponde(m) ao termo Floresta: I. ( ) Florestas são conjuntos de nós pais após a Raiz. II. ( ) Floresta é o Nó que possui filhos. III. ( ) Floresta é um conjunto de 0 ou mais árvores. IV. ( ) Floresta é uma Raiz. Está correto apenas o que se afirma em:
    - R : Letra E. I e III. 
- Q_i
    - P : Muitos elementos em várias estruturas possuem formas de ligação, como uma página web com âncoras ou links que apontam para outra página web. Um vetor aponta para seu próximo a partir do seu tamanho máximo e, em outra estrutura, é chamada de grafo com as arestas. Com base nessas informações e no conteúdo estudado, é correto afirmar que, dentro de uma estrutura de árvore binária, o termo para ligação de elementos em seu conjunto é:
    - R : Letra A. arco
- Q_i
    - P : A árvore é uma estrutura que é composta de node e suas ligações, porém sua organização e forma de utilização dependem do algoritmo escolhido, pois, utilizando uma árvore binária, os nós poderão possuir somente dois filhos e, dependendo das regras de balanceamento a cada nó inserido, ocorrerá o realinhamento de todos os nós. A árvore, diferente das demais estruturas, possui diversas propriedades, conceitos e terminologias que não se aplicam a outras estruturas. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s): I. ( ) Node é uma estrutura referenciável que armazena valores dentro de uma árvore. II. ( ) Cada Node possui apenas um Pai. III. ( ) Cada Node pode possuir vários “irmãos”. IV. ( ) Cada Node poderá ter dois antecessores. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C. V, V, V, F. 
- Q_i
    - P : As árvores são estruturas que em si são simples: possuem raiz, pais e filhos. O que diferencia uma árvore da outra é seu formato de trabalho ao inserir nós, suas regras primordiais para que a considere balanceada ou formas de balanceá-la. Cada árvore geralmente tem o nome de uma das suas regras, como, por exemplo, a árvore binária que só pode ter 2 filhos, a árvore rubro-negra que insere atributo cor nos nodes para que haja balanceamento etc. As árvores do tipo 2-3, por exemplo, são árvores diferenciadas que implementam o formato binário, e em alguns casos conseguem ser mais velozes que as demais árvores. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir sobre a árvore do tipo 2-3 e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) possui um pai com um único valor chave. II. ( ) não possui no máximo dois irmãos. III. ( ) não possui apenas um valor na chave. IV. ( ) possui dois pais com dois valores chaves. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C. F, V, V, F.
- Q_i
    - P : A árvore binária é uma aplicação da estrutura árvore, muito utilizada na computação, sobretudo por conta de suas propriedades e característica de balanceamento a cada operação; a princípio, ele se torna lento em muitas adições e subtrações de itens, mas, quando se trata de buscas, torna-se muito veloz, pois pode facilmente verificar quando tem o elemento buscado em si ou não. Considerando essas informações e o conteúdo estudado, analise as afirmativas sobre as propriedades de Nó a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s): I. ( ) O filho à esquerda de um nó tem o valor da chave menor que seu Pai, e o filho à direita possui o valor da chave maior ou igual a seu Pai. II. ( ) Um nó é um conjunto de subárvores ou vazio. III. ( ) Um nó é uma interligação entre dois nós. IV. ( ) Um nó só pode ter de 0,1 até no máximo 2 filhos. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. V, F, F, V. 
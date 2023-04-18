# Estratégias de Busca

## Tópicos Abordados

- Estratégias de Busca
    - Passo 1: definição do problema
    - Passo 2: analisar o problema em busca da(s) técnica(s) mais adequada(s) para sua solução
    - Passo 3: aplicar a melhor técnica de solução
- Busca em Profundidade
    - Aplicações da Busca em Profundidade
- Busca em Amplitude
    - Aplicações da Busca em Amplitude 
- Abordagem Comparativa
- Uso de Heurística
    - Aplicação da Busca Heurística
- Sistemas Baseados em Conhecimento
    - Conhecimento
    - Aplicação dos sistemas

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Ao se abordar a teoria de sistemas baseados em conhecimento, pode-se aplicar um conjunto de regras lógicas que permitam acúmulo de conhecimento. Os agentes inteligentes poderão, então, usar máquinas de inferência e estratégias de busca para acessar esse conhecimento na solução de problemas. Com base nessa afirmação e no conteúdo estudado sobre sistemas baseados em conhecimento, analise as asserções a seguir e a relação proposta entre elas. I. A lógica OU exclusivo, representada por P  Q, pode ser interpretada da seguinte forma com base em uma tabela-verdade: a resposta lógica a duas variáveis de entrada será verdadeira (V) toda vez que as entradas assumirem níveis lógicos diferentes. Porque: II. Segundo o Teorema de De Morgan, a função lógica NOR também pode ser representada por ( P ^  Q). A seguir, assinale a alternativa correta:
    - R : Letra E. As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa correta da I. 
- Q_i
    - P : Em árvores ou grafos de grande porte, as buscas em profundidade ou em extensão podem demorar muito, dado o grande número de nós a ser visitado. Já a busca heurística cria atalhos, pulando de um ramo para outro de acordo com o que se aprendeu com os nós já visitados e, assim, aumentando a possibilidade de encontrar a solução procurada em menos tempo e com menos esforço. A complexidade da busca heurística e o tempo gasto dependem de algumas condições. Considerando essa informação e o conteúdo estudado sobre uso de heurística, é correto afirmar que são condições implicantes nessa busca: I. A eficiência do algoritmo empregado na busca heurística. II. A presença de um agente inteligente presente para utilizar os resultados adquiridos. III. As eventuais regras que formam os nós dos grafos. IV. O quão complexo é o grafo em que se dará a busca. Está correto apenas o que se afirma em:
    - R : Letra B. I, III e IV. 
- Q_i
    - P : Para a solução de um problema qualquer, particularmente para aqueles de interesse para a Inteligência Artificial, podemos dizer, com alguma generalização, que devemos nos orientar por três passos na difícil tarefa de estruturar uma resposta ao problema. Considerando essa afirmação e o conteúdo estudado em estratégias de busca, é correto afirmar que:
    - R : Letra E. o primeiro passo deve ser sempre a definição precisa do problema: etapa em que definimos os estados iniciais e os estados finais nesse processo de solução do problema.
- Q_i
    - P : Quando nos referimos aos quantificadores utilizados em lógica proposicional, sabemos que o quantificador universal, representado por ∀, indica que a sentença é verdadeira para todos os valores da variável, por exemplo, ∀ X gosta (X, sorvete) é verdadeiro para todos os valores do domínio da definição de X. Por outro lado, o quantificador existencial, representado por ∃, indica que a sentença é verdadeira para pelo menos um valor do domínio, por exemplo, ∃ Y amigos (Y, Maria) é verdadeiro se existir pelo menos um objeto indicado por Y que seja amigo de Maria. De acordo com o texto e com o conteúdo teórico abordado, a sentença lógica proposicional “∀ X  ∃ Y sobre (Y, X)  livre (X)”, apresenta como tradução correta o que está descrito em:
    - R : Letra B. para todo X, X está livre se não houver um Y, tal que Y esteja sobre X.
- Q_i
    - P : Alguns fatores devem ser levados em consideração para se definir qual o tipo de busca mais adequada ao problema em questão. Por exemplo, problemas que apresentam árvores de busca muito profundas, e que não sejam previamente conhecidas, quando explorados pelo tipo de busca inadequado, podem gastar recursos computacionais e tempo de busca proibitivos em uma situação prática Com base no texto e em conhecimentos previamente obtidos sobre estratégias de busca, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) A técnica da busca em profundidade é adequada para problemas com árvores profundas, cuja profundidade é previamente conhecida e com recursos computacionais adequados. II. ( ) Na busca em amplitude, o nó raiz é expandido primeiro. Todos os nós de uma dada profundidade são expandidos antes daqueles do nível seguinte, por isso o problema com árvore rasa é adequado para essa busca. III. ( ) Tanto a técnica da busca em profundidade quanto a busca em amplitude são adequadas quando a árvore de busca de um problema é profunda e previamente conhecida. IV. ( ) A busca heurística utiliza algum conhecimento sobre o problema em forma de custo e opta por aquela de menor custo. Como consequência, realiza aprendizagem no processo e otimiza a busca. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. V, V, F, V.
- Q_i
    - P : Dado um certo número natural, o cálculo de seu fatorial pode ser obtido por multiplicação sucessiva. Por exemplo, caso o número natural dado seja 4, então, teríamos como resultado do fatorial o seguinte resultado: 4! = 4 x 3 x 2 x 1 = 24. Para o número 3, o resultado será: 3! = 3 x 2 x 1 = 6. Percebendo-se que, para cada novo cálculo fatorial, automaticamente, poderíamos armazenar os cálculos intermediários anteriores, como mostrado nos dois exemplos. Assim, foi proposta uma nova abordagem para a solução do problema. Com base no texto e em conhecimentos previamente obtidos sobre sistemas baseados em conhecimento, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Poderíamos, a cada cálculo fatorial, armazenar os cálculos intermediários em uma tabela, por exemplo, desde 0 até 4, e teríamos como resultados, respectivamente, 1, 1, 2, 6 e 24. Esses resultados poderiam estar armazenados em posições conhecidas de memória. II. ( ) O uso de uma tabela, armazenando-se os cálculos intermediários, promove otimização do algoritmo, pois, se o próximo número a ser calculado for igual ou menor ao maior número calculado, basta ler o número direto da tabela ou na posição de memória correspondente. III. ( ) O uso de uma tabela, armazenando-se os cálculos intermediários, promove otimização do algoritmo, pois, se o próximo número a ser calculado for igual ou maior ao maior número calculado, o problema poderá ser resolvido, mas o algoritmo de multiplicação termina. IV. ( ) O uso de uma tabela, armazenando-se os cálculos intermediários, promove otimização do algoritmo, pois, se o próximo número a ser calculado for igual ou maior ao maior número calculado, as multiplicações deverão considerar o último (maior) resultado obtido. Está correto apenas o que se afirma em:
    - R : Letra A.  V, V, F, V. 

<!-- 


Postar no Fórum. A ordem da alternativa está errada!

 -->
- Q_i
    - P : A teoria de resolução de problemas utiliza alguns termos próprios que devem ser conhecidos para se estruturar os problemas e desenvolver os algoritmos para suas soluções, particularmente quando se precisa estruturar as estratégias de busca. Com base nessa afirmação e no conteúdo estudado sobre estratégias de busca, analise os termos a seguir utilizados na resolução de problemas de Inteligência Artificial e relacione-os às suas definições. 1) Estado. 2) Meta. 3) Nó de busca. 4) Espaço de estados. ( ) Um estado temporário em uma árvore de busca ou em um grafo. ( ) Grafo cujos nós são o conjunto de todos os estados possíveis e cujas arcos entre os nós são as ações que, quando executadas, transformam um estado em outro. ( ) Situação que o agente pretende alcançar. ( ) Situação na qual o agente se encontra. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C. 4, 3, 1, 2. O estado é a situação atual do agente, diretamente ligada ao seu ambiente (1). A meta é onde se deseja chegar (2). O nó de busca (3) é um estado transitório, e se altera à medida que o algoritmo de busca se desloca pelo grafo, finalmente, o espaço de estados (4) é o conjunto de todas as possibilidades que o agente pode assumir.
- Q_i
    - P : Um fazendeiro (F), com seu lobo (L), sua cabra (C) e seu repolho (R), chega à margem de um rio que deseja atravessar. Há um barco na margem do rio, mas, naturalmente, somente o fazendeiro pode remar. O barco também só pode transportar duas coisas (incluindo o remador) de cada vez. Se o lobo ficar sozinho com a cabra, ele comerá a cabra. Da mesma forma, se a cabra ficar sozinha com o repolho, ela o comerá. Para esse clássico problema de Inteligência Artificial, considere as afirmações propostas a seguir, com suas heurísticas associadas, e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) FLRC [ ~~~~] (4,0) está mais próxima da solução final do problema que LR [~~~~] F C (2,0). II. ( ) FLR [ ~~~~] C (3,0) está mais próxima da solução final do problema que FLRC [~~~~] (4,0). III. ( ) FC [ ~~~~] LR (2,0) está mais próxima da solução final do problema que FLR [~~~~] C (3,0). IV. ( ) FC [ ~~~~] LR (2,0) é tão boa solução quanto LR [~~~~] FC (2,0). Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. F, V, V, V. 
- Q_i
    - P : Uma característica da busca em profundidade é que ela possui métodos que permitem que os nós dos grafos sejam visitados na ordem especificada. Um dos métodos utilizados nessa busca é o da Pós-Ordem. Considerando essas informações e o conteúdo estudado sobre estratégias de busca, analise os procedimentos abaixo e ordene-os de acordo com a sequência em que eles ocorrem no método Pós-Ordem. ( ) Realiza-se o processo recursivo de visita do ramo à esquerda. ( ) O nó corrente é visitado. ( ) Realiza-se o processo decursivo de visita do ramo à direita. ( ) Após a busca, é possível não encontrar a solução esperada para o problema. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B. 1, 3, 2, 4. 
- Q_i
    - P : Considere o problema do quebra-cabeça do “Fazendeiro, Lobo, Repolho e Cabra”. Representando os elementos do problema de forma matricial, com estado inicial {F, L, R, C}, assumindo os deslocamentos do rio de Norte para o Sul e de nossos personagens de Oeste para Leste. A posição inicial dos personagens, representadas matricialmente, Fazendeiro, Lobo, Cabra e Repolho, nesta ordem, será {Oeste, Oeste, Oeste, Oeste}, o lado esquerdo da margem do rio. Admita que os valores inteiros dos custos variem de 0,0 a 4,0. Considerando essa informação e o conteúdo estudado sobre estratégias de busca, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) { , L, R, } é uma solução parcial para o problema e deve receber um valor de custo menor que 4,0. II. ( ) { , , , } é uma solução parcial para o problema e deve receber um valor de custo igual a 0,0. III. ( ) { ,L , ,C } é uma solução parcial para o problema e deve receber um valor de custo igual a 4,0. IV. ( ) {F, , R,C} e {F, , ,C} são soluções parciais para o problema e devem receber um valor de custo maior que 0,0. Agora, assinale a alternativa que apresenta a sequência correta
    - R : Letra A. V, V, F, V.
- Q_i
    - P : Os agentes inteligentes organizam o que coletam em alguma estrutura que lhes permita encontrar o subconjunto de dados necessários para determinada decisão em um momento qualquer do tempo. O fato é que essa estrutura tende a crescer e deve ser percorrida de alguma forma eficiente para que o algoritmo de busca do sistema baseado em conhecimento seja efetivo em sua ação. Com base no texto e nos sistemas baseados em conhecimento, é correto afirmar que a tarefa dos métodos de busca exposto no texto é:
    - R : Letra B. essencial, sendo o objetivo principal de um algoritmo de busca. 
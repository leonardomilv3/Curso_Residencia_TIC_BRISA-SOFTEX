# Aprendizagem

# Tópicos Abordados

- Aprendizagem de Máquina
    - Conhecendo os principais representantes
- Sistemas Especialistas
- Redes Neurais (Perceptron, Multicamadas, Backpropagation)
    - Neurônio Booleani
    - Perceptron
    - Multicamadas
    - Retropropagação
    - Aplicação
- Algoritmo Genético
    - Aplicação

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : A Inteligência Artificial pode apresentar limitações, dependendo da modelagem que o projetista tenha feito do problema em estudo. Problemas complexos pressupõem uma modelagem complexa para que se alcance os objetivos desejados e a esta deve ser uma associada uma medida de desempenho. Considerando essa informação e o conteúdo estudado sobre Algoritmo Genético, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Há uma grande a diferença, do ponto de vista dos algoritmos e das técnicas de Inteligência Artificial, das soluções empregadas aos problemas do Mundo Real e àquelas empregadas aos problemas do Mundo Virtual. II. ( ) Em um jogo, como o de damas, por exemplo, os algoritmos e técnicas de Inteligência Artificial não são complexos, pois o problema em questão é formalmente mapeável e o jogo é, em si, uma representação alegórica e já mapeada do mundo real. III. ( ) O reconhecimento da fotografia de um gato por uma instância de Inteligência Artificial é um exemplo de um problema complexo que merece modelagem também complexa, e uma boa técnica utilizada é o aprendizado por reforço, que funciona bem para a interação física do agente inteligente com o ambiente. IV. ( ) A atuação dos agentes inteligentes, criados pelos algoritmos e pelas técnicas de Inteligência Artificial, é efetiva, independentemente da generalidade e do escopo dos problemas a serem resolvidos. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra A. V, V, V, F

<!-- 

COLOCAR NO FORUm

 -->
- Q_i
    - P : A teoria das redes neurais gerou, ao longo de sua evolução, tipos de redes com características adequadas ao tipo de problema a ser resolvido. Com base na afirmação apresentada e nos conteúdos estudados sobre Redes Neurais, analise alguns dos tipos de redes neurais propostos a seguir e ordene-os de acordo com suas aplicações. 1) Neurônio Booleano. 2) Rede Neural Perceptron. 3) Rede Neural Perceptron MLP. 4) Rede Neural Perceptron MLP com BackPropagation (retropropagação). ( ) A rede estabelece um valor pré-estabelecido de erro na saída, tornando-se uma das redes mais eficientes no processo de aprendizagem. ( ) Resolve a separação de elementos de um conjunto não-linearmente separáveis. ( ) Resolve as operações lógicas elementares. ( ) Resolve a separação de elementos de um conjunto linearmente separáveis. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D. 3, 4, 2, 1. 
- Q_i
    - P : Considere o algoritmo genético proposto a seguir: Linha 1: Gerar um número randômico n, tal que 0 <= n < comprimento(cromossomo); Linha 2: Genitor A passa seu gene na posição 0 ... n para o Filho 1. Linha 3: Genitor B passa seu gene na posição 0 ... n para o Filho 2. Linha 4: Genitor A passa seu gene na posição (n+1) ... comprimento(cromossomo -1) às posições correspondentes para o Filho 2; Linha 5: Genitor B passa seu gene na posição (n+1) ... comprimento(cromossomo -1) às posições correspondentes para o Filho 1; Considerando esse algoritmo e o conteúdo estudado sobre Algoritmo Genético, é correto o que se afirma em:
    - R : Letra A. O algoritmo proposto usa a técnica do crossover, comum nos algoritmos genéticos, o que pode ser confirmado pelas linhas 4 e 5 quando comparadas com as linhas 2 e 3, respectivamente.
- Q_i
    - P : Uma instância de Inteligência Artificial deve ter a capacidade de utilizar dados e resultados anteriores para melhorar seus parâmetros de funcionamento e, assim, produzir resultados cada vez melhores em execuções futuras de suas funções. Considerando essas informações e os conteúdos estudados sobre Aprendizado de Máquina, pode-se sintetizar a afirmação proposta no texto apresentado com a seguinte palavra:
    - R : Letra C. aprendizado.
- Q_i
    - P : Um dos grandes desafios das instâncias de Inteligência Artificial, e um belo exemplo de aplicação, é Reconhecimento de Voz, que envolve identificar o que foi dito e tomar uma ação com base na informação recebida pelo sistema. São várias as etapas que devem ser analisadas para que o hardware e/ou software possa identificar a pessoa que está falando. Para um sistema de Reconhecimento de Voz genérico, analise os procedimentos a seguir, e ordene-os de acordo com a sequência em que devem ocorrer para que o sistema em questão possa identificar adequadamente a voz de uma pessoa. ( ) O processo de reconhecimento da voz, quando em operação, é influenciado pela altura do som, sotaque e velocidade com o usuário fala ao sistema de reconhecimento. ( ) O usuário deve treinar a instância de Inteligência Artificial, a priori, falando várias palavras, pois trata-se de um processo de aprendizagem. ( ) Uma tabela de busca, chamada “look-up table” deve ser criada com base na decomposição das palavras em suas respectivas frequências (sinais elétricos) correspondentes. ( ) Quanto mais precisa for a tabela de busca (look-up table) mais complexo se torna o processo de reconhecimento. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B.  2, 3, 4, 1.     
- Q_i
    - P : O aprendizado de Máquina é um campo de estudo da Inteligência Artificial (IA) que tem encontrado muitas aplicações nos últimos tempos em função, principalmente, do aumento da complexidade de tarefas diárias. Considerando essa informação e o conteúdo estudado sobre Algoritmo Genético, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Indivíduos com deficiências visuais podem ser beneficiados por sistemas de IA que reconheçam imagens e que possam interpretá-las e descrevê-las em seus celulares. II. ( ) O aprendizado de Máquina está presente em aplicações que envolvem detecção de fraudes e podem, por exemplo, auxiliar agentes da Receita Federal na execução de suas atribuições. III. ( ) O grande problema dos algoritmos genéticos, das redes neurais e dos sistemas especialistas é a impossibilidade da aprendizagem. IV. ( ) O reconhecimento, por um sistema eletrônico, de dígitos escritos à mão e a obtenção de dados importantes a partir de um volume muito grande de dados aparentemente sem importância pode ser obtido com o uso do aprendizado de máquina. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B. V, V, F, V.
- Q_i
    - P : O programa WordGuess precisa que uma sequência de ações seja realizada pelo usuário para que possa iniciar o corretamente o algoritmo que adivinha a palavra sob investigação. Como consequência, com um único algoritmo, pode-se criar diversos cenários para o problema, além de testar o desempenho do algoritmo em cada caso. Considerando essas informações e os conteúdos estudados sobre Algoritmo Genético, admita que a palavra sob investigação é “Estrela” e analise as ações e os nomes de arquivo a seguir, de acordo com a sequência em que aparecem: 1) Descompactar os arquivos zip. 2) Executar Javac 3) Java SetParams params.dat 128 64 5 .1 1000 4) java WordGuessTst params.dat Estrela ( ) Estrela. ( ) Arquivos com extensão java. ( ) Classes Java: SetParams.class e WordGuessTst.class. ( ) Param.dat Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra 
- Q_i
    - P : O programa WordGuess precisa que uma sequência de ações seja realizada pelo usuário para que possa iniciar o corretamente o algoritmo que adivinha a palavra sob investigação. Como consequência, com um único algoritmo, pode-se criar diversos cenários para o problema, além de testar o desempenho do algoritmo em cada caso. Considerando essas informações e os conteúdos estudados sobre Algoritmo Genético, admita que a palavra sob investigação é “Estrela” e analise as ações e os nomes de arquivo a seguir, de acordo com a sequência em que aparecem: 1) Descompactar os arquivos zip. 2) Executar Javac 3) Java SetParams params.dat 128 64 5 .1 1000 4) java WordGuessTst params.dat Estrela ( ) Estrela. ( ) Arquivos com extensão java. ( ) Classes Java: SetParams.class e WordGuessTst.class. ( ) Param.dat Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra A.  2, 3, 4, 1.
- Q_i
    - P : São os processos de aprendizagem os mecanismos que efetivamente conferem às redes neurais a importância que assumiram no desenvolvimento da Inteligência Artificial. Quanto aos tipos de aprendizado de redes neurais e seus algoritmos, analise as afirmativas a seguir: I. Algoritmos do tipo A* e Minmax. II. Algoritmos do tipo Hebbiano e Correção de Erro. III. Algoritmos do tipo Competitivo; de Boltzmann e Probabilístico. IV. Algoritmos do tipo Crossover e Mutação. Está correto apenas o que se afirma em:
    - R : Letra C.  II e III. 
- Q_i
    - P : A Inteligência Artificial é uma ciência multidisciplinar, tendo se desenvolvido sob a influência de diversas áreas do conhecimento. Cada uma dessas áreas apresentou muitas contribuições e algumas delas podem ser facilmente identificadas. Identifique algumas destas contribuições e associe-as com suas respectivas áreas de conhecimento. 1) Matemática. 2) Economia. 3) Neurociência. 4) Linguística. 5) Filosofia. ( ) Relacionamento entre a linguagem e o pensamento, originando a fusão entre a linguística moderna e a Inteligência Artificial, conhecida como processamento da linguagem. ( ) Desde Aristóteles, contribuiu com a Inteligência Artificial com diversos movimentos filosóficos como, por exemplo, o racionalismo, dualismo, materialismo, empirismo, indução, dentre outras correntes de pensamento. ( ) Modelos matemáticos desenvolvidos tendo como referência o neurônio biológico humano dera origem às redes neurais artificiais (RNA). ( ) Proposição de diversas Teorias e Decisões Racionais, Tomadas de Decisões sob situações de Incertezas, Teoria dos Jogos e Processos de Decisão Markov. ( ) Lógica, com a representação formal e as provas; Computação, Algoritmos e a Probabilidade. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C. 4, 5, 3, 2, 1.
- Q_i
    - P : Ao se abordar a teoria das redes neurais, estudamos o Perceptron e o Perceptron MLP, dois representantes dos agentes inteligentes com a característica da aprendizagem. Com base nestas afirmações e no conteúdo estudado sobre Redes Neurais, analise as asserções a seguir e a relação proposta entre elas. I. Em uma rede neural Perceptron, com uma camada de entrada e uma camada de saída, pode-se configurar uma regra simples de aprendizado, conhecida como Regra de Rosenblatt. Porque: II. Se o conjunto de entrada for linearmente separável, haverá a necessidade do uso de uma rede Perceptron Multicamadas (Multilayer Perceptron - MLP). A seguir, assinale a alternativa correta:
    - R : Letra B. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I. 
- Q_i
    - P : Considere a sequência de programação realizada no MATLAB com o objetivo de criar, treinar e gerar o gráfico de uma rede neural aplicada a classificação de elementos, a saber: “net()”, “net=train()” e “plotpc()”. Considerando essas informações e o conteúdo estudado sobre Redes Neurais, é correto afirmar:
    - R : Letra A. as instruções “net = newp([-2 3;-2 3], 1)”, “net=train(net ,P ,T)” e “plotpc(net.IW{1},net.b{1})”, respectivamente, criam a rede neural, treinam a rede criada e classificam seus vetores de entrada em seus compartimentos.
- Q_i
    - P : Estudando os algoritmos genéticos é notável a semelhança de suas técnicas com alguns conceitos da Teoria de evolução, que tem por premissa perpetuar somente os indivíduos mais fortes que formarão a próxima geração de uma dada espécie. De acordo com o texto e com o conteúdo estudado sobre Algoritmo Genético, a alternativa que melhor se ajusta a essa afirmação é:
    - R : Letra D. uma população de soluções candidatas para o problema recebe uma função de aptidão que mede sua contribuição para a geração futura.

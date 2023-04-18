# Deep Learning

## Tópicos Abordados

- Deep Learning
- Tipos de Arquiteturas
    - Feedforward (->)
    - Feedback (<-)
    - Bidirecional (<->)
        - Redes Hofield (redes conectadas simetricamente)
        - Máquinas de Boltzamnn (redes com unidades ocultas) 
- Redes Neurais Profundas
- Complexidade da Teoria
- Redes Convolucionais
- Arquitetura
    - Algoritms de otimização CNN
- Redes Neurais Recorrentes
- Modelos de Redes Neurais e Modelo Probabilísticos
- Deep Belief Network (DBN)
- Autoencoders (AE)

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Existem diversos estudos que se dedicam a demonstrar o porquê de as redes profundas serem melhores que as redes simples, tomando como partida o teorema da aproximação. Este teorema gerou resultados mais refinados em comparação com o teorema de hierarquia de profundidade em complexidade de circuitos. Considerando essas informações e o conteúdo estudado sobre redes neurais, pode-se afirmar que:
    - R : Letra A. trata-se de uma função com diversas entradas e uma saída. Sua tarefa é pegar todos os números de sua entrada, executar uma função neles e enviar o resultado para a saída.
- Q_i
    - P : As Deep Learning são usualmente utilizadas para resolver o problema de treinamento de redes neurais artificiais. Elas necessitam de muitos dados para serem treinadas e, com isso, aprenderem as características hierarquicamente, não precisando mais de um humano para selecionar as características que formarão seu modelo de aprendizado. Considerando essas informações e o conteúdo estudado sobre aos tipos de arquiteturas de Deep Learning, analise as afirmativas a seguir. I. A primeira arquitetura é a Feed-Forward, muito utilizada em redes multicamadas, como a as redes convolutivas. II. A segunda é a Feed-Back, frequentemente usada nas redes Stacked Sparse Coding. III. A terceira é a Bi-Directional, onde em cada camada é realizado o treinamento não supervisionado. IV. A quarta é a arquitetura puramente supervisionado, usada em Deep Bolzmann e Autoencoders. Está correto apenas o que se afirma em:
    - R : Letra E. I e II
- Q_i
    - P : Leia o excerto a seguir: “São redes neurais artificiais profundas que podem ser usadas para classificar imagens, agrupá-las por similaridade (busca de fotos) e reconhecer objetos dentro de cenas. São algoritmos que podem identificar rostos, indivíduos, sinais de rua, cenouras, ornitorrincos e muitos outros aspectos dos dados visuais.” Fonte: DEEP LEARNING. As 10 principais arquiteturas de redes neurais. Disponível em: . Acesso em: 18 out. 2019. Considerando essas informações e o conteúdo estudado sobre arquitetura, a camada onde os neurônios não estão individualmente ligados a todas as entradas da rede é definida como camada:
    - R : Letra C. convolucional.
- Q_i
    - P : Há uma artilharia de satélites, radares, telescópios e supercomputadores por trás da previsão do tempo. A alta tecnologia vai muito além de saber se choverá ou fará sol. O primeiro passo é recolher as informações de temperatura, umidade, velocidade dos ventos e pressão atmosférica. Fonte: SEVERIANO, A. Coluna mostra a tecnologia utilizada para fazer a previsão do tempo. Disponível em: . Acesso em: 17 out. 2019. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que uma importante ferramenta utilizada para a previsão do tempo é denominada de:
    - R : Letra D.Backpropagation.

<!-- 






AVISAR NO FÓRUM

marquei a letra certa mas a plataforma entendeu como errado



 -->
- Q_i
    - P : É uma rede neural treinada para tentar copiar sua entrada para sua saída. Internamente, ela tem uma camada oculta que descreve as proteções presentes na entrada. Além disso, é um algoritmo de aprendizado de máquina não supervisionado que toma uma imagem como entrada e tenta reconstruí-la usando um número menor de bits do gargalo, também conhecido como espaço latente. Considerando essas informações e o conteúdo estudado sobre redes neurais, pode-se afirmar que o texto faz referência ao conceito de:
    - R : Letra B. autoencoders
- Q_i
    - P : É um modelo de Deep Learning inspirado no córtex visual e, portanto, abrange o campo da visão computacional, viabilizando o desenvolvimento de softwares capazes de classificar e localizar objetos em imagens com dinamismo surpreendente. Considerando essas informações e o conteúdo estudado sobre aos modelos de Deep Learning, pode-se afirmar que o modelo ao qual o trecho se refere é:
    - R : Letra A. redes convolucionais.
- Q_i
    - P : Com laços de conexão que possibilitam a persistência da informação, elas utilizam eventos passados para recalibrar suas saídas em relação a novas entradas. Podemos dizer que um sinal é enviado em um instante de tempo t, e este pode alterar o comportamento da rede em um momento t + k, em que k > 0. São máquinas de Turing completas. Na teoria, elas podem desenvolver qualquer computação. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que o texto faz referência ao conceito de:
    - R : Letra E.  rede neurais recorrentes. 
- Q_i
    - P : Existem diversas técnicas que modelam essas inteligências, uma dessas áreas é chamada de Aprendizado de Máquina ou Machine Learning (ML), onde as propriedades a serem mensuradas são as características de um fenômeno, que presumem que o conjunto de dados a ser usado durante o treinamento foi previamente selecionado por um ser humano. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que uma rede neural executa ações relacionadas, por exemplo:
    - R : Letra C. à captura de imagem de entrada.
- Q_i
    - P : Existem diversas técnicas que modelam essas inteligências, uma dessas áreas é chamada de Aprendizado de Máquina ou Machine Learning (ML), onde as propriedades a serem mensuradas são as características de um fenômeno, que presumem que o conjunto de dados a ser usado durante o treinamento foi previamente selecionado por um ser humano. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que uma rede neural executa ações relacionadas, por exemplo:
    - R : Letra B.  decodificador. 
- Q_i
    - P : Adequada para o processamento de informações sequenciais, dado que são capazes de memorizar eventos mesmo que eles ocorram com um intervalo longo, assim como em modelos preditivos, essa arquitetura foi projetada para tratar problemas do fluxo de erro retroprogramado, que decaem ou explodem exponencialmente. Considerando essas informações e o conteúdo estudado sobre tipos de arquitetura do Deep Learning, pode-se afirmar que o modelo ao qual o trecho se refere é:
    - R : Letra E. rede neurais recorrentes.
- Q_i
    - P : Existem três tipos de arquiteturas de Deep Learning. A primeira arquitetura é a Feed-Forward, muito utilizada em redes multicamadas, como as redes convolutivas. A segunda, Feed-Back, é frequentemente usada nas redes Stacked Sparse Coding. E a terceira, Bi-Directional, é utilizada em Deep Bolzmann e Autoencoders. Essas arquiteturas operam em diferentes tipos de treinamento, como o supervisionado e o não supervisionado. Considerando essas informações e o conteúdo estudado sobre protocolo “puramente supervisionado”, pode-se afirmar, em relação a este protocolo, que:
    - R : Letra D. tem inicialização de parâmetros de maneira aleatória, utiliza tipicamente o método do gradiente descendente e backpropagation.

- Q_i
    - P : Um modelo generativo probabilístico composto de diversas camadas de variáveis latentes estocásticas tem como objetivo aprender níveis abstratos da distribuição dos dados de entrada. Considerando essas informações e o conteúdo estudado sobre garantia de qualidade, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s): I. ( ) Wake-Sleep: nesse algoritmo, para cada vetor de pesos reconhecido pelo neurônio da arquitetura é utilizada a programação bottom-up. Estocasticamente é possível selecionar os estados binários das unidades ocultas. II. ( ) Greedily Layer-Wise Training: Os DBN são treinados em conjunto, onde cada variável latente é descartada. Os pesos de entrada de cada camada são utilizados para inicializar a próxima. III. ( ) Up-Down: Utiliza o algoritmo Greedily Traning para aprender os pesos da DBN, porém recarrega estes pesos através do método “up-down”, pois o método GT não garante alta qualidade no valor dos pesos gerados. IV. ( ) Autoencoder: É um dispositivo supervisionado que utiliza áudios como entrada e tenta reconstruí-la usando um número maior de bits do gargalo, também conhecido como espaço variável. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D.  V, F, V, F. 
- Q_i
    - P : Estrutura que tem base no módulo RBM, essa classe de rede pode ser treinada de maneira não supervisionada e pode ser muito útil em um posterior aprendizado supervisionado. Por isso essas estruturas são muito utilizadas na redução de dimensões não lineares de dados com alta dimensão. Considerando essas informações e o conteúdo estudado sobre estruturas no módulo RBM, pode-se afirmar que as estruturas ao qual o trecho se refere são:
    - R : Letra E. autoencoders.
- Q_i
    - P : Leia o excerto a seguir: “Deep Learning é um tipo de Machine Learning que treina computadores para realizar tarefas como seres humanos, o que inclui reconhecimento de fala, identificação de imagem e previsões.” Fonte: SAS. Deep Learning: O que é e qual sua importância? Disponível em: . Acesso em: 17 out. 2019. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que uma de suas funções é:
    - R : Letra E. observar as chances de aprendizagem em um nível mais profundo com o uso de redes neurais.

- Q_i
    - P : Leia o excerto a seguir: “As redes neurais denominadas de autoassociativas (RNAA) têm sido empregadas como uma alternativa para o ajuste das medidas em sistemas reais que envolvem um grande número de sensores, dadas as suas características intrínsecas.” Fonte: SANCHEZ, J. E. R. S. Sistema de monitoramento de múltiplos sensores por redes neurais autoassociativas e lógica fuzzy. Disponível em: . Acesso 18 out. 2019. Considerando essas informações e o conteúdo estudado sobre os autoencoders, pode-se afirmar que o modelo que exerce a função de redes autoassociativas é conhecido como:
    - R : Letra A.  stacked autocoders.
- Q_i
    - P : Existem três tipos de arquiteturas de Deep Learning. Essas arquiteturas operam em dois diferentes tipos de treinamento: supervisionado e não supervisionado. Neste contexto, alguns protocolos de treinamento podem ser utilizados. Considerando essas informações e o conteúdo estudado sobre aos protocolos de treinamento, analise as afirmativas a seguir. I. Bi-directional: Funcionam de maneira distinta das redes recorrentes, porém existe uma assimetria entre as conexões e são mais complexas de serem analisadas. II. Puramente supervisionado: tem inicialização de parâmetros de maneira aleatória, utiliza tipicamente o método do gradiente descendente e backpropagation. III. Não supervisionado e classificação no topo: Em uma camada é realizado o treinamento não supervisionado. Antes são treinadas as camadas supervisionadas, mantendo as outras camadas variáveis. IV. Não supervisionado e sintonização global supervisionada: em cada camada não supervisionada é efetuado o treino, uma após a outra. É adicionada uma camada de classificação e é retirada a supervisão de toda a hierarquia. Está correto apenas o que se afirma em:
    - R : Letra B.  II e IV. 
- Q_i
    - P : É um modelo generativo probabilístico composto de diversas camadas de variáveis latentes estocásticas. Tem como objetivo aprender níveis abstratos da distribuição dos dados de entrada. São usados três algoritmos aplicados na resolução desse tipo de problema. Considerando essas informações e o conteúdo estudado sobre modelos probabilísticos, pode-se afirmar que o modelo ao qual o trecho se refere é:
    - R : Letra C.  Deeb Belief Network.
- Q_i
    - P : As Deep Learning são usualmente utilizadas para resolver o problema de treinamento de redes neurais artificiais. Elas necessitam de muitos dados para serem treinadas e, com isso, aprenderem as características de forma hierárquica, não precisando mais de um humano para selecionar as características que formarão seu modelo de aprendizado. Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que uma de suas atividades executadas está relacionada à:
    - R : Letra A. síntese e reconhecimento de fala.
- Q_i
    - P : Leia o excerto a seguir: “A principal diferença entre Machine Learning tradicional, que utiliza algoritmos não¬ supervisionados, e Deep Learning é o método utilizado para extração de características relevantes para a classificação. Na abordagem tradicional, um programador faz a engenharia de forma manual, determinando quais são as características relevantes para que um certo tipo de dado seja diferenciado das outras possíveis classes.” Fonte: RAMOS, T. Deep Learning. Disponível em: . Acesso em: 18 out. 2019. (Adaptado). Considerando essas informações e o conteúdo estudado sobre Deep Learning, pode-se afirmar que ele se caracteriza por apresentar:
    - R : Letra C. um método de extração de características feito de forma automática.
- Q_i
    - P : Uma rede CNN pode ter diversos estágios empilhados após a camada de entrada e, depois da camada de estágio final, são adicionas uma ou mais camadas complementares, de modo que elas fiquem conectadas entre si. Considerando essas informações e o conteúdo estudado sobre redes CNN, pode-se afirmar, em relação à camada de amostragem de uma rede CNN, que:
    - R : Letra A. a camada opera de uma maneira muito parecida com os features de entrada; reduz a vizinhança pegando o valor máximo e, ao realizar esse procedimento, por vezes reduz as variações da representação do feature.
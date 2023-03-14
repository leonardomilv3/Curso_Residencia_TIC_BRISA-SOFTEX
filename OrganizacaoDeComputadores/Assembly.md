# Técnicas de Programação em Assembly e Introdução a Microcontroladores.

## Tópicos Abordados

- Microprocessador Comercial
    - Conceitos e Definições
    - Instruções de Máquina
    - Representações de uma instrução
    - Tipo de Instrução
    - Número de Endereços
- Lei de Moore
- Técnicas de Programação em Assembly
    - Vantagens e Desvantagens
- Programando em Assembly
- Introdução aos Microcontroladores
    - Microcontroladores PIC
- Arduino


## Questionários 

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : Com relação à função de cada estado do ciclo de instruções, podemos dizer que o cálculo de endereço de instrução (instruction address calculation) determina o endereço da próxima instrução que será executada. Considerando esse excerto e o conteúdo estudado sobre ciclo de instruções, pode-se afirmar que:
    - R : busca da instrução e decodificações da operação da instrução são estados dos ciclos de instrução. 
- Q_i
    - P : Basicamente, o conjunto de instruções é a parte do computador visível para o programador, estabelecendo, dessa forma, a fronteira entre o software e o hardware. Isso significa que o programador deve conhecer a linguagem de máquina para programar as tarefas e as instruções realizadas pelo microprocessador. Tendo em vista que a operação de uma CPU (Central Process Unit – Unidade Central de Processamento) ou de um microprocessador é determinada pelas instruções que ela executa, bem como considerando o conteúdo estudado sobre microprocessadores, analise as afirmativas a seguir: I. O conjunto de instruções de máquina (Machine Instructions Set) é também conhecido como linguagem de máquina ou instruções do computador. II. É o conjunto de instruções que permite tanto a movimentação de dados quanto a execução das operações no microprocessador. III. Cada tipo de microprocessador tem o seu próprio conjunto de endereços mnemônicos. IV. As diferentes instruções que a unidade de controle executa são conhecidas como conjunto de operações. Está correto apenas o que se afirma em:
    - R : I e II. 
- Q_i
    - P : O microprocessador (também conhecido como processador ou chip) é um dispositivo lógico programável capaz de acessar, controlar e executar instruções existentes da memória principal. Também conhecido como Unidade Central de Processamento, o microprocessador tem a função de realizar e gerenciar as operações de leitura/escrita da memória. Considerando essas informações e o conteúdo estudado sobre microprocessadores, pode-se dizer que a operação do microprocessador é determinada pelas:
    - R : instruções que ele executa (instruções de máquina). 
- Q_i
    - P : Os computadores integram inúmeros componentes eletrônicos e lógicos. Um dos principais componentes é o microprocessador. Cada tipo de microprocessador tem o seu próprio conjunto de instruções mnemônicas que representam os códigos binários das instruções. Considerando essas informações e o conteúdo estudado sobre microprocessadores, pode-se afirmar que:
    - R : a linguagem Assembly utiliza o conjunto de instruções para criar programas para o microprocessador.

- Q_i
    - P : A linguagem Assembly (linguagem de máquina) é considerada uma linguagem de baixo nível. Ela utiliza palavras abreviadas (ou representações simbólicas), conhecidas como mnemônicos, para cada instrução de máquina, objetivando, com isso, melhor compreensão das operações por parte das pessoas (programadores, por exemplo). A partir dessas informações e do conteúdo estudado sobre linguagem Assembly, pode-se afirmar que:
    - R : a tradução da linguagem Assembly para os códigos de máquina do processador é realizada por um programa conhecido como assembler.  
- Q_i
    - P : Vale ressaltar que, torna-se difícil para o programador lidar com representações binárias de instruções máquina. Por isso, é comum utilizar uma representação simbólica para instruções de máquina. Nessas condições, considerando o excerto, bem como os estudos realizados sobre microprocessadores comerciais, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Os opcodes são representados por abreviações, chamados mnemônicos, que indicam a operação que será realizada. II. ( ) A instrução ADD R, Y pode ter a seguinte leitura: somar o valor contido no local de dados Y (posição Y) com o conteúdo do registrador R. III. ( ) A arquitetura do microprocessador pode ser descrita pelo número de endereços contidos em cada instrução. IV. ( ) A quantidade de endereços por instrução é uma decisão do programador. Agora, assinale a alternativa que apresenta a sequência correta:
    - R :  V, V, V, F. 
- Q_i
    - P : Basicamente, o funcionamento de um microprocessador resume-se nos inúmeros dispositivos lógicos existentes em sua arquitetura interna, bem como em barramentos (interno e externo) essenciais na comunicação de dados. Nessas condições, considerando essas informações, bem como o estudo sobre a operação de um microprocessador, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. O registrador de instrução tem como função armazenar a instrução mais recente, a qual será executada pelo microprocessador. II. O decodificador de instrução tem como função identificar a operação que será realizada com base na instrução a ser executada. III. O barramento de controle tem como função atuar como um controlador de acesso aos dados. IV. A arquitetura CISC é muito utilizada em processadores da Motorola e AMD. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : V, V, V, F.   
- Q_i
    - P : Durante o processo evolutivo, foram projetados e construídos inúmeros tipos de computadores. Entretanto, acredita-se que grande parte deles já foi esquecida, porém, alguns causaram um impacto significativo sobre o processo histórico, inspirando os cientistas e pesquisadores em novas ideias e desenvolvimentos inovadores. Considerando essas informações e o conteúdo estudado sobre microprocessadores comerciais, é possível afirmar que os computadores que fizeram parte da evolução histórica são:
    - R : UNIVAC, ENIAC e os computadores transistorizados.
- Q_i
    - P : Conforme mencionamos, a linguagem Assembly é uma linguagem de montagem. Programar em Assembly é escrever um código entendido pelo hardware; exemplo disso é a programação dos microprocessadores e dos microcontroladores. Esse programa pode ser escrito em um editor de textos (MS Word, por exemplo) e depois copiado para ambiente de programação. Esse ambiente pode ser o MPLAB. Considerando as informações apresentas e de acordo com os estudos realizados sobre linguagem Assembly, pode-se afirmar que
    - R : o assembler interpreta as instruções escritas em linguagem Assembly como uma sequência de zeros e uns com significado para a lógica operacional do microcontrolador. 
- Q_i
    - P : É necessário que as instruções de máquina tenham as informações necessárias para que a CPU possa executá-las. Nesse sentido, as referidas instruções possuem alguns elementos essenciais. Com base no trecho acima, bem como de acordo com os elementos de uma instrução de máquina, analise as afirmativas a seguir. I. O código de operação especifica a operação a ser realizada. II. A referência ao operando fonte pode envolver um ou mais operandos fontes. III. A referência à próxima instrução faz a busca da próxima instrução após o término de uma instrução. IV. A referência ao destino reproduz uma instrução. Está correto apenas o que se afirma em:
    - R :  I, II e III.


### Questionário II


- Q_i
    - P : Quando um programador tem a tarefa de escrever um programa, além das regras básicas, existem princípios que se tornam convenientes. Esses princípios relatam o profissionalismo e a importância que o profissional estabelece no momento de desenvolver o referido programa. Com base no trecho acima e no conteúdo estudado sobre linguagem Assembly, é possível afirmar que:
    - R : LETRA E. um dos princípios é escrever, no início, o nome do programa, para que serve e a versão; além de outras informações pertinentes.
- Q_i
    - P : Os microcontroladores PIC (Peripherical Interface Controller) possuem algumas famílias que contemplam os seus tipos e modelos específicos de aplicações, como, por exemplo, as famílias de 8, 16, 32 e 64 bits. Porém, cada família de microcontrolador PIC difere em vários fatores. Considerando essas informações e o conteúdo estudado sobre microcontroladores PIC, podemos afirmar que: 
    - R : LETRA D. a tensão elétrica de alimentação é um dos fatores que diferem um microcontrolador de outro 
- Q_i
    - P : Arduino é uma plataforma de prototipagem (projeto/protótipo) eletrônica de software e de hardware livres (open source) e de placa única. Projetada com um microcontrolador Atmel Corporation AVR (microcontrolador RISC de 8 bits), a plataforma possui suporte de entrada/saída embutido e uma linguagem de programação padrão; normalmente são as linguagens C ou C++. Considerando essas informações e o conteúdo estudado sobre Arduino, analise as afirmativas abaixo e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s)
    - R : LETRA C. V, V, V, F. 
- Q_i
    - P : A linguagem Assembly, também conhecida como linguagem de baixo nível, possui alguns elementos básicos, como por exemplo: os Labels, as Instruções, os Operandos, as Diretivas e os Comentários. Esses elementos fazem com que a referida linguagem seja escrita de forma clara e objetiva. A partir dessas informações e do conteúdo estudado sobre linguagem Assembly, é possível dizer que:
    - R : LETRA D. os labels (rótulos) são designações textuais de uma linha em um programa ou o início de um conjunto de linhas de um programa
- Q_i
    - P : O microcontrolador PIC (Programmabile Intelligent Computer) é um circuito integrado lógico que possui inúmeros componentes internos, constituindo, dessa forma, um sistema digital programável totalmente controlado. Considerando essas informações e o conteúdo estudado sobre microcontroladores PIC, podemos afirmar que:
    - R : LETRA E. externamente, o PIC pode ser visto como um circuito integrado lógico da família TTL (Transistor-Transistor Logic) ou mesmo como um circuito integrado CMOS (Complementary Metal Oxide Semiconductor).
- Q_i
    - P : A linguagem Assembly (linguagem de máquina) é considerada uma linguagem de baixo nível. Ela utiliza palavras abreviadas (ou representações simbólicas), conhecidas como mnemônicos, para cada instrução de máquina, objetivando, com isso, melhor compreensão das operações por parte das pessoas (programadores, por exemplo). Vale ressaltar que, a tradução da linguagem Assembly para os códigos de máquina do processador (códigos binários) é realizada por um programa conhecido como assembler (ou montador). Com base no trecho acima e no conteúdo estudado sobre linguagem Assembly, é possível afirmar que: I. Na instrução MOV R1, R2; existem o mnemônico MOV (MOVE) e dois registradores R1 e R2 como parâmetros. II. Na instrução ADD R1, R2; existem o mnemônico ADD (ADDITION) e dois registradores R1 e R2 como parâmetros. III. A linguagem Assembly é portável para uma família de microprocessadores e, não para uma estação de trabalho. IV. O aumento da expertise do programador é uma vantagem da Assembly. Está correto apenas o que se afirma em:
    - R : LETRA E. I, II e III. 
- Q_i
    - P : Diante dos elementos básicos da linguagem Assembly, podemos afirmar que as diretivas independem do tipo de microcontrolador, sendo uma característica inerente à própria linguagem de programação. Dessa forma, cada linguagem possui a sua própria diretiva. A partir dessas informações e do conteúdo estudado sobre os elementos básicos da linguagem Assembly, é possível afirmar que as diretivas:
    - R : LETRA A. utilizam variáveis ou registros para satisfazer determinados propósitos.
- Q_i
    - P : Um microcontrolador difere de um microprocessador em vários aspectos. O primeiro aspecto refere-se à funcionalidade. Ou seja, para que um microprocessador execute as suas funções, outros componentes externos devem ser conectados para receber, enviar e processar os dados, tais como a memória principal (RAM) e o disco rígido. Por outro lado, o microcontrolador é projetado e desenvolvido para integrar inúmeros componentes em um único circuito integrado. Nessas condições, podemos dizer que nenhum componente externo torna-se necessário para o seu funcionamento interno, uma vez que todos os referidos componentes encontram-se integrados no chip microcontrolado. A partir dessas informações e do conteúdo estudado sobre microcontroladores, é possível dizer que os microcontroladores:
    - R : LETRA C. são circuitos integrados programáveis.
- Q_i
    - P : No que se refere aos compiladores para os microprocessadores PIC, podemos dizer que existem vários, cada qual necessitando de ambientes de programação distintos para atender às diversas famílias de PICs. Considerando essas informações e o conteúdo estudado sobre microcontroladores, pode-se afirmar que:
    - R : LETRA A. o MPLAB XC8, o MPLAB XC16 e o MPLAB XC32 são exemplos de compiladores.

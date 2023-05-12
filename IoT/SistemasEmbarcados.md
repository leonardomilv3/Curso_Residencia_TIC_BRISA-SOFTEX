# Sistemas Embarcados

## Tópicos Abordados

- Microcontroladores
- Componentes eletrônicos básicos
    - Resistores
    - Potenciômetro
    - LDR
    - Termistor
    - Capacitores
    - Indutores
    - Transdutor
    - Alto-falante
    - Motor CC
    - Relê
    - Interruptor de pressão
    - Micro switch
    - Reed Switch
    - Diodo
    - LED
    - Transistores
    - CI
    - Display de LCD
- Introdução as microcontroladores
    - Microcontrolador x Microprocessador
    - Arquitetura dos microcontroladores
    - Tipos de memória dos microcontroladores
- Plataforma Arduino
    - Especifiações técnicas do microcontrolador ATmega328P
    - Placa Arduino UNO
- Introdução aos sistemas embarcados
    - Arquitetura de sistemas embarcados
    - Interfaces de comunicação
- Dispositivos de entrada e saída
    - sensores e atuadores

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : A placa Arduino é dotada de diversos conectores e componentes adicionais, e foi projetada para facilitar a montagem dos protótipos de projetos eletrônicos e a programação do microcontrolador. Considerando o texto acima e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas: I. O Arduino não pode ser considerado um sistema embarcado. Porque: II. No Arduino, podemos desenvolver diversos projetos. A seguir, assinale a alternativa correta:
    - R : Letra A.  A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.
- Q_i
    - P : Leia o trecho a seguir: “O microprocessador/microcontrolador tem que ser usado para algum propósito bem definido: Controlar um processo industrial, servir de interface entre uma máquina e o usuário, controlar um terminal bancário, controlar uma impressora, um brinquedo, atuar junto com sensores no sistema de injeção de combustível de um motor etc.” Fonte: E. C. NICOLOSI, Denys. Microcontrolador 8051 Detalhado. 6ª ed. São Paulo: Érica, 2000. p. 67. A partir da leitura do fragmento apresentado, fica evidente a importância do microcontrolador em projetos específicos. Assim, e considerando os conteúdos estudados no livro da disciplina, analise as afirmativas a seguir sobre as vantagens de usar microcontroladores para a construção de circuitos eletrônicos: I. Custo baixo de projeto e construção. II. Sistema compacto (“all in one”). III. Baixo consumo de energia. IV. Facilidade de expansão da memória. Está correto apenas o que se afirma em:
    - R : Letra E.  I, II e III. 
- Q_i
    - P : Alguns componentes básicos da eletrônica são considerados como dispositivos de entrada, outros como dispositivos de saída e outros, ainda, como dispositivos de entrada e saída. Considerando o texto acima e os conteúdos estudados no livro da disciplina, com relação aos componentes, podemos afirmar que: I. O LED é um componente eletrônico que pode ser considerado como um dispositivo de entrada. II. O Piezo é um componente eletrônico que pode ser considerado um dispositivo de entrada e saída. III. O potenciômetro é um componente eletrônico considerado como um dispositivo de saída. IV. O reed switch é um componente eletrônico que pode ser considerado como um dispositivo de entrada. Está correto apenas o que se afirma em:
    - R : Letra C. II e IV. 
- Q_i
    - P : A placa Arduino UNO pode ser alimentada através de um cabo USB ligado ao computador ou através de uma fonte externa. Para alimentação externa da placa, temos um conector jack e uma entrada Vin. Na placa, temos ainda um circuito regulador de tensão que estabiliza em 5 V a tensão de entrada. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Devido ao circuito regulador de tensão e a problemas de aquecimento que podem ocorrer na placa, a tensão de entrada (fonte externa) deve estar entre 7 e 12V. II. ( ) Se for simultaneamente ligada a uma bateria de 9V e a um computador (via cabo USB), a placa Arduino UNO irá ignorar a bateria de 9V, considerando apenas a tensão proveniente do cabo USB. III. ( ) O Arduino UNO é capaz de fornecer uma tensão regulada de 3,3V para shields ou outros componentes externos. IV. ( ) Se for ligada uma bateria de 9V na placa pelo conector jack, teremos uma tensão de 9V no pino Vin da placa Arduino. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. V, F, V, V. 
- Q_i
    - P : Os sistemas embarcados são sistemas eletrônicos que combinam hardware e software para o projeto de um sistema específico. O software de um sistema embarcado é embutido no próprio microcontrolador. Considerando o texto acima e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas: I. Uma das linguagens mais usadas para programar um sistema embarcado é a Linguagem C. Porque: II. A linguagem C é uma linguagem muito popular, de propósito geral e compilada. A seguir, assinale a alternativa correta:
    - R : Letra A. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.

- Q_i
    - P : Leia o trecho a seguir: “Os microcontroladores estão presentes em quase tudo o que envolve a Eletrônica, diminuindo o tamanho, facilitando a manutenção e gerenciando tarefas internas de aparelhos eletroeletrônicos.” Fonte: MARTINS, Nardênio Almeida. Sistemas Microcontrolados: Uma abordagem com o Microcontrolador PIC 16F84. 1.ed. São Paulo: Novatec, 2005. p. 14. Considerando a citação apresentada e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas. I. Um microcontrolador está presente dentro de um notebook. Porque: II. Dentro do microcontrolador, temos a CPU, memória e periféricos de entrada e saída. A seguir, assinale a alternativa correta:
    - R : Letra A. A asserção I é uma proposição falsa, e a II é uma proposição verdadeira. 
- Q_i
    - P : A eletrônica é o ramo da ciência que estuda o uso de circuitos formados por componentes eletrônicos, com o objetivo principal de representar, armazenar, transmitir ou processar informações. Considerando o texto acima e os conteúdos estudados no livro da disciplina, com relação às características dos componentes básicos, analise as afirmativas a seguir: I. Os capacitores podem ser usados para amplificar um sinal. II. Os transistores podem ser usados como chaves controladas eletronicamente. III. O diodo é um componente semicondutor polarizado, sendo o cátodo o lado negativo. IV. O reed switch é uma chave do tipo liga/desliga acionada por infravermelho. Está correto apenas o que se afirma em:
    - R : Letra B. II e III.

- Q_i
    - P : Os sistemas embarcados são sistemas projetados para um uso específico e possuem algumas características que os diferenciam dos sistemas projetados para uso geral. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Um sistema embarcado precisa ser confiável. II. ( ) Um sistema embarcado possui um firmware. III. ( ) Um sistema embarcado permite a expansão da memória. IV. ( ) Um sistema embarcado precisa ter baixo consumo de energia. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C.  V, V, F, V. 
- Q_i
    - P : Os sistemas embarcados podem se comunicar com o ambiente externo usando diversos tipos de interfaces. Uma dessas interfaces é a interface de comunicação serial, que pode ser síncrona ou assíncrona. Considerando o texto acima e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas: I. A comunicação serial SPI é síncrona. Porque: II. O microcontrolador precisa se comunicar com um dispositivo que não tem um relógio interno. A seguir, assinale a alternativa correta:
    - R : Letra A.  As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.
- Q_i
    - P : Os sistemas embarcados estão cada vez mais presentes no nosso dia a dia. Máquinas fotográficas digitais, automóveis, equipamentos médicos e calculadoras portáteis são exemplos de sistemas embarcados. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Um sistema embarcado é um produto que envolve uso de eletrônica e software. II. ( ) Um sistema embarcado é uma combinação de hardware e software desenvolvida para desempenhar uma tarefa específica. III. ( ) Um computador é outro exemplo de sistema embarcado. IV. ( ) Um drone não pode ser considerado um sistema embarcado. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra A. V, V, F, F.
- Q_i
    - P : Um sistema embarcado é um sistema composto de hardware mais software que, após serem programados, possuem uma tarefa específica que não pode ser modificada. Considerando o texto apresentado e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas. I. Um computador não pode ser considerado um sistema embarcado. Porque: II. O computador usa um microprocessador para processar as informações de entrada. A seguir, assinale a alternativa correta:
    - R : Letra D. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.

- Q_i
    - P : O Arduino UNO é a placa mais popular e mais documentada de toda a família Arduino, sendo recomendado para iniciantes. O Arduino UNO usa o microcontrolador ATmega328P, que internamente possui três tipos de memória: Memória FLASH, Memória SRAM e Memória EEPROM. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) O Programa Arduino deve ser gravado na memória SRAM, que é um tipo de memória de alto desempenho que mantém os dados gravados mesmo se a alimentação for cortada. II. ( ) O programa Arduino deve ser gravado na memória EEPROM devido ao espaço disponível ser superior às memórias FLASH e SRAM. III. ( ) Os dados de um sensor que são armazenados em uma variável e perdidos quando a alimentação é cortada usam a memória SRAM. IV. ( ) A memória FLASH é a mais indicada para armazenar o programa Arduino. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra C. F, F, V, V.

- Q_i
    - P : Os acionadores são dispositivos de controle usados nos sistemas embarcados juntos com o microcontrolador para poder acionar e controlar elementos e equipamentos externos ao sistema. Considerando o texto acima e os conteúdos abordados na unidade, analise as asserções a seguir e a relação proposta entre elas: I. Para controlar motores CC no Arduino, devemos usar o módulo driver com ponte H L298N. Porque: II. O Arduino não consegue acionar os motores CC devido à limitação de corrente dos pinos de entrada e saída digitais. A seguir, assinale a alternativa correta:
    - R : Letra A. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I. 
- Q_i
    - P : A placa Arduino UNO possui vários conectores e componentes adicionais usados para facilitar a montagem dos protótipos e a programação do microcontrolador. Assim, considerando as informações apresentadas e os conteúdos estudados, analise os componentes indicados a seguir e associe-os com suas respectivas características: 1) Microcontrolador ATmega16U2. 2) AREF. 3) PWM. 4) ICSP (ATmega16U2). ( ) Saídas analógicas. ( ) Programação do microcontrolador. ( ) Tensão de referência para as entradas analógicas. ( ) Comunicação com o computador através de USB. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra D. 3, 4, 2, 1. 
- Q_i
    - P : Os sensores são dispositivos eletrônicos ou mecânicos capazes de detectar eventos ou alterações no ambiente e são considerados dispositivos de entrada. Na plataforma Arduino, existem diversos tipos de sensores que podem ser usados para diversos fins. Considerando essas informações e o conteúdo estudado, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Um sensor encoder pode ser usado para medir a temperatura. II. ( ) Um sensor de luminosidade pode ser usado em um robô seguidor de linha. III. ( ) Um sensor ultrassônico pode ser usado em um robô para sair de um labirinto de vidro. IV. ( ) Um sensor acelerômetro com giroscópio pode ser usado no drone para estabilizar o voo. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. F, V, V, V.
- Q_i
    - P : Nos microcontroladores, as memórias são encapsuladas no mesmo chip que a unidade central de processamento e os periféricos. Devemos dimensionar o microcontrolador em função do projeto, e para isso devemos conhecer os tipos de memória que podemos encontrar em um microcontrolador. Assim, considerando as informações apresentadas e os conteúdos estudados, analise os tipos de memórias disponíveis a seguir e associe-as com suas respectivas características: 1) Memória DRAM. 2) Memória SRAM. 3) Memória EEPROM. 4) Memória FLASH. ( ) Memória RAM de alta performance (leitura e escrita). Os dados são perdidos quando a alimentação é cortada. ( ) Memória RAM de baixo custo (leitura e escrita). Os dados são perdidos quando a alimentação é cortada. ( ) Memória ROM que pode ser usada como leitura e escrita e regravada eletronicamente. Os dados não são perdidos quando a alimentação é cortada. ( ) Memória ROM de alto desempenho que pode ser usada como leitura e escrita e regravada eletronicamente. Os dados não são perdidos quando a alimentação é cortada. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra B. 1, 2, 3, 4.

- Q_i
    - P : Os sistemas embarcados são projetados para um fim específico e, para conseguirem interagir com o mundo externo, usam diversos tipos de interface de comunicação. Assim, considerando as informações apresentadas e os conteúdos estudados, analise as interfaces a seguir e associe-as com suas respectivas características: 1) GPIO. 2) Ethernet. 3) ADC. 4) Módulo bluetooth. ( ) Interface de comunicação wireless. ( ) Interface usada para ligar através de um cabo de rede o sistema embarcado ao switch da rede local. ( ) Interface que converte sinais analógicos em digitais. ( ) Pinos digitais usados como entrada e saída. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. 4, 2, 3, 1. 
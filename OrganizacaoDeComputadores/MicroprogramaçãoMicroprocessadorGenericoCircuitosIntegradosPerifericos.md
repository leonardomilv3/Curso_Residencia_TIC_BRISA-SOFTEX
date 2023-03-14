# Microprogramação, Microprocessador Genérico e Circuitos Integrados Periféricos

## Tópicos abordados

- Microprogramação
    - Unidades de Controle de Wilkes
- Sequenciamento e execução de microinstruções
    - execução de microinstruções
- Microprocessador genérico
- Arquitetura de microprocessadores: CISC, RISC e híbrida
    - Arquitetura CISC
    - Arquitetura RISC
    - Arquitetura híbrida
- Circuitos integrados periféricos
    - Classificação quanto à sua aplicação
    - Graus de Integração
    - Tipos de Encapsulamento
    - Processos de Fabriação
    - Tipos de Tecnologia
        - CMOS
        - família TTL
        - CMOS vs família TTL


## Questionários 

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P: Leia o excerto a seguir: “Uma ALU e, na realidade, todos os componentes eletrônicos no computador são baseados no uso de dispositivos lógicos digitais simples, que podem armazenar dígitos binários e realizar operações lógicas booleanas simples.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 249. Considerando o excerto apresentado e o conteúdo estudado sobre Unidade Lógica Aritmética, pode-se afirmar que: 
    - R: a função da ULA é executar instruções dos programas que se encontram armazenadas na memória. Quando as instruções estão no microprocessador, elas devem ser interpretadas e traduzidas em operações matemáticas. 
- Q_i
    - P: Na execução de uma microinstrução, o ciclo de uma microinstrução é considerado o evento básico em um processador microprogramado. Cada ciclo é constituído de uma parte de busca e uma parte de execução. Nessas condições, considerando essas informações e os conteúdos estudados sobre a execução de microinstruções, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) A parte de busca é determinada pela geração de um endereço de microinstrução. II. ( ) A parte de execução está relacionada com a geração de sinais de controle. III. ( ) A organização de uma unidade de controle possui dois módulos lógicos de sequenciamento. IV. ( ) O controle do módulo lógico é realizado por uma microprogramação. Agora, assinale a alternativa que apresenta a sequência correta:
    - R: V, V, F, F. 
- Q_i
    - P: Leia o trecho a seguir: “Uma unidade de controle desempenha duas tarefas básicas, são elas: o sequenciamento de microinstruções para obter a próxima microinstrução da memória de controle e a execução de microinstruções para gerar os sinais de controle necessários para executar as referidas microinstruções.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 487. Tendo em vista que, em projetos de unidades de controles microprogramadas, ambas as tarefas devem ser consideradas ao mesmo tempo, e considerando o conteúdo estudado sobre microprogramação, analise as afirmativas a seguir. I. As tarefas podem comprometer o formato (tamanho) da microinstrução. II. Existem três técnicas de sequenciamento de microinstruções para que um endereço de memória de controle seja gerado para a próxima microinstrução. III. A primeira técnica refere-se ao campo de endereço único. IV. A segunda técnica está relacionada ao campo de endereço único. V. A terceira técnica trata do formato variável da informação. Está correto apenas o que se afirma em:
    - R: I, II, IV e V. 
- Q_i
    - P: Basicamente, a grande maioria dos microprocessadores se enquadram nas arquiteturas CISC (Complex Instructon Set Computer – Conjunto de Instruções Complexas para o Computador) e RISC (Reduced Instructon Set Computer – Conjunto de Instruções Reduzidas para o Computador). Porém, muitos fabricantes têm desenvolvido microprocessadores com arquitetura híbrida (arquiteturas CISC e RISC no mesmo microprocessador). A partir dessas informações e do conteúdo estudado sobre microprocessador, pode-se afirmar que:
    - R: do ponto de vista prático, a vantagem da arquitetura CISC é que ela já possui diversas instruções armazenadas no próprio processador. 
- Q_i
    - P: A Unidade Central de Processamento (UCP ou CPU) busca as instruções para serem executadas e decodificadas pelo microprograma, no caso dos computadores que integram a arquitetura CISC ou pelos circuitos lógicos presentes na arquitetura RISC. Considerando as informações apresentadas e os estudos sobre as arquiteturas CISC e RISC, pode-se afirmar que:
    - R: a arquitetura CISC possui enormes conjuntos de instruções com formatos complexos. Nesse sentido, os processadores CISC são capazes de executar centenas de instruções complexas diferentes.

- Q_i
    - P: Leia o trecho a seguir: “O termo microprograma foi criado por M. V. Wilkes no começo dos anos de 1950 (WILKES, 1951). Wilkes propôs uma abordagem para design de unidade de controle que era organizado e sistemático e evitava a complexidade de uma implementação embutida. A ideia intrigou muitos pesquisadores, mas parecia inviável porque iria requerer uma memória de controle rápida e relativamente cara.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 479. Considerando essas informações e o conteúdo estudado sobre microprogramação, é possível dizer que ela é:
    - R: uma técnica de implementação de controladores síncronos que utiliza uma memória de controle semicondutora ROM. 
- Q_i
    - P: Leia o excerto a seguir: “A unidade de controle parece um dispositivo bastante simples. Mesmo assim, implementar uma unidade de controle como uma interconexão de elementos lógicos básicos não é uma tarefa simples. O projeto deve incluir a lógica para sequenciamento por meio de micro-operações, execução de instruções, interpretação de opcodes e decisões tomadas com base em ﬂags da ULA.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 480. Considerando essas informações e o conteúdo estudado sobre unidade de controle, pode-se dizer que uma alternativa utilizada em vários processadores CISC é:
    - R: implementar uma unidade de controle microprogramada
- Q_i
    - P: Leia o excerto a seguir: “A ULA é aquela parte do computador que realmente realiza operações lógicas e aritméticas sobre os dados. Todos os outros elementos do sistema de computação, ou seja, unidade de controle, registradores, memória e E/S, existem principalmente para trazer dados para a ULA processar, e depois levar os resultados de volta. De certa forma, chegamos ao núcleo ou essência de um computador quando consideramos a ULA.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 249. Com base no trecho apresentado, e de acordo com as características operacionais da Unidade Lógica Aritmética (ULA), analise as afirmativas a seguir. I. O microprocessador é um dispositivo lógico programável capaz de acessar, controlar e executar instruções existentes da memória principal. II. A função do registrador de instrução é armazenar a instrução mais recente, que será executada pelo microprocessador. III. Entre as inúmeras funções da unidade de controle, podemos destacar a busca e a interpretação das instruções para identificar quais operações serão executadas pela unidade lógica aritmética. IV. A cache L2 é uma memória presente no interior do microprocessador. V. A função da ULA é executar instruções dos programas que se encontram armazenadas nas instruções. Está correto apenas o que se afirma em
    - R: I, II e III
- Q_i
    - P: Leia o excerto a seguir: “Todos os computadores consistem de blocos funcionais básicos que incluem uma unidade central de processamento (CPU), memória e portas de entrada/saída. Esses blocos funcionais são interconectados por três barramentos [….].” Fonte: FLOYD, T. L. Sistemas digitais: fundamentos e aplicações. 9.ed. rev. e ampl. Porto Alegre: Bookman, 2007. p. 710. Nessas condições, considerando o excerto e os conteúdos estudados sobre arquitetura interna de um microprocessador genérico, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) O barramento de dados permite a troca de dados entre os componentes presentes nas placas do computador, como, por exemplo, entre o processador e a memória. II. ( ) O barramento de endereço tem como função informar a origem e/ou destinos dos dados provenientes do barramento de dados. III. ( ) O barramento de controle atua como um controlador de acesso e uso dos barramentos internos e de endereço. IV. ( ) O barramento interno tem como função armazenar, transportar e processar informações entre os componentes internos do microprocessador. Agora, assinale a alternativa que apresenta a sequência correta:
    - R: V, V, F, F
- Q_i
    - P: Leia o trecho a seguir: “A principal vantagem do uso da microprogramação para implementar uma unidade de controle é que ela simplifica o projeto da unidade de controle. Assim a implementação fica mais barata e menos propensa a erros.” Fonte: STALLINGS, W. Arquitetura e organização de computadores. 8. ed. São Paulo: Pearson Pratice Hall, 2010. p. 485. Considerando essas informações e o conteúdo estudado sobre microprogramação, pode-se afirmar ainda que a desvantagem dela é:
    - R: A maior desvantagem da microprogramação é o uso da arquitetura CISC (Complex Instruction Set Computer – Computador com um Conjunto Complexo de Instruções) em razão da dificuldade de sequenciar as microinstruções e gerar os sinais de controle.


### Questionário II

- Q_i
    - P: A arquitetura RISC, ao contrário da arquitetura CISC, suporta uma pequena quantidade de instruções simples. Como consequência, o seu projeto é mais simples e integra menor quantidade de componentes internos em seu chip, reduzindo o custo de manufatura. A partir dessas informações e do conteúdo estudado sobre a arquitetura RISC, é possível dizer que:
    - R: o desempenho de processadores RISC é melhor quando comparado com os processadores CISC. 
- Q_i
    - P: O encapsulamento de um circuito integrado serve para envolver, proteger de umidade e auxiliar na devida dissipação de calor dos componentes internos do CI. Quanto maior a velocidade de processamento do chip, maior será a possibilidade de aquecimento. O encapsulamento pode ser metálico, cerâmico ou polimérico (de plástico). A partir dessas informações e do conteúdo estudado sobre circuitos integrados, é possível dizer que os tipos de encapsulamentos existentes na maioria dos CIs são:
    - R: encapsulamentos tipo DIL, SIL, QIL, flatpack, metálico e especial. 
- Q_i
    - P: Fotolitografia é a geração de máscaras fotográficas para as diferentes etapas de fabricação do circuito integrado. Essas máscaras permitem proteger da luz incidente zonas de um material fotorresistente depositado sobre a superfície do substrato. Considerando essas informações e o conteúdo estudado sobre circuitos integrados e periféricos, podemos afirmar que:
    - R: o material fotorresistente não modificado é retirado da superfície do substrato com uma solução química adequada, obtendo-se o molde necessário para o próximo processo de fabricação 
- Q_i
    - P: O grau (ou o tipo) de integração refere-se ao número de componentes que contém em uma pastilha de silício. Dessa forma, podemos classificar o grau de integração de acordo com algumas tecnologias. Considerando essas informações e o conteúdo estudado sobre os tipos de integração de circuitos integrados, pode-se afirmar que
    - R: a integração em escala ultralarga corresponde ao grupo de CIs que integra mais de 10 milhões de componentes por pastilha 
- Q_i
    - P: A tecnologia CMOS (Complementary Metal-Oxide Semiconductor – Metal-Óxido Semicondutor Complementar) utiliza Transistores de Efeito de Campo (FET) dos tipos MOSFET (Metal-Oxide Semiconductor Field Effect Transistor – Transistor de Efeito de Campo de Óxido de Metal) e JFET (Junction Field Efect Transistor – Transistor de Junção por Efeito de Campo) em seus processos de manufatura. Considerando essas informações e os conteúdos estudados sobre tecnologia CMOS, pode-se afirmar que:
    - R: no caso dos MOSFETs, a tecnologia CMOS utiliza tanto o MOSFET tipo N (NMOS) quanto o MOSFET tipo P (PMOS).
- Q_i
    - P: Em razão das arquiteturas CISC e RISC apresentarem características particulares, os fabricantes de processadores decidiram integrá-las; originando a arquitetura híbrida. A partir dessas informações e do conteúdo estudado sobre as arquiteturas CISC, RISC e Híbrida, é possível afirmar que:
    - R: na arquitetura híbrida, o processador trabalha mais rápido em instruções que requerem pouca complexidade (RISC) e, quando necessário, executa instruções complexas (CISC). 
- Q_i
    - P: Os principais parâmetros operacionais da tecnologia CMOS e da família lógica TTL são: as tensões elétricas operacionais definidas pelos níveis lógicos 1 (alto) ou 0 (baixo), as correntes elétricas mínimas e máximas das entradas/saídas das portas lógicas, bem como os tempos de atraso de propagação dos sinais existentes na comunicação de dados entre as portas lógicas do circuito integrado. Considerando essas informações e o conteúdo estudado sobre a tecnologia CMOS e a família TTL, podemos afirmar que:
    - R: além desses parâmetros, existe outro muito importante que deve ser considerado em projetos de circuitos lógicos, o fan-out.
- Q_i
    - P: O circuito integrado, também conhecido com CI, microchip ou chip, é um circuito eletrônico constituído por milhares (ou milhões) de dispositivos semicondutores, como, por exemplo, diodos semicondutores e transistores bipolares. Construído sobre um fino substrato de material semicondutor, o CI é considerado uma evolução no mundo da eletrônica. Com base no texto apresentado, e como de acordo com os estudos realizados sobre circuitos integrados periféricos, analise as afirmativas a seguir. I. Os CIs apresentam algumas vantagens em relação aos circuitos eletrônicos analógicos, como, por exemplo: menor peso e dimensões reduzidas. II. Os CIs são classificados quanto à sua aplicação, ao grau de integração, ao tipo de encapsulamento, ao processo de fabricação e à tecnologia empregada (CMOS e/u famílias lógicas). III. Os circuitos integrados digitais são utilizados para a amplificação de sinais. IV. Os circuitos integrados digitais operam segundo a álgebra booleana, realizando operações lógicas. Está correto apenas o que se afirma em:
    - R: I, II e IV.
- Q_i
    - P: Existem diversas famílias lógicas, como por exemplo, o RIL (Resistor Transistor Logic – Lógica de transistor e resistência), o DTL (Diode Transistor Logic – Lógica de transistor e diodo), o TTL (Transistor Transistor Logic – Lógica transistor-transistor), o HTL (High Threshold Logic – Lógica de transistor com alto limiar), ECL (Emitter Coupled Logic – Lógica de emissores ligados) e o I2L (Integrated-Injection Logic – Lógica de injeção integrada). Exceto a família lógica TTL, as demais se encontram obsoletas. Considerando essas informações e o conteúdo estudado sobre as famílias lógicas, é possível dizer que a família TTL:
    - R: é constituída, basicamente, de transistores NPN e/ou PNP, díodos de junção PN e resistências difusas. O bloco lógico padrão construtivo dessa família lógica é a porta NAND.
- Q_i
    - P: Podemos encontrar os TTLs nos circuitos lógicos computacionais, em controles de processos industriais, em equipamentos e instrumentos que utilizam a eletrônica digital como base de suas operações (como, por exemplo, painéis de controle de aviões e veículos que possuem computadores de bordo), entre outras aplicações. É importante ressaltar que tanto a tecnologia CMOS quanto a família TTL são projetadas e desenvolvidas com as típicas portas lógicas existentes na área de sistemas digitais, ou seja: as portas AND, OR, NOT, NAND, NOR, XOR e XNOR. Considerando essas informações e o conteúdo estudado sobre a família TTL, analise as afirmativas abaixo e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) Os dispositivos CMOS têm alto consumo de energia quando comparados com os dispositivos da família TTL. II. ( ) Os dispositivos CMOS apresentam rápido tempo de chaveamento quando comparados com os dispositivos da família TTL. III. ( ) Os dispositivos CMOS podem queimar com certa facilidade. IV. ( ) O custo dos dispositivos CMOS é menor do que os dispositivos da família TTL. Agora, assinale a alternativa que apresenta a sequência correta:
    - R:  F, V, V, F.

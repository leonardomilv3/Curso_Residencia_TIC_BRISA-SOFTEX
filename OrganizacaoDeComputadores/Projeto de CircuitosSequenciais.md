# Projeto de Circuitos Sequenciais I 


## Questionários 

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta


### QUESTIONÁRIO I

- Q_i
    - P: O flip-flop tipo T (Toggle), assim como o flip-flop tipo D, pode ser obtido por meio de um flip-flop JK. Nesse sentido, tanto o flip-flop tipo D quanto o tipo T são essenciais na construção de contadores e registradores de deslocamento. Considerando essa afirmação e as características operacionais dos flip-flops JK, tipo D e tipo T, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) O flip-flop tipo T tem a propriedade de alterar (Toggle) a sua saída a cada mudança (ou transição) do sinal de clock. II. ( ) No flip-flop tipo T, as entradas J e K estão curto-circuitadas. III. ( ) No flip-flop tipo T, quando o valor lido na entrada T tiver nível lógico 0, a saída do flip-flop não irá se alterar. IV. ( ) No flip-flop tipo T, caso a entrada T tenha nível lógico 1, o flip-flop não irá inverter as suas saídas. Agora, assinale a alternativa que apresenta a sequência correta:
    - R: V, V, V, F. 
- Q_i
    - P: ?
    - R: flip-flop são multivibradores biestaveis
- Q_i
    - P: Basicamente, os registradores são utilizados em operações aritméticas de complementação, multiplicação e divisão, em conversão de uma informação série em paralela, bem como em vários outros tipos de circuitos digitais. Com base no trecho apresentado e com os estudos realizados sobre registradores de deslocamento, analise as afirmativas a seguir. I. Se quisermos obter um registrador de deslocamento para a esquerda, é necessário alterar a ordem dos ﬂip-ﬂops tipo D. II. Se quisermos obter um registrador de deslocamento para a esquerda, é necessário manter a ordem dos ﬂip-ﬂops tipo D. III. O sentido de deslocamento dos dados pode ocorrer tanto para a direita quanto para a esquerda. IV. Na prática, é possível implementarmos 4 (quatro) tipos de registradores, entre eles, destacamos dois tipos: entrada e saída serial e entrada paralela e saída serial. Está correto apenas o que se afirma em:
    - R: I, III e IV. 
- Q_i
    - P:
    - R: Os contadores são utilizados em diversos situações do nosso cotidiano
- Q_i
    - P: Leia o excerto a seguir: “Registradores de deslocamento são circuitos digitais compostos por arranjos/interligações de flip-flops que têm por finalidade armazenar e transferir informações binárias (números binários) provenientes de uma fonte externa de dados. Diferentemente de um contador, os registradores não têm uma sequência específica de estados, exceto em aplicações específicas.” Fonte: FLOYD, T. L. Sistemas digitais: fundamentos e aplicações. 9. ed. reV. e ampl. Porto Alegre: Bookman, 2007. p. 510. A partir dessas informações e do conteúdo estudado sobre os registradores de deslocamento, é possível dizer que:
    - R: existem algumas formas de transmitir informações (bits) nos registradores. Ou seja, é possível inserir e retirar bits de forma serial (informação serial) ou paralela (informação paralela).

- Q_i
    - P: O flip-flop tipo D é considerado um circuito lógico básico, já que ele armazena apenas 1 (um) bit de informação. Ele possui 2 (duas) entradas e 2 (duas) saídas. Considerando essas informações e o conteúdo estudado sobre flip-flop tipo D, pode-se afirmar que:
    - R: as duas entradas do flip-flop tipo D referem-se À entrada de clock (CLK) e à entrada de dados D (Data ou Delay), onde é inserido o bit de dado. Já as duas saídas são conhecidas como Q e q 
- Q_i
    - P: O flip-flop JK foi desenvolvido para resolver o problema do estado ambíguo, ou seja, quando as entradas J e K forem iguais ao nível lógico 1. Dessa forma, esse tipo de flip-flop é muito utilizado em projetos lógicos e circuitos que contemplam aplicações da eletrônica digital. Considerando essas informações, bem como as características operacionais do flip-flop JK, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) O funcionamento do flip-flop JK é semelhante ao flip-flop RS. II. ( ) Quando o flip-flop JK está em modo de comutação (transição), isto é, quando existe variação do clock, o valor armazenado no flip-flop será alternado se as entradas J e K forem ambas iguais a 1. III. ( ) Quando J tiver nível lógico 1 e K nível lógico 0, a saída será igual a 0. IV. ( ) Quando J tiver nível lógico 0 e K nível lógico 1, a saída será igual a 1. Agora, assinale a alternativa que apresenta a sequência correta:
    - R: V, V, F, F
- Q_i
    - P: O flip-flop JK Mestre-Escravo (Master-Slave) é constituído por dois flip-flops JK com sinais de clock invertidos (um com relação ao outro) por meio de uma porta lógica inversora (porta NOT). Com base no trecho acima, bem como de acordo com as características operacionais do flip-flop JK mestre-escravo, analise as afirmativas a seguir: I. O flip-flop JK mestre-escravo foi desenvolvido para resolver uma condição indesejada no flip-flop JK. II. O flip-flop JK mestre-escravo é constituído por dois flip-flops RS com sinais de clock invertidos. III. No flip-flop JK mestre-escravo, com J = 0 e K = 0, a saída mantém-se igual ao período anterior (mantém Q). IV. No flip-flop JK mestre-escravo, quando J = 1 e K = 0, a saída terá nível lógico igual a 1. Está correto apenas o que se afirma em:
    - R: I, III e IV. 
- Q_i
    - P: Leia o excerto a seguir: “As entradas S e R do flip-flop SR são denominadas entradas síncronas porque os dados nessas entradas são transferidos para a saída do flip-flop apenas na borda de disparo do pulso de clock.” Fonte: FLOYD, T. L. Sistemas digitais: fundamentos e aplicações. 9. ed. reV. e ampl. Porto Alegre: Bookman, 2007. p.395. Tendo em vista que os flip-flops são muito utilizados em sistemas e circuitos digitais, e considerando o conteúdo estudado sobre flip-flops, analise as afirmativas a seguir: I. O flip-flop RS é um emento biestável síncrono básico. II. O flip-flop RS é composto por 4 (quatro) portas lógicas NAND. III. O flip-flop RS é composto por 5 (cinco) portas lógicas NAND. IV. No flip-flop RS, quando SET = 0 e RESET = 0, as saídas 𝑄 e 𝑄´ terão níveis lógicos alterados. Está correto apenas o que se afirma e:
    - R: I e II. 
- Q_i
    - P: Leia o excerto a seguir: “O latch é um tipo de dispositivo de armazenamento temporário que tem dois estados estáveis e é normalmente colocado numa categoria separada dos flip-flops. Os latches são similares aos flip-flops porque eles são dispositivos que podem permanecer em um dos dois estados estáveis usando uma configuração de realimentação, na qual as saídas são conectadas de volta às entradas opostas. A principal diferença entre os latches e os flip-flops é o método usado para a mudança de estado.” Fonte: FLOYD, T. L. Sistemas digitais: fundamentos e aplicações. 9. ed. rev. e ampl. Porto Alegre: Bookman, 2007. p. 388. Considerando essas informações e o conteúdo estudado sobre circuitos sequenciais, é correto afirmar que os latches são considerados dispositivos
    - R:  biestáveis. 


### QUESTIONÁRIO II

- Q_i
    - P: Os Controladores Lógicos Programáveis (Programmable Logic Controller), também conhecidos como CLPs, são equipamentos utilizados nas indústrias de manufatura devido à versatilidade nas funções de controle. Também são imunes a ruídos eletromagnéticos e resistentes as vibrações, além de proporcionarem agilidade nos processos de comunicação e de processamento de dados/informações. Considerando essas informações e o conteúdo estudado sobre controladores lógicos programáveis, pode-se afirmar que os CLPs são constituídos de:
    - R: dispositivos de entrada/saída de dados, componentes de processamento e armazenamento, barramentos, chips e softwares de programaçã 
- Q_i
    - P: De acordo com a sua aplicação na área industrial, os CLPs permitem distintas formas de programação, o que facilita a sua utilização nos mais variados sistemas de produção. A partir dessas informações e do conteúdo estudado, é possível dizer que principais aplicações dos CLPs em sistemas industriais são:
    - R: acionamento de motores, máquinas, sensores, esteiras de movimentação e acionamento de sistemas hidráulicos e pneumáticos 
- Q_i
    - P: Os barramentos podem ser considerados internos e externos. Os internos são responsáveis pela transmissão de dados entre os componentes internos da placa do computador. Por outro lado, o barramento externo interliga os periféricos do computador, como, por exemplo: disco rígido, mouse e impressora. Neste caso, são necessários entrada e saída de dados específicos do tipo USB (Universal Serial Bus – Barramento Universal Serial) para conectar impressora, pendrive ou mouse, SATA (Serial Advanced Technology Attachment – Tecnologia Avançada Serial) para conexão de discos rígidos ou HDMI (High-Definition Multimedia Interface – Interface Multimídia de Alta Definição), o qual é utilizado para transmitir áudio e vídeo de alta definição. Considerando essas informações e o conteúdo estudado sobre barramentos, analise as afirmativas abaixo e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) O barramento ISA não é mais utilizado nos computadores. II. ( ) O barramento PCI surgiu com a Intel no início de 1990 com a capacidade de transferir dados a 32 bits. III. ( ) O barramento AGP, também conhecido como porta de aceleração gráfica, foi desenvolvida pela Intel. IV. ( ) O barramento PCI Express foi desenvolvido pela AMD em 2004, surgindo para substituir os barramentos PCI e AGP. O PCI Express encontra-se disponível em vários segmentos, ou seja: 1x, 2x, 3x, 4x, 12x e 32x. Agora, assinale a alternativa que apresenta a sequência correta:
    - R: V, V, V, F.  
- Q_i
    - P: Na área de arquitetura de computadores, os barramentos (também conhecidos como BUS) são constituídos de conjuntos de linhas (fios) que transmitem dados e informações entre os componentes presentes nas placas dos computadores digitais. Entre estes componentes, podemos destacar o processador, o chipset e a memória principal (memória RAM – Random Access Memory – Memória de Acesso Aleatório). Nestas condições, podemos dizer que o barramento é um meio de transmissão compartilhado. Considerando essas informações e o conteúdo estudado sobre barramentos, pode-se afirmar que:
    - R: a velocidade do barramento é importante, tendo em vista que ela determina a quantidade de dados que ele pode transmitir. 
- Q_i
    - P: De forma geral, os barramentos de um computador podem ser classificados em três categorias principais, são elas: barramento de dados (ou linha de dados), barramento de endereços (ou linha de endereços) e barramento de controle (ou linha de controle). Considerando essas informações e o conteúdo estudado sobre barramentos, é possível dizer que o barramento de controle serve para:
    - R: controlar o acesso e uso dos barramentos de dados e de endereço, já que esses barramentos são compartilhados por todos os componentes do computador. 
- Q_i
    - P: A Norma IEC 61131-3 – Padronização Internacional de Linguagens, Estrutura de Software e Execução de Programas em Controladores Lógicos Programáveis define cinco tipos de linguagens de programação para CLPS. Considerando essas informações e o conteúdo estudado sobre controladores lógicos programáveis, podemos afirmar que os cinco tipos de linguagens de programação são:
    - R: ST (Structured Text) – Texto Estruturado, IL (Instruction List) – Lista de Instruções, LD (Ladder) – Linguagem Ladder, FBD (Function Block Diagram) – Diagrama de Blocos e SFC (Sequential Flow Chart) – Diagrama de Fluxo.
- Q_i
    - P: Programar um controlador lógico por meio da linguagem Ladder é, na verdade, controlar o acionamento de máquinas e equipamentos por meio da combinação lógica entre as saídas e os contatos de entrada. Considerando essas informações e o conteúdo estudado sobre a linguagem Ladder de programação, podemos afirmar que:
    - R: o diagrama de contatos Ladder é uma técnica adotada para descrever uma função lógica utilizando contatos (chaves) para representar as entradas e relés (bobinas ou chaves) para representar as saídas. 

# Memórias Semicondutoras e Dispositivos Lógicos

## Memórias Semicondutoras

- As memórias semicondutoras possuem células capazes de armazenar dados em unidades conhecidas como **bits**.
- E os dados são manipulados em unidades de 8 bits denominadas **byte**.
- As **memórias** podem realizar **operações de escrita e leitura**.
    - **Escrita**: insere dados em um endereço específico.
    - **Leitura**: copia os dados do endereço.

## Tipos de Memória

- **RAM**: memória de armazenamento randômico de característica volátil, ou seja, armazena dados enquanto o computador está ligado.
- **SRAM**: memória estática volátil de acesso aleatório.
- **DRAM**: memória de acesso dinâmico.
- **SRAM vs DRAM**
    - A DRAM precisa que a informação seja atualizada o tempo todo para que permaneça armazenada. Com isso, esse tipo de RAM gasta mais energia se comparado com a SRAM.
    - Já a SRAM consegue manter os bytes mesmo sem atualização contínua, perdidos somente após a interrupção da fonte de energia.
- **Discos Rígidos**: armazenamento magnético. Exemplo: HDs.
- **Fitas Magnéticas**: armazenamento óptico que utiliza um *LASER* de baixa potência para leitura e escrita dos dados. Exemplos: CD-ROM, CD-R e o CD-RW.
- **Flash**: memória não volátil de escrita e leitura. Exemplos: pen drive e cartões de memória.


### Memórias de Leitura

- **ROM**: permite apenas a leitura dos dados, já que a gravação deles é realizada pelo fabricante.
- **PROMs**: programáveis apenas para leitura, uma vez que são produzidas pelo fabricante sem programação.
- **EPROMs**: são programáveis e apagáveis por meio de radiação ultravioleta.
- **EEPROMs**: também são programadas e apagadas, porém, eletricamente, por meio de pulsos elétricos.

### Ordem de Entrada e Sída da Memória

- **FIFO** (*First In, First Out*): constituída por um conjunto de registradores de deslocamento que efutam operações básicas de entrada e saída de dados respeitando a seguinte condição: **o primeiro dado escrito na memória é o primeiro a ser lido**.
- **LIFO** (*Last In, First Out*): refer-se a uma pilha de bytes operado de forma paralela, é utilizado em aplicações que envolvem sistemas microprocessados e permite que dados e informações sejam armazenados e lidos na ordem inversa.

## Dispositivos Lógicos Programáveis

- Existem os dispositivos lógicos programáveis SPLD dos tipos **PAL e GAL**.
- Bem como o dispositivo lógico programável complexo **CPLD** (dispositivo lógico complexo programável).
- Os principais fabricantes de dispositivos lógicos programáveis são: **Altera, Cypress, Latticesemi, Philips, Vantis e Xilins**.

## Questionários 

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionario 2

- Q_i 
    - P: Leia o excerto a seguir: “Os dois tipos principais de dispositivos lógicos programáveis simples (SPLDs) são o PAL e o GAL. PAL significa lógica de arranjo programável e GAL significa lógica de arranjo genérico. Geralmente, o dispositivo PAL é programável uma vez (OTP – One-Time Programmable) e um dispositivo GAL é um tipo de PAL reprogramável […]”.
    - R: I, II e IV.
- Q_i
    - P: A partir dessas informações e do conteúdo estudado sobre o armazenamento óptico, para que os dados sejam gravados no CD-RW, deve haver:
    - R: um feixe de laser focado para aquecer o composto cristalino a uma determinada temperatura para derreter o material, resultando em um estado amorfo. 
- Q_i
    - P: A partir dessas informações e do conteúdo estudado sobre o armazenamento óptico, para que os dados sejam gravados no CD-RW, deve haver:
    - R: um feixe de laser focado para aquecer o composto cristalino a uma determinada temperatura para derreter o material, resultando em um estado amorfo. 
- Q_i
    - P: Considerando essas informações e o conteúdo estudado, pode-se afirmar que os LABs possuem:
    - R: blocos de arranjos lógicos.
- Q_i
    - P: Considerando essas informações e o conteúdo estudado sobre CPLD MAX 7000, pode-se afirmar que:
    - R: o CPLD MAX 7000 ainda integra um sistema de controle para a entrada e saída de dados que atente os subsistemas do dispositivo lógico, bem como 5 portas lógicas AND programável e 1 porta lógica OR.  
- Q_i
    - P:  Considerando essas informações e o conteúdo estudado sobre CPLD MAX 7000, pode-se afirmar que os principais atributos são:
    - R: Dependendo da série do CPLD, a densidade pode variar entre 2 a 16 LABs. Com relação à tecnologia de processo, o CPLD MAX 7000 utiliza a memória semicondutora EEPROM. A tensão de operação pode variar entre 3,3 e 5,0 V e o consumo de potência (energia) depende da tensão e da corrente elétrica, bem como da frequência elétrica de operação. Dessa forma, torna-se necessário consultar o datasheet (manual técnico de operação) do dispositivo lógico utilizado no projeto de sistemas digitais.
- Q_i
    - P: Considerando essas informações e o conteúdo estudado sobre o CPLD CoolRunner II da Xilinx, pode-se afirmar que:
    - R: Tendo em vista que a série CoolRunner II de CPLDs da Xilinx contém de 32 a 512 macrocélulas e, como existem 16 macrocélulas por bloco de função, o número de blocos de funções varia de 2 a 32. Ou seja, multiplicando o número 2 por 16 e, novamente, o número 2 agora por 32, chegaremos de fato a 32 e, respectivamente, a 512 macrocélulas.
- Q_i
    - P:  A partir dessas informações e do conteúdo estudado sobre o armazenamento óptico, é possível dizer que o laser:
    - R: Conforme o CD-ROM gira sobre um eixo movido por um motor de 12 V, o feixe de laser infravermelho de baixa potência detecta a distribuição e a configuração de pits e lands ao longo da trilha, diferenciando-os para informar a presença de 0s e 1s que irão compor o conteúdo presente no disco.
- Q_i
    - P:  Leia o trecho a seguir: “Um CPLD com arquitetura CoolRunner II usa uma estrutura do tipo PLA. Esse dispositivo tem múltiplos blocos de funções (FBs), os quais são análogos aos LABs na arquitetura MAX 7000 da Altera.” Fonte: FLOYD, T. L. Sistemas digitais: fundamentos e aplicações. 9. ed. rev. e ampl. Porto Alegre: Bookman, 2007. p. 637. Considerando essas informações e o conteúdo estudado sobre CPLD CoolRunner II, pode-se afirmar que:
    - R:A empresa Xilinx, da mesma forma que a empresa Altera, também manufatura dispositivos lógicos programáveis CPLDs, os quais, similarmente aos dispositivos lógicos estudados, também variam de acordo com a sua arquitetura, densidade, tecnologia de processo, consumo de potência elétrica, tensão elétrica de alimentação e velocidade de processamento. Existem diversas famílias e séries de CPLDs produzidos pela Xilinx, como por exemplo: a família CoolRunner II séries XC2C32A, XC2C64A, XC2C128, XC2C256
- Q_i
    - P: A partir dessas informações e do conteúdo estudado sobre dispositivos lógicos programáveis – CPLDs, é possível afirmar que
    - R: Grande parte dos dispositivos lógicos programáveis CPLDs possuem em torno de 2000 macrocélulas com centenas de pinos em seus encapsulamentos. Além disso, os CPLDs são reprogramáveis e usam tecnologia de processo de EEPROM. O consumo de potência pode variar de alguns miliwatts a algumas centenas de miliwatts e as tensões de alimentação contínua são da ordem de 2,5 V a 5,0 V (dependendo do dispositivo)
# Protocolos de Rede e Criptografia

# Tópicos Abordados

- Protocolos para Transporte Seguro: SSL/TLS, HHTPS, SSH
- Mecanismos de Criptografia
- PROTOCOLO SSL/TLS
- Protocolo HTTPS
- Protocolo SSH
- Protocolos na Camada de Aplicação: PGP


## Questionários

Afim de documentar os questionários abordados nesse conteúdo, bem como cada questão e sua respectiva resposta, foi desenvolvido uma legenda que para facilitar o entendimento dos leitores:

        Q_i - Questão com índice i (pois a ordem das questões pode ser diferente para cada participante)
        P - Pergunta
        R - Resposta

### Questionário I

- Q_i
    - P : “Um problema de segurança em seu computador pode torná-lo indisponível e colocar em risco a confidencialidade e a integridade dos dados nele armazenados. Além disto, ao ser comprometido, seu computador pode ser usado para a prática de atividades maliciosas como, por exemplo, servir de repositório para dados fraudulentos, lançar ataques contra outros computadores (e assim esconder a real identidade e localização do atacante), propagar códigos maliciosos e disseminar spam.” Fonte: CERT.br Cartilha de Segurança para a Internet: Segurança na Internet. Disponível em: . Acesso em: 29 ago. 2020. Com base no trecho apresentado e no conteúdo estudado sobre Protocolos para Transporte Seguro, pode-se afirmar que em uma comunicação segura a integridade garante:
    - R : Letra D. que a informação não foi alterada ou sofreu interferências.

- Q_i 
    - P : Após o protocolo de transporte seguro via SSH iniciar a troca de informações entre o cliente e o servidor para estabelecer a sessão criptografada, o processo de autenticação é iniciado para validar as credenciais de acesso do cliente no servidor designado. A partir do texto apresentado e do conteúdo estudado sobre Protocolo SSH, pode-se afirmar que o método de autenticação utilizado para automatização de rotinas é:
    - R : Letra A. definido por chaves compartilhadas.

- Q_i
    - P : O protocolo SSH utiliza a camada denominada SSH Connection Protocol (SSH-CONN) para definir múltiplos canais de comunicação em uma simples sessão de comunicação confiável entre o cliente e o servidor, permitindo a execução de mais de um formato de aplicação através do canal seguro. Com base no trecho apresentado e no conteúdo estudado sobre Protocolo SSH, pode-se afirmar que o canal que implementa um formato de “VPN” através da sessão SSH, para ser utilizado por comunicação sem encriptação, é o:
    - R : Letra A.  forwarded-tcpip.
- Q_i
    - P : Leia o excerto a seguir: “Na criptografia assimétrica, existem duas chaves: a chave pública e a chave privada. A chave de ciframento é publicada ou tornada acessível aos usuários, sem que haja quebra na segurança. Dessa forma, cada usuário tem uma chave de ciframento, de conhecimento público.” Fonte: ALVARENGA, L. Criptografia Clássica e Moderna. Joinville: Clube dos Autores, 2019. p. 102. A partir do texto apresentado e considerando o conteúdo estudado sobre Mecanismos de Criptografia, pode-se afirmar que um exemplo de algoritmo de encriptação assimétrico é o padrão:
    - R : Letra C. RSA.
- Q_i
    - P : Através do uso de um certificado digital é possível perceber, ao examinar as informações contidas, se algo está incorreto em relação à origem do certificado. Qualquer substituição nas informações causa a quebra de integridade do certificado, invalidando-o como mecanismo de autenticidade. A partir da leitura do texto apresentado e de acordo com o conteúdo estudado sobre Mecanismos de Criptografia, pode-se afirmar que o certificado digital é um tipo de aplicação de criptografia que visa garantir:
    - R : Letra D. uma identidade virtual.

- Q_i
    - P : O Secure Shell (SSH) foi um protocolo desenvolvido para garantir segurança na comunicação via TCP/IP para sessões remotas em substituição ao padrão Telnet, atribuindo encriptação no reconhecimento entre os hosts envolvidos e o encaminhamento dos pacotes em si. De acordo com o texto apresentado e o conteúdo estudado sobre Protocolo SSH, analise as afirmativas a seguir e assinale V para a(s) verdadeira(s) e F para a(s) falsa(s). I. ( ) A versão mais atual do protocolo SSH é a número 1. II. ( ) O Putty é um exemplo de aplicativo para utilização do SSH. III. ( ) O protocolo SSH atua na camada de transporte do modelo TCP/IP. IV. ( ) O SSH-CONN é a última camada a ser acionada quando uma sessão SSH é estabelecida. Agora, assinale a alternativa que apresenta a sequência correta:
    - R : Letra E. F, V, F, V.

- Q_i
    - P : Leia o excerto a seguir: “O uso de criptografia ajuda a proteger a sua privacidade e a privacidade das pessoas com quem você se comunica. A encriptação dificulta a ação dos sistemas de vigilância em massa. O GnuPG é uma das ferramentas que Snowden utilizou para encobrir os segredos da NSA.” Fonte: GnuPG Home. GnuPG Project. Disponível em: . Acesso em: 29 ago. 2020. (Adaptado). Com base no entendimento do texto citado e no conteúdo abordado sobre Protocolo PGP, pode-se afirmar que o GnuPG é um tipo de aplicativo que utiliza o padrão aberto para o protocolo PGP, denominado:
    - R : Letra A. OpenPGP.

- Q_i
    - P : Quando é necessário que sejam trafegados dados em um nível de sigilo maior durante uma comunicação, podemos fazer a encriptação desses dados, convertendo em informações sem sentido. Para convertê-los de volta, você os decripta utilizando um algoritmo, que pode envolver um cálculo matemático complexo. Com base no trecho apresentado e o conteúdo estudado na disciplina relacionado a Mecanismos de Criptografia, pode-se afirmar que os algoritmos de criptografia DES e 3DES utilizam o método denominado:
    - R : Letra B. chave simétrica. 
- Q_i
    - P : Leia o excerto a seguir: “O TLS depende de alguma forma de transporte confiável e, no nosso caso, o HTTPS utiliza TCP da mesma forma como é feito com HTTP […], o cliente e o servidor começam a trocar informações para fechar uma conexão TLS […]. Dezenas de pacotes são trocados para que o handshake aconteça […].” Fonte: MOLINARI, W. Descontruindo a Web: as tecnologias por trás de uma requisição. São Paulo: Casa do Código, 2016, p. 98. (Adaptado). Conforme o trecho apresentado e com base nos conhecimentos adquiridos sobre Protocolo SSL/TLS, pode-se afirmar que a primeira etapa do handshake do protocolo SSL/TLS é feita:
    - R : Letra B.  através de um envio da mensagem “Client Hello”.
- Q_i
    - P : Cada algoritmo de criptografia tem uma lista de comandos ou etapas para execução, com os quais os programas responsáveis pela encriptação recebem os dados necessários, convertendo-os em algo sem sentido, para serem transmitidos de forma segura. A partir da leitura do trecho apresentado e levando em conta os conceitos estudados na disciplina, análise as afirmativas a seguir sobre características a respeito dos algoritmos de criptografia: I. O 3DES é um tipo de criptografia de chave secreta. II. O DSA é um modelo de encriptação de chave pública para garantir que uma informação trafegue de forma confidencial. III. O RSA é um dos principais padrões utilizados de criptografia assimétrica. IV. O Blowfish é um padrão de criptografia assimétrico alternativo ao AES ou ao DES. Está correto apenas o que se afirma em:
    - R : Letra E. I e III.
- Q_i
    - P : Leia o excerto a seguir: “O protocolo HTTP é, como a grande maioria dos protocolos de aplicação da Internet, orientado a mensagens. A comunicação está baseada em pedidos de um cliente e respostas de um servidor, utilizando formatos de mensagens padronizados pelo protocolo.” Fonte: COSTA, D. Java em Rede: Recursos Avançados de Programação. Rio de Janeiro: Brasport, 2008. p. 86. Com base no trecho apresentado e no conteúdo estudado sobre Protocolo HTTPS, pode-se afirmar que, no cabeçalho de resposta do servidor HTTP ou HTTPS para o cliente, uma das informações presentes é:
    - R : Letra D.  o status da requisição.

- Q_i
    - P : Leia o excerto a seguir: “Um certificado digital pode ser comparado a um documento de identidade, por exemplo, o seu passaporte, no qual constam os seus dados pessoais e a identificação de quem o emitiu. No caso do passaporte, a entidade responsável pela emissão e pela veracidade dos dados é a Polícia Federal.” Fonte: CERT.br Cartilha de Segurança para a Internet: Segurança na Internet. Disponível em: . Acesso em: 29 ago. 2020. Conforme o trecho apresentado e com base nos conteúdo estudado sobre Mecanismos de Criptografia, pode-se afirmar que a entidade responsável pelos certificados digitais é a:
    - R : Letra B.  Autoridade Certificadora.
- Q_i
    - P : Leia o excerto a seguir: “O SSL foi criado pela Netscape na década de 90, e até hoje ainda é utilizado para algumas poucas conexões. O TLS é a nova versão do SSL, desvinculando totalmente o nome da antiga Netscape do protocolo e trazendo melhorias.” Fonte: MOLINARI, W. Descontruindo a Web: As tecnologias por trás de uma requisição. São Paulo: Casa do Código, 2016. p. 96. Conforme o trecho apresentado e com base nos conhecimentos adquiridos com relação a Protocolo SSL/TLS, pode-se afirmar que a versão 1 do TLS foi lançada como substituição para a última versão do SSL, a:
    - R : Letra E. SSL versão 2. 
- Q_i
    - P : Leia o excerto a seguir: “A ideia principal do TLS é adicionar segurança de uma forma transparente a uma comunicação. Com isso, o protocolo que usar o TLS pode continuar o mesmo, apenas utilizando-o como um encapsulamento que leva a informação de um lado para outro de forma segura.” Fonte: MOLINARI, W. Descontruindo a Web: as tecnologias por trás de uma requisição. São Paulo: Casa do Código, 2016, p. 97. Com base no entendimento do texto citado e do conteúdo abordado sobre Protocolo SSL/TLS, pode-se afirmar que a camada interna de protocolos do SSL/TLS que se comunica diretamente com o TCP é a camada:
    - R : Letra E. Record Protocol
- Q_i
    - P : O SSL é o protocolo de segurança mais amplamente utilizado quando se trata de comércio eletrônico, além de estar disponível dentro do sistema operacional de várias plataformas, fornecendo segurança não apenas em comunicações de HTTP, mas também em outros protocolos de aplicação também. Considerando o texto apresentado e de acordo com conteúdo abordado sobreo tópico, pode-se afirmar que o SSL foi gradativamente sendo sucedido por outro protocolo de comunicação segura, o:
    - R : Letra
- Q_i
    - P : O SSL é o protocolo de segurança mais amplamente utilizado quando se trata de comércio eletrônico, além de estar disponível dentro do sistema operacional de várias plataformas, fornecendo segurança não apenas em comunicações de HTTP, mas também em outros protocolos de aplicação também. Considerando o texto apresentado e de acordo com conteúdo abordado sobreo tópico, pode-se afirmar que o SSL foi gradativamente sendo sucedido por outro protocolo de comunicação segura, o:
    - R : Letra C. TLS.

- Q_i
    - P : Leia o excerto a seguir: “WWW é a abreviatura de World Wide Web (Teia de Abrangência Mundial). Em uma rede TCP/IP é o serviço que utiliza o protocolo HTTP […] para a transferência de hipertexto […]. O WWW trabalha na arquitetura cliente-servidor.” Fonte: FERREIRA, R. Linux: Guia do Administrador do Sistema. São Paulo: Novatec, 2003. p. 361. Com a análise do trecho apresentado, aliado ao conteúdo sobre Protocolo HTTPS presente na disciplina, pode-se afirmar que tanto um cabeçalho HTTP quanto sua extensão segura, o HTTPS, ao partir da solicitação de um cliente, possui entre seus dados:
    - R : Letra E. o item Query, que determina o método de requisição (como GET, por exemplo).

- Q_i
    - P : Leia o excerto a seguir: “Quando um servidor web é instalado e configurado, a aplicação recebe uma parte do sistema de arquivos no servidor web em que a aplicação pode residir. Esses diretórios permitidos normalmente estão em alguns níveis mais internos de diretórios no sistema de arquivos do servidor web.” Fonte: PAULI, J. Introdução ao Web Hacking: Ferramentas e técnicas para invasão de aplicações web. São Paulo: Novatec, 2014. Com base nas informações do texto apresentado e no conteúdo estudado a respeito de Protocolo HTTPS, pode-se afirmar que o item que identifica o caminho dos arquivos na URI do cabeçalho HTTP ou HTTPS é:
    - R : Letra E. Path
- Q_i
    - P : Leia o excerto a seguir: “Na criptografia de chave simétrica, o algoritmo usado para decifração é o inverso do algoritmo usado para encriptação. Isso significa que, se o algoritmo de encriptação usa uma combinação de adição e multiplicação, o algoritmo de decifração usa uma combinação de subtração ou divisão.” Fonte: FOROUZAN, B.; FEGAN, S. Protocolo TCP/IP. 3. ed. Porto Alegre: AMGH, 2009. p. 728. Com base no entendimento do trecho apresentado e no estudo do conteúdo abordado sobre Mecanismos de Criptografia, pode-se afirmar que o tipo de algoritmo de criptografia que utiliza a mesma chave para cifrar e decifrar a informação é:
    - R : Letra A. o algoritmo de encriptação simétrico
- Q_i
    - P : Leia o excerto a seguir: “Sempre que um acesso envolver a transmissão de informações sigilosas, é importante certificar-se do uso de conexões seguras. Para isso, você deve saber como identificar o tipo de conexão sendo realizada pelo seu navegador Web e ficar atento aos alertas apresentados durante a navegação, para que possa, se necessário, tomar decisões apropriadas.” Fonte: CERT.br Cartilha de Segurança para a Internet: Segurança na Internet. Disponível em: . Acesso em: 29 ago. 2020. A partir do trecho citado e com base no conteúdo estudado sobre Protocolo HTTPS, pode-se afirmar, sobre a relação do protocolo HTTPS com o protocolo HTTP, que:
    - R : Letra C. o protocolo HTTPS é uma extensão segura do HTTP.
- Q_i
    - P : Leia o excerto a seguir: “O OpenSSH utiliza criptografia de chave pública para autenticar usuários e para criptografar a comunicação entre dois computadores, portanto, os usuários podem fazer o login em sistemas remotos e copiar arquivos com segurança.” Fonte: DULANEY, E.; BARKAKATI, N. Linux: referência completa para leigos. Rio de Janeiro: Novatec, 2009. p. 416. A partir do trecho apresentado e com base no conteúdo estudado sobre Protocolo SSH, pode-se afirmar que o utilitário do OpenSSH responsável pela execução do servidor SSH é:
    - R : Letra D. o programa sshd.

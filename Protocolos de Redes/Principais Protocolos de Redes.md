# Principais Protocolos de Redes

##### Neste artigo listarei alguns dos Principais Protocolos de Redes e algumas de suas funcionalidades brevemente. 

• Os protocolos surgiram para que a comunicação pudesse ser realizada de 
maneira eficaz e padronizada.
• A Internet e as redes de computadores em geral fazem uso intenso 
de protocolos.
• Diferentes tipos de protocolos são usados para realizar diferentes
tarefas de comunicação.



**1) Modelo TCP/IP:** 

 A  arquitetura TCP/IP é combinação de dois protocolos TCP (Transmission Control Protocol) + IP (Internet Protocol). Eles são os responsáveis por todo o envio e recebimento de dados em todas as redes e consequentemente, na Internet. TCP/IP é uma referência do Modelo OSI, mas é a que foi implementada e está em uso até os dias de hoje. Ele é composto por 4 camadas, formando uma pilha de estrutura.

![](https://www.dltec.com.br/blog/wp-content/uploads/2019/02/osi-tcp-ip.png)

link para saber mais detalhes de cada camada: 
[Modelo OSI e suas 7 camadas - Protocolos de rede | Alura](https://www.alura.com.br/artigos/conhecendo-o-modelo-osi?gclid=CjwKCAjwscGjBhAXEiwAswQqNJh9G7ez8YhX111svACxhHfXAhec9-N2erGd-kO2D-nDNtDCc2SW9xoCax0QAvD_BwE)



**2) MAC Address (Camada Física)**

 O MAC Address ou Endereço MAC é de suma importância se tratando de redes e conexões Ethernet. Ele é a mais básica identificação de uma placa de rede ou dispositivo, cada placa possui um endereço único. Dispositivo como Switch por exemplo faz uma conexão entre o endereço de origem até o endereço de destino. A conexão funciona com dois protocolos, o endereço IP e o MAC, sendo que o endereço IP é a primeira opção para envio de pacotes. Se o destino não está no mesma rede IP do remetente, é necessário enviar para o roteador configurado.

 Endereço MAC é um número de série de 48 bits exibido em 12 dígitos hexadecimais, os 6 primeiros dígitos informam o fabricante que serve para identificar aquele dispositivo de rede Ethernet ou Wi-Fi e os outros 6 são o número de série.

![https://www.mundotibrasil.com.br/wp-content/uploads/2014/07/cmd.png](https://www.mundotibrasil.com.br/wp-content/uploads/2014/07/cmd.png)



**3) ETHERNET (Camada Física/Enlace)**

 Ethernet é um protocolo de conexão que gerencia como os dispositivos e computadores se comunicam em uma rede local (LAN). Muito comum em ambientes corporativos, esse protocolo facilita o acesso e a troca de informações e arquivos entre máquinas que estão na mesma rede.

 O Ethernet também dá nome aos cabos de conexão presentes nos equipamentos. Esse cabo é utilizado em modens e roteadores para distribuir a internet nos equipamentos. 

 Principais vantagens de utilizar conexão cabeada é a velocidade, estabilidade e segurança. Existem três tipos principais de redes que são configuradas com a ethernet, Fast Ethernet, Gigabit Ethernet e Switch Ethernet. 

![](https://www.electronicshub.org/wp-content/uploads/2021/03/Ethernet-1.png)



**4) PPP (Camada Enlace)**

 O Point-to-Point Protocol, ponto-a-ponto é um protocolo para transmissão de pacotes através de linhas seriais. É projetado para transportar pacotes através de uma conexão entre dois pontos. A conexão entre os pontos deve prover operação full-duplex sendo assumido que os pacotes são entregues em ordem. Estas características são desejadas para que o PPP proporcione uma solução comum para a conexão de uma grande variedade de hosts e roteadores.

 Ele pode fornecer autenticação de conexão, criptografia de transmissão e compressão. O PPP é usado sobre muitos tipos de redes físicas incluindo cabo serial, linha telefônica, telefone celular, enlaces de rádio especializados e enlaces de fibra ótica. O PPP é composto basicamente de três partes, sendo que a interação entre elas obedece a um diagrama de fases(Encapsulamento de data gramas, Link Control Protocol (LCP), Network Control Protocols (NCPs). 

 Dois derivados dele são o Point-to-Point Protocol over Ethernet (PPPoE), e Point-to-Point Protocol over ATM (PPPoA), são usados mais comumente por Provedores de Serviços de Internet para estabelecer uma conexão de serviços de Internet de Linha Digital de Assinante (ou DSL) com seus clientes.



**5) ARP (Camadas Rede/Enlace)**

 O ARP (Address Resolution Protocol – protocolo de resolução de endereços) é um protocolo utilizado para resolução de endereços físicos, isto é, eles têm a função de mapear ou traduzir qual endereço físico está vinculado a um determinando endereço IP de um host remoto. Isto é necessário em redes da família Ethernet para que o quadro de camada 2 possa ser montado e enviado localmente até seu destino (que pode ser a Internet, por exemplo). O mecanismo de tradução de endereços implementado pelo ARP é baseado no uso de broadcast.



**6) IP (Camada Rede)**

 O IP (Internet Protocol) é um dos principais protocolos utilizados na comunicação de dados na Internet. É responsável pela identificação e endereçamento dos dispositivos conectados em uma rede, permitindo que eles se comuniquem entre si e garante que os dados enviados cheguem ao destinatário correto. Cada dispositivo em uma rede tem um endereço IP único, que é formado por uma série de números separados por pontos. 

 IPv4 versão 4 e IPv6 versão 6 são dois tipos diferentes de endereços IP usados na comunicação de dados pela Internet. O IPv4 é a versão mais antiga e mais comum, ele usa endereços IP de 32 bits. O IPv6, por sua vez, ele usa endereços IP de 128 bits. Uma diferença importante é que o IPv6 suporta recursos avançados como, melhor suporte para multicast e autoconfiguração de endereço e qualidade de serviço, que não estão disponíveis no IPv4.

 O IP depende de roteadores para encaminhar pacotes de dados pela rede. Cada roteador verifica o cabeçalho do pacote e encaminha o pacote para o próximo roteador na rota até o destinatário. Sem roteadores, a comunicação entre dispositivos na Internet seria impossível. O IP é representado por um conjunto de quatro números: por exemplo, 192.158.1.38. Cada número do conjunto pode variar entre 0 e 255. Ou seja, o intervalo de endereçamento IP vai de 0.0.0.0 a 255.255.255.255.

![](https://www.hardware.com.br/static/20140325/redes-comand1.png)

link para saber mais detalhes específicos do Endereço IP:
https://www.avg.com/pt/signal/what-is-an-ip-address



**7) ICMP (Camada Rede)**

 Internet Control Message Protocol é um protocolo para determinar a disponibilidade da rede e gerenciar o tráfego e o controle de erros na camada de rede. Este protocolo diagnostica problemas de conectividade de rede ou transferência de dados entre dispositivos. Ele auxilia enviando, recebendo e processando mensagens ICMP para relatar problemas de conectividade aos dispositivos de rede de origem.

 Portanto, o principal objetivo do protocolo ICMP é relatar erros na camada de rede. No entanto, atores mal-intencionados podem manipular seus recursos para lançar ataques como ataques distribuídos de negação de serviço (DDoS).



**8) TCP e UDP (Camada de Transporte)**

 O protocolo TCP é, talvez, o mais utilizado. É voltado à conexão e tem como garantia a integridade, segurança e ordem de todos os dados. É interessante notar que o TCP permite o envio simultâneo de dados de ambos os pontos ao outro, durante todo o fluxo de comunicação. Com o TCP, de fato temos uma conexão entre um ponto e outro, comumente chamados de servidor e cliente.

 O protocolo UDP (User Datagram Protocol) tem, como característica essencial, não ser orientado a conexão, por falta de confiabilidade, porém é veloz. Pode-se enviar data gramas de uma máquina à outra, mas sem garantia de que os dados enviados chegarão intactos e na ordem correta. O UDP tem sua grande vantagem quando se trata de serviços cuja velocidade é fundamental e a perda mínima de dados não muito desvantajosa. 

 O que determina essa escolha é o tipo de aplicação a ser utilizada pelo desenvolvedor.

![](https://dicionariotec.com/public_html/images/tcpnudp.jpg)



**9) FTP (Camada Aplicação/Transporte)**

  FTP (File Transfer Protocol) é um protocolo padrão usado para transferir arquivos entre computadores via conexões TCP/IP na rede. Ele permite que usuários autorizados enviem e recebam arquivos de servidores FTP, sendo assim, um modelo de transferência de arquivos da camada de transporte e da camada de aplicação com servidores FTP. 

 O protocolo FTP permite que usuários autorizados possam fazer download e upload de arquivos de um servidor FTP, um computador que armazena os dados. Dessa forma, o FTP facilita a transferência de informações entre diferentes dispositivos. O FTP permite que você transfira múltiplos arquivos de modo simultâneo e facilitado. 

O FTP não tem qualquer recurso de segurança incorporado. Isso significa que ele geralmente é fácil de ser haqueado, já que ele transfere dados de texto simples sem qualquer criptografia.

 

**10) SSH (Camada Sessão/Aplicação)**

 O protocolo SSH (Secure Shell) é um método seguro e confiável para conectar-se a servidores remotos e realizar tarefas administrativas, como gerenciamento de arquivos e processos. Com ele, é possível acessar seus servidores de forma segura e privada, sem precisar se preocupar com invasões ou interceptações de dados. 

 O SSH foi criado para resolver essa questão de segurança, permitindo a conexão e comunicação entre o cliente e o servidor de forma segura, através da criptografia das informações. Ele se tornou uma das ferramentas mais utilizadas para gerenciar servidores remotamente e tem sido amplamente utilizado em vários setores.

![](https://www.ipxo.com/app/uploads/2022/02/What-is-SSH-820x460.jpg)



**11) SNMP (Camada Aplicação)**

 Simple Network Management Protocol  é o protocolo mais usado para saber o que acontece dentro de ativos de redes e serviços, já que permite trabalhar com produtos e serviços de diversos fabricantes. Principais soluções de monitoramento de redes fornecem alertas (SMS, E-mail ou PUSH) para comunicar falhas na infraestrutura de rede. Seu funcionamento se dá através de uma solicitação ou alteração de configuração de status.

 Em resumo, sua função básica é facilitar a troca de informações de gerenciamento entre os dispositivos da rede. Para isso, fornece dados de status dos elementos ativos da rede e estatísticas importantes para seu funcionamento, como uso, taxa de erros, vazão, nível de colisão, entra outros.

![](https://static.wixstatic.com/media/911aa6_20122c4c57204ccc92d2d9f3e8973cd2~mv2.png/v1/fit/w_1000%2Ch_628%2Cal_c%2Cq_80,enc_auto/file.jpg)



**12) NTP (Camada Aplicação)**

 Network Time Protocol é o padrão que permite a sincronização dos relógios dos dispositivos de uma rede como servidores, estações de trabalho, roteadores e outros equipamentos à partir de referências de tempo confiáveis. O NTP permite manter o relógio de um computador sincronizado com a hora sempre certa e com precisão de milissegundos. 

 O NTP usa um algoritmo para sincronizar o tempo em uma rede usando escalas de tempo como UTC e pode suportar recursos como o salto de segundos - adicionado para compensar a desaceleração da rotação da Terra. No entanto, o NTP pode sincronizar as redes com um relógio atômico usando a rede do sistema de posicionamento global (GPS) ou a transmissão de rádio especializada. Os relógios atômicos são os dispositivos de manutenção de tempo mais absolutos.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Network_Time_Protocol_servers_and_clients.svg/350px-Network_Time_Protocol_servers_and_clients.svg.png)



**13) HTTP e HTTPs (Camada Aplicação)**

 O Protocolo (HyperText Transfer Protocol) é usado principalmente em redes baseadas em IP para a transmissão de páginas web de um servidor para o navegador. Ele funciona sem criptografia e não se limita a aplicativos. 

 Uma unidade de comunicação em HTTP é chamada de mensagem, sendo feita uma distinção entre solicitação ou consulta e resposta: a solicitação é feita do cliente ao servidor web, enquanto a resposta se refere à ação subsequente do servidor ao cliente.

 Além disso, o Protocolo de Transferência de Hipertexto inclui a opção de autenticação do usuário. Se um nome de usuário e uma senha forem necessários para um arquivo, o servidor relata isso ao navegador web. O HTTP é usado para carregar páginas web da World Wide Web (WWW) em um navegador. Por outro lado, o protocolo HTTPS garante a segurança em um site. 

 O protocolo HTTPS (HyperText Transfer Protocol Secure) é uma forma de proteger a comunicação entre dois sistemas, como servidor e navegador. Ele permite o trânsito de dados confidenciais, como números de cartão de crédito, informações bancárias e credenciais de login. O ícone de cadeado, bem como o HTTPS, o certificado SSL e as informações detalhadas, mostram rapidamente ao usuário se a página é segura ou não. 

![](https://www.datarain.com.br/wp-content/uploads/2020/08/HTTP-vs-HTTPS-300x153.png)



**14) DHCP (Camada Aplicação)**

 DHCP é a sigla para (Dynamic Host Configuration Protocol). Trata-se de um protocolo utilizado em redes de computadores que permite a estes obterem um endereço IP automaticamente. Em uma rede local ele distribui endereços IP na medida em que as máquinas solicitam conexão à rede. Quando um computador desconecta, seu IP fica livre para uso de outra máquina. Para isso, o servidor geralmente é configurado para fazer uma checagem da rede em intervalos pré-definidos.

 Um exemplo importante sobre o uso de DHCP é o caso dos provedores de internet. Na maioria dos casos, a máquina do usuário recebe um endereço IP diferente para cada conexão à internet. Isso é possível graças à combinação do DHCP com outros protocolos, o PPP (Point to Point Protocol), por exemplo.

 Em resumo, ele atribui endereços de IP automaticos e variáveis, oferecendo configuração dinâmica de hosts e outros parâmetros de configuração para clientes de rede.

![](https://www.valuehost.com.br/blog/wp-content/uploads/2022/12/post_thumbnail-416d9756493bb261933c9a08a83ed837.jpeg)

**15) DNS**

 Domain Name System não é necessariamente um protocolo, mas sim um servidor que contém nomes de domínio na internet, mas por padrão o DNS usa o protocolo User Datagram Protocol UDP para servir as solicitações e as requisições. É um sistema que contém uma lista de nomes de domínio e permite que usuários encontrem uma página por meio desses nomes.

 Ele funciona como uma "lista telefônica de toda a internet", ele quem traduz endereços IP em nomes de sites. Um serviço que se encarrega de conectar você a todos os sites da internet, sem precisar digitar uma série de endereços IP.

 Existem duas formas de acessar um site na internet: digitando o nome de domínio que formam a URL ou digitando o endereço IP da sua hospedagem.

![](https://academy.bit2me.com/wp-content/uploads/2019/05/49_DNS.png)
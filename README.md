# REDES-e-Infraestrutura

# Protocolo
Um conjunto de regras que define como os dispositivos se comunicam em uma rede. Exemplos incluem HTTP, FTP, IP, TCP e UDP.

# IP
O Protocolo de Internet (IP) é responsável pelo endereçamento e encaminhamento dos pacotes de dados. Existem duas versões principais: IPv4 e IPv6.

# TCP-IP
Um conjunto de protocolos que define como os dados são transferidos na internet. É composto por:

# TCP (Transmission Control Protocol): Confiável e orientado à conexão.

# IP (Internet Protocol): Gerencia o endereçamento e o roteamento.

# Pacotes Novell
Pacotes utilizados no protocolo IPX (Internetwork Packet Exchange) no sistema de rede Novell NetWare. Foi amplamente usado antes da popularização do TCP/IP.

# Pacotes Apple
Formatos usados por protocolos AppleTalk, um sistema de rede desenvolvido pela Apple para comunicação entre dispositivos.

# ICMP
O Internet Control Message Protocol é usado para enviar mensagens de erro e diagnóstico na comunicação de redes. Exemplos incluem o comando ping.

# Ping da Morte
Ataque que explora vulnerabilidades ao enviar pacotes ICMP grandes, podendo causar falhas ou travamentos no sistema de destino.

# Interface de Rede
O hardware ou software que conecta um dispositivo à rede, como placas de rede (NICs) ou interfaces virtuais.

#LAN, #WAN, #MAN, #RAN, #CAN, #PAN, #SAN, #WLAN
#LAN (Local Area Network): Rede local, pequena (ex.: casa ou escritório).
#WAN (Wide Area Network): Rede ampla, cobrindo grandes áreas (ex.: internet).
#MAN (Metropolitan Area Network): Rede para áreas metropolitanas.
#RAN (Radio Access Network): Rede de acesso via rádio (ex.: redes móveis).
#CAN (Campus Area Network): Conecta várias LANs em um campus.
#PAN (Personal Area Network): Rede pessoal de curto alcance (ex.: Bluetooth).
#SAN (Storage Area Network): Rede de armazenamento.
#WLAN (Wireless LAN): Rede local sem fio.
Diferenças entre LAN e WAN (Hardware e Largura de Banda)
#LAN:
Hardware: Switches, hubs, roteadores simples.
Largura de Banda: Alta (Gigabit ou superior).
#WAN:
Hardware: Roteadores avançados, conexões de longa distância.
Largura de Banda: Geralmente menor, devido às longas distâncias.
Colisão (CSMA-CD)
No Carrier Sense Multiple Access with Collision Detection, os dispositivos verificam se o canal está livre antes de transmitir. Caso ocorra uma colisão, os dados são retransmitidos.

#HUB
Dispositivo simples que distribui dados para todos os dispositivos conectados, sem distinção de destino. Propenso a colisões.

#Switch
Dispositivo que encaminha pacotes para dispositivos específicos com base em endereços MAC, reduzindo colisões.

#Router
Encaminha pacotes entre redes diferentes, utilizando tabelas de roteamento.

O que acontece quando o Router não conhece o caminho?
Ele descarta o pacote e pode enviar uma mensagem ICMP informando o problema.

O que acontece quando um Pacote não chega até o destino?
No TCP, o emissor retransmite o pacote após um tempo. No UDP, o pacote é simplesmente descartado.

#TCP
Protocolo orientado à conexão.
Garante entrega confiável.
Realiza retransmissão e controle de congestionamento.
#UDP
Protocolo não orientado à conexão.
Mais rápido, mas não confiável.
Usado em streaming, VoIP e jogos.
#Proxy
Um servidor intermediário que atua entre o cliente e o destino final.

#Funções do Proxy
Cache de dados.
Filtragem de conteúdo.
Anonimato.
Balanceamento de carga.
Firewall
Dispositivo ou software que monitora e controla o tráfego de rede com base em regras predefinidas.

#Portas
Identificadores numéricos para diferentes serviços de rede (ex.: 80 para HTTP).

#Portas Comuns

80: HTTP.
110: POP3 (recebimento de e-mails).
25: SMTP (envio de e-mails).
21: FTP (transferência de arquivos).
23: Telnet (comunicação remota não segura).

#DNS


O Domain Name System traduz nomes de domínio (ex.: www.google.com) em endereços IP.

O IPv4 (Internet Protocol version 4) utiliza um sistema de endereçamento baseado em 32 bits. Esses endereços são divididos em cinco classes principais: Classe A, B, C, D e E. Vamos detalhar as classes de IPv4:

1. Classe A
 Intervalo de endereços: 0.0.0.0 a 127.255.255.255
Destinado a: Redes muito grandes.
Estrutura:
Bits iniciais: Sempre começa com 0.
Quantidade de redes: 2⁷ = 128 redes (os endereços 0 e 127 são reservados).
Quantidade de hosts por rede: 2³¹ - 2 = 16.777.214 hosts.
Máscara padrão: 255.0.0.0 ou /8.
Exemplo de endereço: 10.0.0.1.

2. Classe B
Intervalo de endereços: 128.0.0.0 a 191.255.255.255
Destinado a: Redes de tamanho médio a grande.
Estrutura:
Bits iniciais: Sempre começa com 10.
Quantidade de redes: 2¹⁴ = 16.384 redes.
Quantidade de hosts por rede: 2¹⁶ - 2 = 65.534 hosts.
Máscara padrão: 255.255.0.0 ou /16.
Exemplo de endereço: 172.16.0.1.

3. Classe C
Intervalo de endereços: 192.0.0.0 a 223.255.255.255
Destinado a: Redes pequenas (como LANs).
Estrutura:
Bits iniciais: Sempre começa com 110.
Quantidade de redes: 2²¹ = 2.097.152 redes.
Quantidade de hosts por rede: 2⁸ - 2 = 254 hosts.
Máscara padrão: 255.255.255.0 ou /24.
Exemplo de endereço: 192.168.0.1.

4. Classe D
Intervalo de endereços: 224.0.0.0 a 239.255.255.255
Destinado a: Multicast (comunicação de um para vários).
Estrutura:
Bits iniciais: Sempre começa com 1110.
Não utiliza máscara de sub-rede.
Exemplo de uso: Transmissão de vídeo em grupo.
[IP.pptx](https://github.com/user-attachments/files/18566702/IP.pptx)
[Atividade REDES.docx](https://github.com/user-attachments/files/18566701/Atividade.REDES.docx)
![Ip-Classes](https://github.com/user-attachments/assets/c4f1d850-6c01-4604-8c1a-d4e425caf11d)

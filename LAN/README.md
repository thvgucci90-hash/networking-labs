# LAN - Local Area Network

## 1. Objetivo

Construir uma rede local (LAN) utilizando o Cisco Packet Tracer, conectando quatro computadores a um switch e configurando a comunicação entre os dispositivos por meio de endereçamento IPv4.

## 2. Topologia

A rede foi construída utilizando quatro computadores conectados a um switch.

PC1 ─────┐
PC2 ─────┤
PC3 ─────┤── Switch
PC4 ─────┘

## 3. Dispositivos utilizados

4 computadores (PC-PT)
1 switch Cisco 2960
Cabos Ethernet Copper Straight-Through

## 4. Endereçamento IPv4

Foi utilizada a rede 192.168.10.0/24, com máscara 255.255.255.0.

| Dispositivo | Endereço IPv4 | Máscara de sub-rede |
| ----------- | ------------- | ------------------- |
| PC1         | 192.168.10.10 | 255.255.255.0       |
| PC2         | 192.168.10.11 | 255.255.255.0       |
| PC3         | 192.168.10.12 | 255.255.255.0       |
| PC4         | 192.168.10.13 | 255.255.255.0       |
*Não foi configurado gateway padrão, pois todos os dispositivos pertencem à mesma rede local e não foi utilizado um roteador neste laboratório.

## 5. Configuração

Os endereços IPv4 foram configurados manualmente em cada computador através de:

PC → Desktop → IP Configuration

Cada computador recebeu um endereço diferente dentro da rede 192.168.10.0/24.

## 6. Testes de conectividade

Após a configuração dos endereços IPv4, foram realizados testes utilizando o comando ping para verificar a comunicação entre os computadores.
EX. PC1 → ping 192.168.10.11

Também foram realizados testes entre os demais dispositivos da rede.

Os testes confirmaram a comunicação entre os computadores conectados ao switch.

## 7. Observações

Durante o laboratório, foi possível observar a comunicação entre dispositivos pertencentes à mesma rede utilizando endereçamento IPv4.

Também foi utilizado o comando: arp -a
*para observar as informações de endereços associadas aos dispositivos após a comunicação.

## 8. Resultado

A rede local foi configurada com sucesso e os computadores conseguiram se comunicar entre si através do switch.

## 9. O que aprendi

Neste laboratório, pratiquei:

construção de uma rede LAN;
conexão de computadores a um switch;
utilização de cabos Ethernet;
configuração manual de endereços IPv4;
utilização de máscara de sub-rede;
identificação de dispositivos dentro da mesma rede;
teste de conectividade utilizando ping;
observação das informações de ARP.

## 10. Ferramenta utilizada
Cisco Packet Tracer

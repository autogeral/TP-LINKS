# TP-LINKS



Habilitar Wan e Wan/Lan1 para lojas que tenha 2 links de internet, e Wan/Lan2 para as que tenha 3 links. 
E clicar em Salvar 

![Captura de tela 2024-06-26 134812](https://github.com/autogeral/TP-LINKS/assets/100229068/0f5e6893-9554-46e4-9fd9-6bdce52866ae)


![Captura de tela 2024-06-26 134452](https://github.com/autogeral/TP-LINKS/assets/100229068/9d8d1ecb-5c7f-4847-bd7d-64606b5063fd)

Configurando cada Wan e Lan 

No Exemplo do firewall da loja de indaiatuba, foi estabelecido que a Wan, no caso a internet principal, que é a VIVO, ficasse com o tipo de conexão com IP Dinâmico 

![Captura de tela 2024-06-26 141406](https://github.com/autogeral/TP-LINKS/assets/100229068/188a5fbd-4a0b-41df-af63-a6b2dbfd0c14)

Em WAN/LAN1, também fica com a conexão dinâmica, nesta a internet é a ALGAR.

![image](https://github.com/autogeral/TP-LINKS/assets/100229068/7371924e-5270-4a30-a7d2-9427d09452fa)

e em WAN/LAN2 também com conexão ip dinâmica, a internet é a CLARO

![image](https://github.com/autogeral/TP-LINKS/assets/100229068/25b25894-0af8-4808-b4c1-b341de4f0a5d)












 

 

 

 

 

 

 

 

 

 

Após isso ainda na aba Rede, clicar em Lan e em configurações, habilitar Proxy IGMP igual esta na imagem abaixo: 

 

 

Em listas de Redes, como no exemplo esta o firewall de Indaiatuba, esta configurado o ip de acesso externo ao firewal, 10.50.5.254 

 

 

 

 

 

 

 

Que é possível alterar, clicando ali abaixo da operação, que vai abrir esta tela, então adicionar o endereço ip da loja em que você esta configurando o firewall: 

 

  

Bem como, habilitar ou não a opção deste firewall ser um Servidor DHCP: 

 

Onde você deve definir o range de ip inicial e final, como no exemplo, 10.50.5.100 e 10.50.5.199 

 

 

 

 

 

 

 

 

 

É possível também, quando se é um servidor DHCP, adicionar um IP e reservá-lo, segue exemplo 

 

 

 

 

 

 

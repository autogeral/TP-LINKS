# TP-LINKS #

Configurando a parte básica de um firewall ER605

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

![Captura de tela 2024-06-26 135009](https://github.com/autogeral/TP-LINKS/assets/100229068/77e4c834-facc-47fb-a3b5-4a58e1af27f9)

Em listas de Redes, como no exemplo esta o firewall de Indaiatuba, esta configurado o ip de acesso externo ao firewal, 10.50.5.254

![Captura de tela 2024-06-26 135323](https://github.com/autogeral/TP-LINKS/assets/100229068/642be166-ca4f-41d9-a7b5-6f70e1f4eeed)

Que é possível alterar, clicando ali abaixo da operação, que vai abrir esta tela, então adicionar o endereço ip da loja em que você esta configurando o firewall: 

![Captura de tela 2024-06-26 140339](https://github.com/autogeral/TP-LINKS/assets/100229068/aae7b449-3f5b-4807-8634-c43521c21254)

Bem como, habilitar ou não a opção deste firewall ser um Servidor DHCP: 

![Captura de tela 2024-06-26 140605](https://github.com/autogeral/TP-LINKS/assets/100229068/4b536428-dbf8-4bcd-9a02-474d207d869d)

Onde você deve definir o range de ip inicial e final, como no exemplo, 10.50.5.100 e 10.50.5.199 

![Captura de tela 2024-06-26 140753](https://github.com/autogeral/TP-LINKS/assets/100229068/481fe605-40c1-4d47-a210-1bd8cfb51fe6)




 

 

 

 

 

 

 

 

 

É possível também, quando se é um servidor DHCP, adicionar um IP e reservá-lo, segue exemplo 

 

 

 

 

 

 

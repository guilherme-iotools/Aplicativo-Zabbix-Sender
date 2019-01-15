# Zabbix-Sender
Aplicativo Zabbix Sender, desenvolvido para Android.

Este aplicativo foi desenvolvido para Android. São dois Arquivos:

-- Zabbix_post_autenticacao.apk --> Instalador do aplicativo no Android. Basta colocar no celular e rodar o App

-- Zabbix_post_autenticacao.aia --> Código fonte. É necessário importar o projeto na plataforma App Inventor 2.

O objetivo geral do aplicativo é enviar informações do celular do usuário para um determinado item no Zabbix. Para isso,
é necessário inserir a chave do item e o nome do Host, de outras informações como o IP do servidor e a porta padrão do Zabbix Sender (10051).

Um breve tutorial foi disponibilizado no Canal da IoTools, no Youtube:
--> https://www.youtube.com/watch?v=nFLO7QceEv4&index=2&list=PLl6eaqJjI6AywgwQl5c5E7OeEQrogRrrJ

Duas aplicações exemplo foram adicionadas ao App: 

--> Bateria do celular: informações de temperatura (ºC), nível de bateria (%) e tensão (V).
--> Acelerômetro: Acelerações nos eixos x, y e z.


Também estamos disponibilizando os Hosts e Mapas usados nos testes desse projeto:

-- zbx_export_hosts.xml --> Host -- zbx_export_maps.xml --> Mapa

É preciso importar esses arquivos no servidor Zabbix.

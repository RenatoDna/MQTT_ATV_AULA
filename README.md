Codigo exemplo de conexao MQTT - ESP32 

servidor broker fou usado o app: MQTT Broker
https://play.google.com/store/apps/details?id=in.naveens.mqttbroker&hl=pt_BR&pli=1

O cliente foi usado o app: MQTT Dashboard Client
https://play.google.com/store/apps/details?id=com.doikov.mqttclient&hl=pt_BR


Descrição: 
O codigo gravado no esp32 realiza a conexao no wifi e apos se conecta MQTT SERVER,

No APP MQTT Dashboard Client e configurado um botao em modo switch que ao enviar o valo 1 ele ligara a led e ao enviar o valor 0 desligara o led e o servidor broker, segue dados de configuração do botao e servidor na pasta "documentacao/MQTT_Dashboard_Client".

No app MQTT Broker foi configurado dados do servidor, segue dados de configuração do servidor na pasta "documentacao/MQTT_Broker.

nota: 
no codigo deve ser colocado nome da wifi/senha e nome usuario e senha do servidor MQTT_Broker segue abaixo linhas que devem ser alteradas no codigo:

// Definições de conexão: Pino, Wi-Fi e MQTT

#define WIFI_SSID          "rede wifi"    
#define WIFI_PASS          "senha wifi"
#define MQTT_USER          "usuario mqtt"    
#define MQTT_PASS          "senha servido mqtt"




política de Privacidade
Aplicativo: Controle Remoto de TV  · Pacote: io.tvremote.control  · Última atualização: abril de 2026

📋
Visão geral
O aplicativo TV Remote Control ("o aplicativo") é um aplicativo Android que permite controlar dispositivos Android TV e Google TV na sua rede Wi-Fi local. Esta política explica quais informações o aplicativo acessa e como elas são usadas.

✅ Este aplicativo não coleta, armazena ou transmite quaisquer dados pessoais para servidores externos. Todas as funcionalidades operam inteiramente no seu dispositivo e rede local.
📡
Descoberta de rede e dispositivos
O aplicativo requer acesso à sua rede Wi-Fi local para:

Analise a rede local (LAN) para descobrir dispositivos Android TV/Google TV.
Estabeleça uma conexão direta com o dispositivo de TV selecionado.
Envie comandos de controle remoto (navegação, volume, teclado, etc.) via Wi-Fi.
A varredura de rede é realizada localmente no seu dispositivo . Nenhum nome de dispositivo, endereço IP ou dado de rede é transmitido para qualquer serviço externo.
💾
Armazenamento local
O aplicativo armazena os seguintes dados localmente apenas no seu dispositivo :

Nome e endereço IP do último dispositivo de TV emparelhado.
Certificados TLS usados ​​para emparelhamento seguro com sua TV.
Status de emparelhamento e preferências do dispositivo
Esses dados são armazenados usando o SharedPreferences/DataStore do Android e nunca são enviados ou compartilhados com terceiros.

🔒
Explicação das permissões
INTERNET – Necessária para comunicação com a sua TV via Wi-Fi.
ACCESS_NETWORK_STATE / ACCESS_WIFI_STATE – Detectar conexão Wi-Fi ativa
CHANGE_WIFI_MULTICAST_STATE – Necessário para a descoberta de dispositivos mDNS/NSD na rede local.
DISPOSITIVOS WI-FI PRÓXIMOS (Android 13+) – Busca dispositivos próximos sem acesso à localização.
VIBRAR – Feedback tátil opcional ao pressionar os botões do controle remoto.
O aplicativo não solicita permissão de localização no Android 13 e versões superiores. No Android 12 e versões anteriores, o equivalente a NEARBY_WIFI_DEVICES requer uma permissão de localização no nível do sistema operacional, mas o aplicativo não usa nem armazena dados de localização.
👤
Dados pessoais
O aplicativo não coleta:

Nome, e-mail ou qualquer informação da conta
Dados de localização
Análises de utilização ou relatórios de falhas enviados a terceiros
Identificadores de publicidade
Quaisquer dados do conteúdo reproduzido na sua TV
🔐
Segurança
A comunicação entre o aplicativo e sua TV utiliza criptografia TLS, seguindo o protocolo de pareamento do controle remoto do Google TV/Android TV. Os certificados são gerados localmente e armazenados apenas no seu dispositivo.

👶
Privacidade das crianças
Este aplicativo não coleta intencionalmente informações de crianças menores de 13 anos. O aplicativo não contém publicidade, contas ou coleta de dados de qualquer tipo.

🔄
Alterações a esta política
Caso esta política de privacidade seja alterada, a versão atualizada será publicada neste URL com uma nova data de "Última atualização". O uso contínuo do aplicativo após as alterações constitui aceitação da nova política.

✉️
Contato
Se você tiver alguma dúvida sobre esta política de privacidade ou sobre o aplicativo, entre em contato conosco através dos seguintes canais:

📧 support@tvremote.io

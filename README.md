#Acessarvpspeloandroid

Modo para acessar a vps pelo termux no Android 

O que é isso?
Este é um script que permite instalar o Ubuntu em seu aplicativo termux sem um dispositivo rooteado

Atualizações
• Atualizado para Ubuntu 22.04

Etapas de instalação
Atualizar termux: 
apt-get update && apt-get upgrade -y

Instale o wget: 
apt-get install wget -y

Instale o proot: 
apt-get install proot -y

Instale o git: 
apt-get install git -y

Vá para a pasta HOME: cd ~

Baixe o script: 
git clone https://github.com/zxwellzika/Acessarvpspeloandroid.git

Vá para a pasta de scripts: cd acessarvpspeloandroid
Dê permissão de Deus execução: chmod +x ubuntu.sh
Execute o script: ./ubuntu.sh -y
Agora é só iniciar o Ubuntu: ./startubuntu.sh
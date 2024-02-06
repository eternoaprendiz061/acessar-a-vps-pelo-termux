#Acessarvpspeloandroid

Modo para acessar a vps pelo termux no Android 

O que é isso?
Este é um script que permite instalar o Ubuntu em seu aplicativo termux sem um dispositivo rooteado

Atualizações
• Atualizado para Ubuntu 22.04

Etapas de instalação
Atualizar termux: 
apt-get update && apt-get upgrade -y

instale o tsu:
Pkg install tsu

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

Dê permissão de execução: 
chmod +x ubuntu.sh

Execute o script: 
./ubuntu.sh -y

Agora é só iniciar o Ubuntu: ./startubuntu.sh

continue com:
apt update

instale o ssh:
apt install ssh

inicie o ssh:
service ssh start

agora acesse sua vps com:
Ssh root@ipdavps -porta 

substitua o "ipdavps" depois do @, pelo ip da sua vps, depois dê um espaço e coloque - e a porta, normalmente a porta é 22 então fica o exemplo: Ssh root@123.456.789 -22
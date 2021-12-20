- Packages used

    `$ npm i express cors express-fileupload tesseract.js`

    Servidor de Backend na AWS

Servidor de Backend na AWS

Criar servidor na AWS
Associar ao security group
Associar ao Key par

https://www.youtube.com/watch?v=u-o7cqzK6u8

Servidor de Backend na AWS

Criar servidor na AWS
Associar ao security group
Associar ao Key par

Atualizar 
sudo apt-get update
sudo apt-get upgrade

Instalar o Node.js
Site do Node
Downloads
Packages
Ubuntu
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
node -v
npm -v

Instalar Git
sudo apt install git

Clonar repositorio
git clone https://github.com/Alezeveall/reciboocr-backend.git reciboocr-backend

Entrar no diretorio e instalar pacotes
\reciboocr-backend\npm install

Instalar o pm2
sudo npm install pm2 -g

Executar a aplicaçao
pm2 start app.js --name dev (na pasta do aplicativo)

Checar o que está rodando
pm2 list
pm2 stop

Após atualizar rodar o git pull no servidor
git pull origin master
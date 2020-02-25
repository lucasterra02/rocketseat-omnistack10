# rocketseat-omnistack10
Projeto Dev Radar, ministrado pela semana OmniStack 10 da Rocketseat

## Configurar seu MongoDB:

### 1 - Criar uma conta no mongodb atlas (https://www.mongodb.com/cloud/atlas)
### 2 - Criar um cluster
### 3 - Criar o database selecionar Node.js - Version 3.0 or later

Colocar sua String de conexão (mongoose.connect) no arquivo: /backend/src/index.js

na String de conexão colocar sua senha e escolher um nome para o seu database, exemplo:

mongodb+srv://lucasterra:senha_do_banco@cluster0-qysus.mongodb.net/nome_do_banco_que_vc_deseja?retryWrites=true&w=majority

## Iniciar aplicações:

start backend = yarn dev
start front web = yarn start
start front mobile = yarn start

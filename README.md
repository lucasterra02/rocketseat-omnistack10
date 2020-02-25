# rocketseat-omnistack10
Projeto Dev Radar, ministrado pela semana OmniStack 10 da Rocketseat

Configurar seu banco de dados na:

Criar uma conta no mongodb atlas (https://www.mongodb.com/cloud/atlas)
Criar um cluster
Criar o database selecionar Node.js - Version 3.0 or later

Colocar sua String de conexão no arquivo: /backend/src/index.js

em
mongoose.connect

na String de conexão colocar sua senha e escolher um nome para o database, exemplo:

mongodb+srv://lucasterra:senha_do_banco@cluster0-qysus.mongodb.net/nome_do_banco_que_vc_deseja?retryWrites=true&w=majority

start backend = yarn dev
start web front = yarn start
start mobile app = yarn start

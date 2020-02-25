# rocketseat-omnistack10
Projeto Dev Radar, ministrado pela semana OmniStack 10 da Rocketseat

## Configurar seu MongoDB:

#### 1 - Criar uma conta no mongodb atlas (https://www.mongodb.com/cloud/atlas)
#### 2 - Criar um cluster (sempre mantendo as opções Default)
#### 3 -  Ir em Database Access e criar um usuário/senha para acessar o banco
#### 3.1 - definir User Privileges como 'Read and Write'
#### 4 - Ir em Network Access > ADD IP ADRESS > ALLOW ACCESS FROM ANYWHERE > Confirm
#### 4.1 - (Esta opção irá liberar os acessos de qualquer origem no seu banco de dados)
#### 5 - Após o CLUSTER e USUÁRIO finalizarem a criação (isto pode demorar) ir em: Cluster > CONNECT > Connect Your Application > Driver escolher Node.js > Version 3.0 or later
#### 4.1 - Copiar String de conexão 
#### 4.2 - Colar sua String de conexão (mongoose.connect) no arquivo: /backend/src/index.js

#### 4.3 - Na String de conexão colocar sua senha e escolher um nome para o seu database, exemplo:
mongodb+srv://lucasterra:SENHA_DO_BANCO@cluster0-qysus.mongodb.net/NOME_DO_BANCO_QUE_VC_DESEJA?retryWrites=true&w=majority

## Iniciar aplicações:

#### start backend = yarn dev
#### start front web = yarn start
#### start front mobile = yarn start

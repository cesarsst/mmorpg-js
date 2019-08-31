
# mmorpg-js
Jogo criado com NodeJS+express+Phaser  no estilo MMORPG


# Pré-requisitos
- NodeJs 

## Primeira vez?
    npm install
    
## Configuração adicional:
### No arquivo app.js faça a mudança para seu banco de dados (MongoDb é usado nesse caso online) 
    mongoose.connect('<Sua String de conexão>', {
    useNewUrlParser: true
});

## Execute o app.js com:
    node app.js

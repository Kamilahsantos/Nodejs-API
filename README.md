# Nodejs-API

API desenvolvida com Nodejs durante o curso  (Nodejs da RocketSeat)[https://rocketseat.com.br/starter/curso-gratuito-nodejs]

## Pacotes utilizados
 - express;
 - mongoose;
 - mongoose-paginate;
 - require-dir;
 - cors

## Para executar a API:

### Instalar as dependências:
 ```
 npm i
 ```
 ### Iniciar a aplicação
 ```
 npm run dev
 ```

 ### Para conectar com o mongodb utilizando o dockers(banco utilizado na aplicação):

baixar a imagem do mongodb:
 ```
 docker pull mongo
 ```

rodar o container do mongodb
 ```
 docker run --name mongodb -p 27017:27017 -d mongo
 ```

verificar os processo em execucao
```
docker ps
```

#Execução
..
Dentro da pasta de "backend" deve ser dado o comando:
npm install
npm start

Dentro da pasta de "frontend" deve ser dado o comando:
npm install
npm start

Depois será necessário dentro da pasta "backend" dar o comando:
docker compose up
..
apos a realização desses comandos, você poderá entrar no navegador:
http://localhost:3000/


A tela inicial será necessário colocar o login e senha, para isso é importante realizar 
a requisição para cadastrar o usuario, tanto usario comum como adm.

Para isso faça requisição como exemplo abaixo via post:
http://localhost:3333/v1/usuario

{
  "nome": "Bruno Ramos",
  "email": "adm_bruno@gmail.com",
  "tipoUsuarioId": "7edd25c6-c89e-4c06-ae50-c3c32d71b8ad",
  "senha": "123456"
}

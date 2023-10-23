# Angular 14
Um exemplo de Login simples.

## Requisitos
 - Angular (v14+)
 - API ( https://github.com/prdossantos/node-express-api )

## Instalação

 1. Clone o Repositório:
 ```bash
    git clone https://github.com/prdossantos/angular-14.git
    cd angular-14
 ```
 2. Instale as Dependências:
 ```bash
    npm install
 ```
 3. Caso tenha alterado a porta de funcionamento da api, deve alterar a ```.src/environments/environment.ts```, com a mesma.

 4. Inicialize a API, Verifique se API está rodando e inicie o serviço.

## Uso
 1. Inicie o Servidor:
 ```bash
    npm run start
 ```
 A API agora estará rodando em http://localhost:4200
 
 Utilize os seguintes dados de acesso para efetuar login: 
 ```json
  "email": "root@api.com",
  "password": "password"
 ```

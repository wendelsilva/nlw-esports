![imagem de capa](https://github.com/wendelsilva/nlw-esports/blob/main/capa-nlw-esports.png?raw=true)
# nlw-esports

Evento da rocketseat onde durante 1 semana desenvolvemos uma aplicação fullstack web e mobile onde você consegue encontrar jogadores que jogam os mesmos jogos que você atráves de anúncios que você publica ou busca na plataforma.

## Tecnologias Utilizadas
### FrontEnd
- [ ] Reactjs
- [ ] TailwindCSS
- [ ] React Native
### Backend
- [ ] Nodejs
- [ ] Expresjs
- [ ] PrismaORM
- [ ] Sqlite

## BackEnd
Para executar o backend entre na pasta server e execute os seguintes comandos

Instalar dependências
```
npm install
```
Dentro da pasta server crie um arquivo .env e cole o seguinte comando
```
DATABASE_URL="file:./dev.db"
```
Rodar Migrations
```
npx prisma migrate dev
```
Executar BackEnd
```
npm run dev
```
Caso queira acessar o backend o prisma disponibiliza um cliente web para editar o banco de dados, para isso execute
```
npx prisma studio
```
## FrontEnd
Para executar o frontend execute os seguintes comandos

Instalar dependências
```
npm install
```
Executar FrontEnd
```
npm run dev
```

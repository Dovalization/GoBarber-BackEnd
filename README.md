<h1 align="center">
  <img src="https://ik.imagekit.io/qtk8amezw72/logo_ec1JWPdcp.svg">
</h1>

## 📋 Sobre

API REST desenvolvida para a aplicação GoBarber durante a bootcamp GoStack da Rocketseat.


---

## 🧰 Tecnologias utilizadas
O projeto foi desenvolvido utilizando as seguintes tecnologias:

- [NodeJS](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [TypeORM](https://typeorm.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)
- [Redis](https://redis.io/)

---

## 📁 Como baixar o projeto

### Pre Requisitos:
Certifique de ter os seguintes bancos rodando na sua máquina para rodar a API, podendo serem rodadas através de container docker.
Para mais informações, consultar o arquivo *ormconfig.example.json*

Incluso no repositório estão as configurações de workspace do [Insomnia](https://insomnia.rest/) caso queira testar o funcionamento das rotas.
  - PostgreSQL
  - MongoDB
  - Redis

```bash
  # Clonar repositório git
  $ git clone https://github.com/Dovalization/GoBarber-BackEnd.git

  # Entrar na pasta do projeto
  $ cd GoBarber-BackEnd

  # Instalar dependências
  $ yarn install

  # Rodar migrations do banco PostgreSQL
  $ yarn typeorm migration:run

  # Iniciar API
  $ yarn dev:server
```


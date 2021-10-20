<h1 align="center">Backend da Aplicação em Nodejs / By Alex, Rocketseat</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## 🚀 Como executar

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub

- Clone o repositório e acesse a pasta;
- Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub;
- As credenciais são GITHUB_CLIENT_SECRET e GITHUB_CLIENT_ID, além de uma variavel JWT_SECRET aleatória;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Inicie o servidor com `yarn dev`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

- [Repositorio](https://github.com/alexRicc2/nlw-front) da aplicação web front-end;

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Pqp deu trabalho isso 10/20/2021

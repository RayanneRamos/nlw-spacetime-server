<h1 align="center"> NLW Spacetime - Server </h1>

<p align="center">
  <img alt="nlw-spacetime-server" src="https://github.com/RayanneRamos/nlw-spacetime-server/assets/43352880/cdf93e73-cf3e-4a90-bc6d-4c4971209b43" width="100%">
</p>

<p  align='center'>
  <img src='https://img.shields.io/badge/license-MIT-%23835afd' alt='License' />
  <img src='https://img.shields.io/badge/forks-MIT-%23835afd' alt='Forks' />
  <img src='https://img.shields.io/badge/stars-MIT-%23835afd' alt='Stars' />
</p>

<br>

## 💻 Projeto

[NLWSpacetime] É um projeto desenvolvido durante a [Next Level Week](https://nextlevelweek.com/) apresentado pela [Rocketseat](https://www.rocketseat.com.br/) nos dias 16 de Janeiro a 20 de Janeiro de 2023. O projeto consiste numa interface web e mobile para a criação e visualização de memórias parecido com o conceito de cápsula do tempo onde o usuário pode gravar todo dia uma memória e depois de um tempo ver a sua evolução.

- [x] NLW Spacetime - Abertura
- [x] Aula 01 | Iniciando o projeto de ponta a ponta
- [x] Aula 02 | Avançando o back end e Front end
- [x] Aula 03 | Integrando UI com bibliotecas
- [x] Aula 04 | Integrando os projetos web e mobile
- [x] Aula 05 | O próximo nível
- [x] NLW Spacetime - Encontro ao vivo

## 🧪 Technologies

Esse projeto foi desenvolvido com as seguintes tecnolgias:

- [Typescript](https://www.typescriptlang.org/)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [axios](https://axios-http.com/ptbr/docs/intro)
- [Zod](https://www.npmjs.com/package/zod)

## 🚀 Instalação

```bash
  # Clone o repositório e entre na pasta do projeto
  $ git clone https://github.com/RayanneRamos/nlw-spacetime-server.git
  $ cd server
  # Instale as dependências
  $ npm install
  # ou
  $ yarn install
  # Execute a aplicação
  $ npm run dev
  # ou
  $ yarn start
```

## 🧩 Rotas do Server

Aqui você encontra todas as rotas disponíveis na aplicação.

- `POST http://localhost:3333/register` - Cria um novo usuário
- `POST http://localhost:3333/upload` - Sobe os arquivos para o site
- `POST http://localhost:3333/memories` - Cria uma nova memória
- `PUT http://localhost:3333/memories/:id`- Serve para editar uma memória
- `GET http://localhost:3333/memories` - Lista as memórias
- `GET http://localhost:3333/memories/:id` - Entra em uma memória específica
- `DELETE http://localhost:3333/memories/:id` - Deleta uma memória

## 📝 License

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para obter mais detalhes.

---

<p align='center'>Criado by Rayanne Ramos</p>

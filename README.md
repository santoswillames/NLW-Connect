<img src="./img/logo.svg"/>

# NLW Connect Rocketseat 🚀

Esse é um projeto do evento **NLW Connect**, um site responsivo de inscrição e indicação para eventos, além de acompanhar o **ranking** dos participantes com maior número de indicações.

Após clonar o repositório siga os comandos:
Navegue até a pasta do repositório

```bash
cd NLW-Connect
```

Crie os containers do Postgres e Redis (Precisa do coker e docker compose instalado)

```bash
docker compose up -d
```

Adicione as variáveis de ambiente

```bash
cp .env.example .env
```

Crie as migrations do banco de dados

```bash
npm run db:migrate
npm run db:generate
```

Instalação das dependências

```bash
npm install
```

Execute o servidor e acesse a documentação em <a href="http://localhost:3333/docs">DOCS</a>

```bash
npm run dev
```

## Tecnologias Utilizadas

- Node.js
- Fastify
- TypeScript
- Zod
- Drizzle ORM
- Redis
- Postgresql
- Swagger
- Docker

 <img src="./img/image-evento.png"/>

# NLW Agents

Este projeto é o **NLW Agents**, desenvolvido durante um evento da Rocketseat.

## Tecnologias e Bibliotecas Utilizadas
- [Fastify](https://www.fastify.io/): Framework web para Node.js, focado em performance.
- [@fastify/cors](https://github.com/fastify/fastify-cors): Middleware para habilitar CORS.
- [fastify-type-provider-zod](https://github.com/fastify/fastify-type-provider-zod): Integração do Zod para validação e tipagem de schemas no Fastify.
- [Zod](https://zod.dev/): Biblioteca de validação de schemas TypeScript.
- [Drizzle ORM](https://orm.drizzle.team/): ORM para TypeScript/Node.js.
- Docker: Utilizado para orquestração de containers e ambiente de banco de dados.

## Padrões de Projeto
- **Modularização de rotas**: As rotas HTTP ficam organizadas em arquivos separados dentro de `src/http/routes`.
- **Validação de dados**: Utiliza Zod para validação e tipagem de dados nas rotas.
- **Separação de configuração**: Variáveis de ambiente e configuração do banco ficam em arquivos próprios (`env.ts`, `db/connection.ts`).

## Setup e Configuração

1. **Clone o repositório:**
   ```sh
   git clone <url-do-repo>
   cd agents/server
   ```

2. **Instale as dependências:**
   ```sh
   npm install
   ```

3. **Configure as variáveis de ambiente:**
   - Renomeie `.env.example` para `.env` e ajuste conforme necessário.

4. **Suba o banco de dados com Docker:**
   ```sh
   docker-compose up -d
   ```

5. **Execute as migrations e seeds (se necessário):**
   ```sh
   npm run db:migrate
   npm run db:seed
   ```

6. **Inicie o servidor:**
   ```sh
   npm run dev
   ```

O servidor estará disponível em `http://localhost:3333` (ou porta definida em `.env`).

---

Projeto desenvolvido durante o evento NLW da Rocketseat.

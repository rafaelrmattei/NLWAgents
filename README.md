# Agents - NLW Rocketseat

Projeto desenvolvido durante a Next Level Week (NLW) da [Rocketseat](https://www.rocketseat.com.br/). O "Agents" é uma aplicação fullstack composta por um backend em Node.js (Fastify) e um frontend em React (Vite), permitindo a criação e gerenciamento de salas e perguntas em tempo real.

## ✨ Tecnologias Utilizadas


### Backend (server)
- Node.js
- Fastify
- Drizzle ORM
- SQLite
- TypeScript
- Docker (opcional)
- Gemini AI (Google) — integração de IA para processamento de linguagem natural

### Frontend (web)
- React
- Vite
- TypeScript
- dayjs

## 🚀 Requisitos
- [Node.js](https://nodejs.org/) >= 18.x
- [npm](https://www.npmjs.com/) >= 9.x
- [Docker](https://www.docker.com/) (opcional, para banco de dados ou ambiente isolado)

## 📦 Instalação e Execução

### 1. Clone o repositório
```bash
git clone https://github.com/rafaelrmattei/nlw-agents
cd NLW
```

### 2. Instale as dependências
```bash
npm install
```

### 3. Configuração do Backend (server)
```bash
cd server
# Configure variáveis de ambiente se necessário (exemplo: .env)
# Execute as migrations e seeds, se necessário
npm run dev
```

- O backend estará disponível em: `http://localhost:3333`

### 4. Configuração do Frontend (web)
Abra um novo terminal:
```bash
cd web
npm run dev
```
- O frontend estará disponível em: `http://localhost:5173`

## 📁 Estrutura Sugerida
```
NLW/
  server/   # Backend (Fastify, Node.js)
  web/      # Frontend (React, Vite)
```

## 📝 Comandos Úteis

### Backend
- `npm run dev` — inicia o servidor em modo desenvolvimento
- `npm run build` — gera build de produção
- `npm run start` — inicia o servidor em produção
- `npm run db:generate` — gera as entidades/migrations do banco de dados (Drizzle)
- `npm run db:migrate` — executa as migrations do banco de dados (Drizzle)
- `npm run db:seed` — executa o seed do banco de dados

### Frontend
- `npm run dev` — inicia o frontend em modo desenvolvimento
- `npm run build` — gera build de produção
- `npm run preview` — visualiza build de produção localmente

---

Projeto criado durante a [NLW da Rocketseat](https://www.rocketseat.com.br/).

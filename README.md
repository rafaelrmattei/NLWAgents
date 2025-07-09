# Agents - NLW Rocketseat

Projeto desenvolvido durante a vigésima edição da Next Level Week (NLW) da Rocketseat.
"Agents" é uma aplicação fullstack composta por um backend em Node.js com Fastify e um frontend em React com Vite.

A aplicação permite a criação de salas, onde os participantes podem enviar áudios que são automaticamente transcritos. Esses trechos transcritos formam o contexto da conversa, que é utilizado pela IA Gemini, da Google, para responder perguntas enviadas por texto de forma inteligente e contextualizada.

## ✨ Tecnologias Utilizadas


### Backend (server)
- Gemini AI (Google)
- Node.js
- Fastify
- Drizzle
- TypeScript
- Docker
- Postgres

### Frontend (web)
- React
- Vite
- TypeScript
- Shadcn

## 🚀 Requisitos
- [Node.js](https://nodejs.org/) >= 18.x
- [npm](https://www.npmjs.com/) >= 9.x
- [Docker](https://www.docker.com/)

## 📝 Comandos Úteis

### Backend
- `npm run dev` — inicia o servidor em modo desenvolvimento
- `npm run start` — inicia o servidor em produção
- `npm run db:generate` — gera as entidades/migrations do banco de dados (Drizzle)
- `npm run db:migrate` — executa as migrations do banco de dados (Drizzle)
- `npm run db:seed` — executa o seed do banco de dados

### Frontend
- `npm run dev` — inicia o frontend em modo desenvolvimento
- `npm run build` — gera build de produção
- `npm run preview` — visualiza build de produção localmente

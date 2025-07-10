# Agents – NLW Rocketseat

Project developed during the 20th edition of **Next Level Week (NLW)** by Rocketseat.  
**"Agents"** is a fullstack application composed of a backend built with **Node.js** and **Fastify**, and a frontend using **React** and **Vite**.

The app allows the creation of rooms where participants can send **voice messages**, which are automatically transcribed. These transcriptions form the **context of the conversation**, which is then used by **Google's Gemini AI** to generate intelligent and contextual responses to text-based questions.

---

## ✨ Technologies Used

### 🔧 Backend (`/server`)
- Gemini AI (Google)
- Node.js
- Fastify
- Drizzle ORM
- TypeScript
- Docker
- PostgreSQL

### 💻 Frontend (`/web`)
- React
- Vite
- TypeScript
- Shadcn UI

---

## 🚀 Requirements

- [Node.js](https://nodejs.org/) >= 18.x  
- [npm](https://www.npmjs.com/) >= 9.x  
- [Docker](https://www.docker.com/)

---

## 📝 Useful Commands

### 📦 Backend

```bash
npm run dev        # Start the development server
npm run start      # Start the production server
npm run db:generate # Generate entities/migrations (Drizzle)
npm run db:migrate # Run database migrations (Drizzle)
npm run db:seed    # Seed the database

### 💻 Frontend

npm run dev        # Start the frontend in development mode
npm run build      # Build the frontend for production
npm run preview    # Preview the production build locally

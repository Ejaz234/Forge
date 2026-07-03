# 🚀 Forge — AI-Powered App Builder

Turn your ideas into fully functional React applications using AI.

Forge is a modern full-stack AI application builder that transforms natural language prompts into production-ready React applications. It features live preview, editable code, AI-powered iterations, image uploads, authentication, project history, and one-click downloads.

## ✨ Features

- 🤖 AI-powered React app generation
- ⚡ Live preview with Sandpack
- 💬 Persistent AI chat history
- 🖼 Image upload support
- 🛠 AI Improve using Cline SDK
- 🔐 Clerk Authentication
- 💳 Credit & subscription system
- 📦 Export project as ZIP

## 🛠 Tech Stack

| Framework | Next.js 15 |
|------------|------------|
| Language | TypeScript |
| AI Model | Google Gemini 3.5 Flash |
| Authentication | Clerk |
| Database | Supabase PostgreSQL |
| ORM | Prisma |
| Styling | Tailwind CSS + Shadcn UI |
| Rate Limiting | Arcjet |


## 🚀 Getting Started

```
npm install
npx prisma generate
npx prisma db push
npm run dev
```

## 🔑 Environment Variables

```
.env.local
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
GEMINI_API_KEY=
ARCJET_KEY=
```

## 🌍 Live Demo

https://forge-xmll.vercel.app/

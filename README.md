# 🚀 BuildAI

AI-powered React application generator inspired by Bolt.new and Lovable.

Users describe an app in natural language, and BuildAI generates a production-ready React project with a live preview, editable code, AI improvements, image support, and project history.

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
| AI | Gemini 3.5 Flash |
| Auth | Clerk |
| Database | Supabase |
| ORM | Prisma |
| Styling | Tailwind CSS + Shadcn UI |


## 🚀 Getting Started

npm install

npx prisma generate

npx prisma db push

npm run dev

## 🔑 Environment Variables

.env.local

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=

DATABASE_URL=

GEMINI_API_KEY=

ARCJET_KEY=

## 🌍 Live Demo

https://forge-xmll.vercel.app/

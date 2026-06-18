# 🤖 AI SaaS Starter Kit

> Production-ready boilerplate for building and launching AI-powered SaaS products — fast.

![React](https://img.shields.io/badge/React-18-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-06B6D4?style=flat-square&logo=tailwindcss)
![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=flat-square&logo=supabase)
![Claude API](https://img.shields.io/badge/Claude-API-AA3BFF?style=flat-square)

---

## 🚀 What is this?

**AI SaaS Starter Kit** is a complete, production ready codebase that helps developers skip weeks of boring setup and ship their AI powered product fast.

Instead of spending 3–4 weeks wiring up authentication, databases, billing, and AI integrations buy this kit, swap in your idea, and launch in a weekend.

---

## ✨ Features

- 🔐 **Authentication** - Login, signup, password reset powered by Supabase
- 🤖 **AI Chatbot** - Real-time streaming chat UI powered by Claude API
- 🖼️ **AI Image Analyser** - Drag & drop image analysis with Claude Vision
- 💳 **Credit System** - Per user AI usage limits out of the box
- ⚙️ **System Prompt Config** - Change AI behaviour without touching code
- 🌙 **Dark / Light Mode** - Fully supported across all components
- 📱 **Fully Responsive** - Works perfectly on mobile and desktop
- 🗄️ **PostgreSQL Database** - Via Supabase with RLS security policies
- 💰 **Optional Stripe Billing** - Pre-documented, easy to enable
- 🎨 **Beautiful UI** - Built with shadcn/ui + Tailwind CSS

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18 + Vite + TypeScript |
| Styling | Tailwind CSS + shadcn/ui |
| Database | PostgreSQL via Supabase |
| Auth | Supabase Auth |
| AI | Anthropic Claude API |
| Icons | Lucide React |
| Routing | React Router DOM |
| Billing (optional) | Stripe |

---

## 📁 Project Structure

```
ai-saas-kit/
├── src/
│   ├── components/
│   │   ├── ui/          # shadcn/ui components
│   │   ├── chat/        # AI Chatbot UI
│   │   ├── image/       # AI Image Analyser UI
│   │   └── layout/      # Navbar, sidebar, page wrapper
│   ├── pages/
│   │   ├── Landing.tsx
│   │   ├── Login.tsx
│   │   ├── Dashboard.tsx
│   │   ├── ChatDemo.tsx
│   │   ├── ImageDemo.tsx
│   │   └── Settings.tsx
│   ├── lib/
│   │   ├── supabase.ts  # Supabase client
│   │   ├── claude.ts    # Claude API wrapper
│   │   └── credits.ts   # Usage limiter
│   ├── hooks/
│   │   ├── useAuth.ts
│   │   ├── useCredits.ts
│   │   └── useStream.ts
│   └── types/
├── supabase/
│   └── schema.sql       # Run once in Supabase SQL Editor
├── .env.example
├── README.md
└── CUSTOMIZE.md
```

---

## ⚡ Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/Kethmika2004/ai-saas-kit.git
cd ai-saas-kit
npm install
```

### 2. Set up environment variables

```bash
cp .env.example .env
```

Fill in your keys:

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_CLAUDE_API_KEY=your_anthropic_api_key
```

### 3. Set up the database

- Go to your Supabase dashboard → SQL Editor
- Paste and run `supabase/schema.sql`
- All tables, triggers, and policies are created automatically

### 4. Run locally

```bash
npm run dev
```

Visit `http://localhost:5173` — you're live.

---

## 🎯 Who is this for?

- Developers who want to ship an AI product without weeks of setup
- Indie hackers building and selling AI tools
- Freelancers who need a solid base for client projects
- Students learning how to build full-stack AI applications

---

## 📄 License

This project is available for purchase on [Gumroad](https://gumroad.com/yasandu). Each purchase grants a single-project license. Redistribution or resale of the source code is not permitted.

---

## 👨‍💻 Built by

**Yasandu Kethmika** : Computer Science & Engineering undergraduate at the University of Moratuwa, Sri Lanka.

Building production ready AI templates so you can focus on your idea, not the boilerplate.

---

⭐ If this helped you, consider leaving a star!

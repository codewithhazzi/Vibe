# 🚀 Vibe

<div align="center">

**AI-powered development platform that lets you create web applications by chatting with AI agents in real-time sandboxes.**

[![Next.js](https://img.shields.io/badge/Next.js-15.3.4-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

</div>

## ✨ Features

<table>
<tr>
<td width="50%">

- 🤖 **AI Code Generation** - GPT-4 powered agents
- 💻 **Real-time Development** - E2B sandboxes
- 🔄 **Live Preview** - Split-pane interface
- 📁 **File Explorer** - Syntax highlighting
- 💬 **Conversational** - Message history

</td>
<td width="50%">

- 🎯 **Usage Tracking** - Smart rate limiting
- 💳 **Subscriptions** - Pro features
- 🔐 **Authentication** - Clerk integration
- 📱 **Responsive** - Mobile friendly
- ⚙️ **Background Jobs** - Inngest processing

</td>
</tr>
</table>

## 🛠️ Tech Stack

<div align="center">

**Frontend**
[![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

**Backend**
[![tRPC](https://img.shields.io/badge/tRPC-11-2596BE?logo=trpc&logoColor=white)](https://trpc.io/)
[![Prisma](https://img.shields.io/badge/Prisma-6-2D3748?logo=prisma&logoColor=white)](https://prisma.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791?logo=postgresql&logoColor=white)](https://postgresql.org/)

**AI & Services**
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4-412991?logo=openai&logoColor=white)](https://openai.com/)
[![E2B](https://img.shields.io/badge/E2B-Sandbox-FF6B6B?logo=e2b&logoColor=white)](https://e2b.dev/)
[![Clerk](https://img.shields.io/badge/Clerk-Auth-7C3AED?logo=clerk&logoColor=white)](https://clerk.com/)
[![Inngest](https://img.shields.io/badge/Inngest-Jobs-00D4AA?logo=inngest&logoColor=white)](https://inngest.com/)

</div>

## 🚀 Quick Start

```bash
# 1. Clone repository
git clone <your-repo-url>
cd nextjs-vibe-main

# 2. Install dependencies
npm install

# 3. Setup environment
cp .env.example .env.local
# Fill in your API keys

# 4. Setup database
npx prisma migrate dev

# 5. Start development
npm run dev
```

## 🔧 Environment Variables

```bash
# Database
DATABASE_URL="postgresql://..."

# Authentication (Clerk)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="pk_..."
CLERK_SECRET_KEY="sk_..."

# AI (OpenAI)
OPENAI_API_KEY="sk-..."

# Sandbox (E2B)
E2B_API_KEY="e2b_..."

# Background Jobs (Inngest) - Production only
INNGEST_EVENT_KEY="your-inngest-event-key"
INNGEST_SIGNING_KEY="your-inngest-signing-key"
```

## 📁 Project Structure

```
src/
├── app/                 # Next.js app router
├── components/          # Reusable UI components
├── modules/             # Feature modules
│   ├── home/           # Landing page
│   ├── projects/       # Project management
│   └── messages/       # Chat system
├── inngest/            # Background jobs
├── lib/                # Utilities
└── trpc/               # API layer
```

## 🎯 How It Works

```mermaid
graph LR
    A[User Prompt] --> B[tRPC API]
    B --> C[Database]
    B --> D[Inngest Event]
    D --> E[AI Agent]
    E --> F[E2B Sandbox]
    F --> G[Code Generation]
    G --> H[Live Preview]
    H --> I[File Explorer]
```

## 📋 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint |
| `npx prisma studio` | Open database studio |
| `npx prisma migrate dev` | Run database migrations |

## 🌟 Features in Detail

### 🤖 AI-Powered Development
- **GPT-4 Integration** - Advanced AI code generation
- **Real-time Processing** - Instant feedback and updates
- **Context Awareness** - Remembers conversation history

### 💻 Sandbox Environment
- **E2B Integration** - Isolated development environments
- **Live Preview** - Real-time application preview
- **File Management** - Complete file system access

### 🎨 Modern UI/UX
- **Shadcn/ui** - Beautiful, accessible components
- **Dark Mode** - Full theme support
- **Responsive** - Mobile-first design
- **Animations** - Smooth interactions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<div align="center">

**Built with ❤️ by [Hanzla Masood](https://github.com/codewithhazzi)**

[![GitHub stars](https://img.shields.io/github/stars/codewithhazzi/Vibe?style=social)](https://github.com/codewithhazzi/Vibe)
[![GitHub forks](https://img.shields.io/github/forks/codewithhazzi/Vibe?style=social)](https://github.com/codewithhazzi/Vibe)

</div>
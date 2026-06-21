# AI Finance Platform 💰

A full-stack finance management platform built with Next.js, Prisma, Neon, Clerk, and Inngest.

## 🚀 Tech Stack

- **Frontend:** Next.js 15, React 19, Tailwind CSS, Shadcn/ui
- **Backend:** Next.js API Routes, Prisma ORM
- **Database:** Neon (PostgreSQL)
- **Authentication:** Clerk
- **Background Jobs:** Inngest
- **AI:** Gemini API (Receipt Scanning & Insights)
- **Email:** Resend
- **Security:** Arcjet

## 📦 Features

- 🔐 Authentication with Clerk
- 💳 Account Management
- 📊 Transaction Tracking
- 🤖 AI-Powered Receipt Scanning
- 📈 Monthly AI Reports
- 🔄 Recurring Transactions
- 📧 Email Reports

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local

# Run database migrations
npx prisma db push

# Start the development server
npm run dev

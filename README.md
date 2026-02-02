 🛠️ PartsFindr - Concierge Parts Sourcing Platform
📋 Project Overview
PartsFindr is a service-based ecommerce platform that connects customers who need replacement parts with experts who can find and order those parts. Customers submit requests for parts they can't locate themselves, our team researches and sources the parts online, and customers pay via local money transfer.

Core Concept: "You describe what's broken, we find the exact part you need."

✨ Key Features
For Customers
📝 Smart Request Form - Submit part requests with descriptions and photos

📊 Dashboard - Track all your requests and quotes in one place

💰 Local Payment Options - Pay via bank transfer, mobile money, or other local methods

📦 Order Tracking - Follow your order from quote to delivery

🔗 Public Tracking - Shareable links for order status (no login required)

For Admin Team
🎯 Request Queue - View and manage incoming part requests

🔍 Online Research Tools - Integrated tools for sourcing parts across the web

💵 Quote Generator - Create professional quotes with automatic fee calculation

📈 Order Management - Update order status, tracking numbers, and delivery updates

👥 Customer Management - View customer history and preferences

🏗️ Technical Stack
Frontend
Framework: Next.js 14 (App Router)

Language: TypeScript

Styling: Tailwind CSS

Form Handling: React Hook Form + Zod validation

State Management: React Context + TanStack Query

Backend
Framework: NestJS

Language: TypeScript

Database: PostgreSQL with Prisma ORM

Authentication: NextAuth.js (customers) + JWT (admin)

Email: Resend with React Email templates

Infrastructure
Frontend Hosting: Vercel

Backend Hosting: Railway/Render

Database: PostgreSQL (Railway/Supabase)

File Storage: Uploadthing or AWS S3

Monitoring: Sentry (error tracking)

🚀 Quick Start
Prerequisites
Node.js 18+ and npm/yarn/pnpm

PostgreSQL database

Git

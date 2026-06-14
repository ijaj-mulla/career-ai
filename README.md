# 🚀 AI Career Coach

An all-in-one, AI-powered career development platform. This application provides users with an intelligent resume builder, tailored cover letter generation, interview preparation tools, and real-time industry insights.

## ✨ Features

* 🔐 Secure Authentication with Clerk
* 📄 AI Resume Builder
* 📝 AI Cover Letter Generator
* 🤖 AI Interview Preparation
* 📊 Personalized Career Dashboard
* 📥 Resume PDF Download

---

## 📦 Installation

### Clone Repository

```bash
git clone https://github.com/ijaj-mulla/career-ai.git
cd career-ai
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the project root:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

DATABASE_URL=

GEMINI_API_KEY=

INNGEST_EVENT_KEY=
```

### Setup Database

```bash
npx prisma generate
npx prisma db push
```

### Run Development Server

```bash
npm run dev
```
---

## 🏗️ Production Build

```bash
npm run build
npm start
```

---

## 📂 Project Structure

```bash
├── app
├── actions
├── components
├── data
├── hooks
├── lib
├── prisma
├── public
├── .env
├── package.json
└── README.md
```

---

## 🌍 Deployment

### Vercel Deployment

1. Push project to GitHub
2. Import repository into Vercel
3. Add all environment variables
4. Deploy

---

## ⭐ Show Your Support

If you found this project useful, please give it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the MIT License.

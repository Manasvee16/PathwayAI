# PathwayAI

PathwayAI is an intelligent, full-stack web application that empowers users to advance their careers with AI-powered tools. It provides personalized career guidance, resume and cover letter generation, interview preparation, and real-time industry insights—all tailored to your background and goals.

---

## 🚀 Features

- **AI-Powered Career Guidance:** Get personalized advice and insights powered by advanced AI technology.
- **Smart Resume Creation:** Generate ATS-optimized resumes with AI assistance and track your ATS score.
- **Cover Letter Generator:** Create compelling, tailored cover letters for any job.
- **Interview Preparation:** Practice with role-specific, AI-generated questions and get instant feedback.
- **Industry Insights:** Access real-time trends, salary data, and market analysis for 50+ industries.
- **Progress Tracking:** Monitor your interview performance and receive improvement tips.
- **Secure & Private:** All data is encrypted and securely stored. Authentication is handled by Clerk.

---

## 🛠️ Tech Stack

- **Framework:** Next.js 15 (App Router, Server Components)
- **Styling:** Tailwind CSS, shadcn/ui
- **Database:** PostgreSQL (via Prisma ORM)
- **Authentication:** Clerk
- **AI:** Google Generative AI
- **Charts & UI:** Recharts, Lucide Icons
- **Other:** React Hook Form, Zod, html2pdf.js

---

## ⚙️ How It Works

1. **Onboarding:** Share your industry and experience for personalized guidance.
2. **Document Creation:** Build ATS-optimized resumes and cover letters with AI.
3. **Interview Prep:** Practice with AI-powered mock interviews tailored to your role.
4. **Track Progress:** Monitor your growth with analytics and performance charts.

---

## 📦 Getting Started

1. **Clone the repo:**
   ```bash
   git clone <your-repo-url>
   cd PathwayAI
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**
   - Copy `.env.example` to `.env` and fill in your database and Clerk credentials.
4. **Run database migrations:**
   ```bash
   npx prisma migrate deploy
   ```
5. **Start the dev server:**
   ```bash
   npm run dev
   ```

---

## ❓ FAQ

- **What makes PathwayAI unique?**
  - Combines AI-powered tools with industry insights for a holistic career platform.
- **Is my data secure?**
  - Yes, all data is encrypted and authentication is managed by Clerk.
- **Can I edit AI-generated content?**
  - Yes! All resumes, cover letters, and interview answers are fully editable.
- **How often are industry insights updated?**
  - Weekly, using AI analysis of current market trends.

---

## 🙏 Credits
- Built by Manasvee Rathie
- Powered by Next.js, Prisma, Clerk, and Google Generative AI

---

## 📄 License
This project is for educational and demonstration purposes.

# AI-LEVATE: AI-Powered Career Coach

**AI-LEVATE** is an AI-powered career guidance platform that helps job seekers and professionals make informed career decisions using personalized, data-driven insights. It leverages artificial intelligence to provide resume and cover letter generation, industry analysis, skill evaluation, and learning recommendations.

---

## Features

- **Industry Trend Analysis** – Get insights on emerging technologies, market demand, and salary trends using Gemini API.
- **AI Resume Builder** – Generate optimized, professional resumes tailored to your domain.
- ✉**AI Cover Letter Generator** – Create personalized cover letters aligned with job descriptions.
- **Mock Interview Quizzes** – Practice with AI-generated quizzes, track performance, and get improvement suggestions.
- **Skill & Career Guidance** – Get recommendations on in-demand skills and potential career paths.
- **Future Enhancements (Planned)** – Daily/weekly challenges, job recommendations, and AI-generated learning roadmaps.

---

## Tech Stack

| Frontend       | Backend               | Database            | AI & Utilities       |
|----------------|-----------------------|---------------------|----------------------|
| React 19       | Next.js 15            | NeonDB (PostgreSQL) | Gemini API           |
| Tailwind CSS   | Inngest (Event workflows) | Prisma ORM      | Clerk (Authentication) |
| ShadCN UI      |                       |                     |                      |

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gyanprakash03/AiLevate.git
   cd ai-levate
2. Install dependencies:

    ```bash
    npm install
    Create a .env file with the following:

3. env:
    ```env
    DATABASE_URL=your_neondb_url
    GEMINI_API_KEY=your_gemini_api_key
    CLERK_SECRET_KEY=your_clerk_key

4. Run the development server:

    ```bash
    npm run dev

---

# Folder Structure

```bash
/app               → Pages & routes
/components        → Reusable UI components (Shadcn-based)
/lib               → Utility functions and config
/prisma            → Prisma schema and migrations
/public            → Assets
```

---

## Contact
For suggestions or inquiries, feel free to connect at: gyan091203@gmail.com

---

## Screenshots

# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI 🔥🔥


![sensai](https://github.com/user-attachments/assets/eee79242-4056-4d19-b655-2873788979e1)

# DEVSENSAI - AI-Powered Career Coaching Platform

## Overview

DEVSENSAI is an AI-powered career coaching platform that helps users streamline their job search and career growth. It provides personalized resume generation, cover letter creation, mock interviews, and industry trend insights based on user skills. At every step, AI assists in guiding career decisions.

## Features

- **AI-Generated Resumes**
- **Cover Letter Creation**
- **Mock Interviews**
- **Industry Trend Insights**
- **AI-Powered Career Guidance**

## Tech Stack

**Frontend:** Next.js, Tailwind CSS, ShadCN  
**Backend:** Next.js API Routes, Prisma  
**Database:** PostgreSQL  
**AI Integration:** Gemini AI  
**Authentication:** Clerk  

## Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/yourusername/DEVSENSAI.git
cd DEVSENSAI
```

### Install Dependencies
```bash
npm install
```

### Set Up Environment Variables
Create a `.env` file and add the following environment variables:
```env
DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
GEMINI_API_KEY=
```

### Migrate Database
```bash
npx prisma migrate dev
```

### Start the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) to view the app.

## Deployment

### Vercel
```bash
vercel
```
Follow the instructions to deploy.

### Docker (Optional)
```bash
docker build -t devsensai .
docker run -p 3000:3000 devsensai
```

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License.

## Connect with Me
- **LinkedIn:** [Your LinkedIn Profile](#)
- **GitHub:** [Your GitHub Profile](#)

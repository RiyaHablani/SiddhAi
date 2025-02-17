# **SiddhAi - AI-Powered Career Coach**

SiddhAi is an advanced AI-driven career coach platform designed to revolutionize job applications and professional growth. By leveraging artificial intelligence, SiddhAi offers tailored solutions for resume tailor,cover letter generation, interview preparation, and industry insights, empowering users to make informed decisions in their career journeys.

## 🚀 **Key Features**

### AI-Powered Resume Optimization
Easily customize your resume with AI-generated feedback and see live changes as you enhance it, boosting your chances of landing your dream job.

### Smart Cover Letter Generation
Craft customized cover letters by simply providing the job description, ensuring that each application stands out.

### AI-Driven Interview Preparation
Enhance your interview performance with personalized assessments and actionable feedback on areas for improvement.

### Industry Insights
Stay ahead with data-driven salary trends, in-demand skills, and key industry analysis to make informed career decisions.

### Personalized Experience
Track progress, receive tailored recommendations, and improve your career strategy with continuous AI-driven feedback.

## 🛠️ **Tech Stack**

- **Frontend:** Next.js, React, Tailwind CSS
- **Backend:** Node.js, Express.js, Prisma ORM
- **Database:** PostgreSQL (NeonDB)
- **Authentication:** Clerk
- **Event Handling:** Inngest
- **Deployment:** Vercel

## 📌 **Core Components**

### Prisma Schema
Defines the essential data models (User, Resume, CoverLetter, Assessment, IndustryInsight) for efficient data management and querying.

### Middleware
Handles authentication and enforces role-based access control for secure and personalized routes.

### AI-Powered Career Assessments
Uses historical data to generate personalized improvement suggestions and career growth insights.

### Resume & Cover Letter Builder
User-friendly UI with integrated AI-powered feedback to enhance job applications for higher success rates.

## 📢 **Why Choose SiddhAi?**

SiddhAi isn't just another career tool—it's a smart, adaptable assistant that customizes your career growth journey. By using AI to optimize your job applications, SiddhAi maximizes your chances of success, helping you move faster and smarter through your career milestones.

## 🚀 **Get Started**

### Clone the repository:
```bash
git clone https://github.com/your-repo/siddhai.git

### Install dependencies:
npm install
### Configure environment variables:
Make sure to set up the following in your .env file:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

### Run the development server:
npm run dev

### 🤝 Contributing
We welcome contributions to make SiddhAi even better! If you have any new feature suggestions, or improvements, feel free to submit a PR.

📜 License
MIT License. See the LICENSE file for more details.

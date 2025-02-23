# AI Career Coach

## Introduction
AI Career Coach is a full-stack web application that leverages artificial intelligence to provide personalized career guidance. It helps users by analyzing their skills, resumes, and job preferences to offer tailored career recommendations, interview preparation, and job matching.

## Problem Statement
Choosing the right career path is challenging for many individuals. Traditional career guidance is often generalized and lacks personalization. Many job seekers struggle with resume building, interview preparation, and identifying skill gaps. AI Career Coach aims to bridge this gap by offering AI-powered, data-driven career recommendations.

## Solution
AI Career Coach uses machine learning models to analyze user data, such as skills, job preferences, and past experiences. It then generates personalized career advice, recommends relevant job opportunities, and assists with resume enhancement and mock interviews.

## Technology Stack
The project is built using the following technologies:
- **Frontend:** Next.js (for building the user interface)
- **Backend:** Node.js and Express.js (for handling API requests)
- **Database:** PostgreSQL (Neon for cloud-based database management)
- **Authentication:** Clerk (for user authentication and authorization)
- **AI Models:** OpenAI API (for natural language processing and resume analysis)
- **Serverless Functions:** Inngest (for automating backend workflows)
- **Hosting:** Vercel (for frontend) and Railway (for backend deployment)

## Key Features
- **Personalized Career Guidance:** AI-based recommendations based on user profiles.
- **Resume Analysis:** AI-powered resume feedback and improvement suggestions.
- **Job Matching:** Finds the best job opportunities based on skills and preferences.
- **Interview Preparation:** AI-generated mock interview questions and feedback.
- **Skill Gap Analysis:** Identifies missing skills and suggests learning resources.

## Workflow
1. User registers and logs in using Clerk authentication.
2. The system collects user details (skills, job preferences, experience).
3. AI analyzes the data and generates career recommendations.
4. User receives job suggestions, resume feedback, and interview questions.
5. Backend handles data storage and automation using serverless functions.

## Use Cases
- **Students** looking for career guidance based on their education and interests.
- **Job seekers** needing AI-powered resume review and job recommendations.
- **Professionals** aiming to switch careers and identify skill gaps.
- **HR professionals** using AI to assist candidates in career planning.

## Installation and Setup
Follow these steps to set up the project on your local machine:

### Prerequisites
Ensure you have the following installed:
- Node.js (>= 16.x)
- PostgreSQL database (Neon for cloud-based management)
- Git

### Clone the Repository
```sh
git clone https://github.com/chetanck03/Ai-coach.git
cd Ai-coach
```

### Install Dependencies
```sh
npm install
```

### Set Up Environment Variables
Create a `.env` file in the root directory and configure the following:
```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```

### Start the Development Server
```sh
npm run dev
```
The server should start on `http://localhost:3000`.

## Deployment
To deploy the application, use platforms like **Vercel (Frontend)** and **Railway (Backend)**. Ensure environment variables are set accordingly.

## Hackathon Relevance
This project aligns with the **'AI for Smart and Adaptive Systems'** track by using AI to personalize career guidance. It automates coding assistance, provides financial insights through job market analysis, and generates career-related suggestions efficiently.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

## License
This project is licensed under the **MIT License**.

## Contact
For any queries or contributions, reach out via [GitHub Issues](https://github.com/chetanck03/Ai-coach/issues).

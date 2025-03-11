# CareerPilot AI

## Project Overview

CareerPilot AI is an AI-powered career development platform designed to assist professionals in optimizing their job search. It provides intelligent tools to enhance career documents, prepare for interviews, and assess skills through interactive quizzes. By leveraging advanced AI models, CareerPilot AI offers personalized guidance and industry-specific insights to help users navigate the competitive job market effectively.

## Features

- **AI-Generated Resumes**: Create professional and optimized resumes with AI-driven suggestions.
- **AI-Powered Cover Letters**: Generate personalized cover letters tailored to job descriptions.
- **Adaptive Interview Preparation**: Practice interviews with AI-driven feedback and real-world questions.
- **Industry-Specific Quizzes**: Assess career readiness with tailored skill-based quizzes.
- **Real-Time Industry Insights**: Stay updated with job market trends and industry demands.
- **Data Security Measures**: Ensure user data privacy with robust encryption and authentication mechanisms.

## Tech Stack

- **Frontend**: Next.js
- **Backend**: Inngest for background task processing
- **Database**: NeonDB with Prisma ORM
- **Authentication**: Clerk`

## Installation Guide

Follow these steps to set up the CareerPilot AI project:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/shreyshukla29/CareerPilot-AI.git
   cd CareerPilot-AI
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Configure environment variables:**
   - Create a `.env` file in the root directory and add required variables such as:
     ```sh
     DATABASE_URL=<your-neondb-url>
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
     CLERK_SECRET_KEY=<your-clerk-secret-key>
     NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
     NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
     NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
     NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
     GEMINI_API_KEY=<your-gemini-api-key>
     ```
4. **Run the development server:**
   ```sh
   npm run dev
   ```

## Usage Guide

1. **Sign up/Login**: Use Clerk authentication to create an account.
2. **Complete Quizzes**: Take industry-specific quizzes to evaluate your skills.
3. **Generate Career Documents**:
   - Create AI-powered resumes and cover letters.
4. **Prepare for Interviews**:
   - Utilize the adaptive interview preparation tool for practice and feedback.
5. **Track Progress**:
   - Monitor skill improvements and document versions through the dashboard.

## Security & Privacy

- All user data is securely stored in **NeonDB** and managed via **Prisma ORM**.
- Authentication is handled by **Clerk**, ensuring robust security and user verification.
- End-to-end encryption is implemented to protect sensitive information.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

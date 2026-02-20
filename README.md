
# 🎓 SensAI – AI-Powered Career Coach Platform

**SensAI** is an AI-driven career assistant web application designed to help students, job seekers, and professionals navigate their career paths with confidence. Built with modern full-stack web technologies such as **Next.js**, **React**, **Tailwind CSS**, and integrated with **OpenAI’s GPT language models**, this platform offers intelligent guidance in the form of resume reviews, interview coaching, skill path planning, and real-time AI chat support.

SensAI aims to bridge the gap between ambition and action by providing users with personalized, contextual career support—right from choosing a career path to preparing for job interviews. Whether you're a college student unsure of your next step, or a working professional looking to switch domains, SensAI is built to guide you with the power of Artificial Intelligence.

---

## 🧠 Project Vision

The idea behind SensAI was born from a common pain point: lack of personalized career support accessible to all. Career coaches are expensive, and online advice is often generic or outdated. With advancements in Natural Language Processing and AI models like GPT-4, we now have the ability to democratize mentorship and career coaching.

SensAI leverages AI to simulate the kind of nuanced advice you'd expect from a real human mentor. It provides:
- Context-aware guidance based on the user’s input
- AI-generated feedback on resumes, profiles, and portfolios
- Behavioral and technical interview practice through AI simulations
- Learning path suggestions based on current skills and goals

---

## ⚙️ Core Features and Functionalities

### 🔍 Personalized Career Guidance
Users can interact with the AI coach to receive career path suggestions tailored to their background, skills, and goals. The guidance evolves dynamically based on the user's queries and selections.

### 🧾 Resume Analyzer
Users can paste their resumes into the platform and receive detailed AI feedback on structure, wording, technical accuracy, and impact. The system highlights areas for improvement and suggests enhancements based on industry standards.

### 🎯 Skill Gap & Learning Path Planner
The system can suggest personalized learning paths, including free/paid resources, certifications, and technologies to master based on the user's desired job role or industry.

### 🧠 Interview Prep Simulator
The chatbot is capable of simulating behavioral or technical interview questions based on the selected domain. It can also give real-time evaluation tips to help improve answers.

### 🌐 Modern Responsive UI
The application has a sleek, mobile-friendly, dark-mode-enabled interface built using Tailwind CSS, offering an intuitive and clutter-free user experience.

---

## 🛠️ Technologies and Tools Used

SensAI demonstrates a strong understanding and practical use of the following technologies:

### Frontend:
- **React.js**: For component-based UI development.
- **Next.js**: React framework with server-side rendering, routing, and API support.
- **Tailwind CSS**: Utility-first CSS framework for rapid styling.

### Backend:
- **Next.js API Routes**: Handles server-side functions such as AI requests.
- **Prisma ORM**: Manages database access and schema for storing user data, logs, or preferences.
- **OpenAI API (GPT-4)**: Delivers AI-driven conversational and analytical capabilities.

### Dev Tools & Config:
- **Vercel**: Deployment and hosting platform for Next.js apps.
- **npm**: For managing JavaScript dependencies.
- **.env**: Environment variable management for secure API keys.

---

## 📁 Project Structure

SensAI/
├── app/ # Main app pages and routes
├── components/ # Reusable UI components
├── data/ # Static and structured data files
├── hooks/ # Custom React hooks
├── lib/ # Utility and helper functions
├── prisma/ # Prisma schema and database access layer
├── public/ # Static assets (images, icons, etc.)
├── .gitignore # Files to be ignored by Git
├── next.config.mjs # Next.js configuration
├── tailwind.config.mjs # Tailwind CSS customization
├── middleware.js # Middleware logic for request handling
└── package.json # Project metadata and scripts

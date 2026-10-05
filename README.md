# AI Mock Interview

An AI-powered mock interview platform that helps users practice job interviews through realistic AI-driven conversations and receive detailed feedback on their performance.

The platform allows users to create customized interviews based on their job role, experience level, interview type, and technical stack, then participate in an AI-powered interview and receive detailed performance feedback.

---

## ✨ Features

- 🔐 **User Authentication**
  - Secure sign up and sign in using Firebase authentication.
- 🤖 **AI Interview Generation**
  - Generate customized interview questions based on job role, experience level, interview type, and technical stack.
- 🎙️ **AI Voice Interviews**
  - Conduct realistic mock interviews using an AI voice agent.
- 🧠 **AI-Powered Feedback**
  - Receive detailed feedback after completing an interview.
- 📊 **Performance Analysis**
  - Get scores and feedback for:
    - Communication Skills
    - Technical Knowledge
    - Problem-Solving
    - Cultural & Role Fit
    - Confidence & Clarity
- 📋 **Interview Dashboard**
  - View and manage previously created interviews.
- 🔄 **Retake Interviews**
  - Retake previous interviews to improve your performance.
- 📱 **Responsive Design**
  - Works across desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

- Next.js
- React
- Tailwind CSS
- Firebase
- Vapi AI
- Google Gemini
- shadcn/ui
- Zod

---

## 🔄 How It Works

```text
User
  ↓
Select Interview Preferences
  ↓
AI Generates Questions
  ↓
AI Voice Interview
  ↓
Interview Transcript
  ↓
AI Evaluates Performance
  ↓
Detailed Feedback & Score
```

### 📋 Interview Creation
Users can create an interview by providing:
- Job role
- Experience level
- Technical stack
- Interview type
- Number of questions

The application then generates interview questions tailored to the selected preferences.

### 📊 AI Feedback
After completing an interview, the system analyzes the candidate's responses and provides:
- Overall score
- Category-wise scores
- Detailed assessment
- Strengths
- Areas for improvement

This helps users understand their performance and identify areas that need improvement.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- Git
- Node.js
- npm

### Clone the Repository
```bash
git clone <your-repository-url>
cd <your-project-folder>
```

### Install Dependencies
```bash
npm install
```

### Environment Variables
Create a `.env.local` file in the root directory and add:

```env
NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=

GOOGLE_GENERATIVE_AI_API_KEY=

NEXT_PUBLIC_BASE_URL=

NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=

FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=
```
*Add your actual Firebase, Vapi, and Google Gemini credentials.*  
**Important:** Never commit your `.env.local` file or expose your API keys publicly.

### Run the Project
```bash
npm run dev
```
Open the application in your browser: [http://localhost:3000](http://localhost:3000)

---

## 📁 Project Structure

```text
AI-Mock-Interview/
│
├── app/
│   ├── api/
│   ├── interview/
│   └── ...
│
├── components/
├── constants/
├── lib/
├── public/
├── types/
│
├── .env.local
├── package.json
├── next.config.ts
└── README.md
```

---

## 🧠 AI Evaluation

The feedback system evaluates the candidate across multiple categories. Each category receives a score from 0 to 100, along with a detailed explanation of the candidate's performance.

### Evaluation Categories

| Category | Description |
| :--- | :--- |
| **Communication Skills** | Clarity, articulation, and structure of responses |
| **Technical Knowledge** | Understanding of concepts relevant to the role |
| **Problem-Solving** | Ability to analyze problems and propose solutions |
| **Cultural & Role Fit** | Alignment with the role and company expectations |
| **Confidence & Clarity** | Confidence, engagement, and clarity while answering |

---

## 🎯 Project Goal

This project was built as a personal full-stack project to explore the integration of:
- AI APIs
- Voice-based AI agents
- Authentication
- Database-backed applications
- Next.js & React
- Responsive UI
- AI-powered evaluation

The main goal is to build a practical application that helps candidates practice interviews and receive useful feedback before attending real interviews.

---

## 🔮 Future Improvements

- 📈 Interview progress tracking
- 📊 Advanced performance analytics
- 🎭 Multiple AI interviewer personalities
- 📄 Resume-based interview generation
- 🎯 Personalized preparation recommendations
- 📝 Custom interview templates
- 🧠 Improved conversational AI

---

## 👨‍💻 Author

**Avinash Raj**  
Computer Science Engineer | Full-Stack Developer  
*Built with Next.js, React, AI, and a lot of experimentation.*

⭐ *If you find this project useful or interesting, consider giving the repository a star.*

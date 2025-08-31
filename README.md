📄 AI Resume Analyzer

An AI-powered web application that helps analyze resumes and provides feedback on skills, strengths, and improvements.
Built with React (Vite) and OpenAI API.

🚀 Features

Upload resumes (PDF/DOCX)

AI-powered resume analysis

Highlights key skills and weaknesses

Provides tailored suggestions for improvement

Simple and clean UI

🛠️ Tech Stack

Frontend: React + Vite + TypeScript

Styling: TailwindCSS (if included)

AI Engine: OpenAI GPT models

Deployment: Vercel / Netlify

⚡ Getting Started
1. Clone the repo
git clone https://github.com/YOUR_USERNAME/ai-resume-analyzer.git
cd ai-resume-analyzer

2. Install dependencies
npm install

3. Set up environment variables

Create a file called .env in the project root and add your OpenAI API key:

VITE_OPENAI_API_KEY=your_openai_api_key_here


Get your API key from OpenAI
.

4. Run the app locally
npm run dev


Visit http://localhost:5173
 in your browser.

🌍 Deployment
Deploy on Vercel

Push your project to GitHub.

Go to Vercel
 → New Project → Import repo.

Build command: npm run build

Output directory: dist

Add environment variable:

VITE_OPENAI_API_KEY=your_openai_api_key_here


Deploy 🎉

Your app will be live at:

https://your-app-name.vercel.app/

🔒 Security Note

Currently, the OpenAI key is exposed in the frontend.
For production use, set up a backend API (Node/Express or serverless functions) to hide your API key securely.

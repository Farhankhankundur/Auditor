🔍 CheckMate

Real-time, Full-Stack Website Auditor — Private, Powerful, AI-Assisted

CheckMate is a full-stack web application that performs a comprehensive, real-time audit of any given website. Unlike typical online tools, it runs locally — ensuring privacy, speed, and deep technical insights.

Think of it as your website’s personal health scanner + AI analyst — all running from your machine.

✨ Core Features

🔐 Multi-Faceted Audit

DNS Records

TLS/SSL Certificates

Security Headers

Performance Metrics (Lighthouse-style checks)

SEO Best Practices

Accessibility Issues

🤖 AI-Powered Assistant (Gemini Integration)

After an audit, an AI assistant (powered by Google Gemini) provides:

Expert, structured analysis

Actionable improvement tips

Conversational Q&A on audit results

⚡ Clean Client-Server Architecture

Backend: Node.js + Express → Handles auditing & AI communication

Frontend: Vanilla JavaScript → Tabbed UI for structured results

🚀 Quick Start
1️⃣ Prerequisites

Install Node.js
 (latest LTS recommended).

2️⃣ Install Dependencies
cd a3/backend
npm install

3️⃣ Configure Gemini API

The AI assistant requires a Google Gemini API key.

Get your API key from Google AI Studio
.

Create a .env file in the backend folder.

Add your key:

GEMINI_API_KEY=YOUR_API_KEY_HERE

4️⃣ Run the Server
cd backend
node server.js


You should see:

Server listening on port 3333

5️⃣ Open the App

Navigate to 👉 http://localhost:3333

Enter a website URL → Click Run Audit → Get instant results + AI analysis

📸 Demo Preview

(You can add screenshots / GIFs of your interface here)

🧩 Why CheckMate is Different

✅ No Third-Party Data Leaks – Everything runs locally.
✅ Full-Stack Control – Not just frontend scans, but deep backend-powered analysis.
✅ AI-Enhanced Reports – Get expert, conversational advice instead of raw logs.
✅ Lightweight & Portable – Simple Node.js + JS stack.

🤝 Contributing

Pull requests are welcome! If you’d like to add new audit checks or improve the UI, open an issue first to discuss your idea.

# AI Resume Critiquer 📄🤖

AI Resume Critiquer is a modern, AI-powered web application that analyzes resumes and provides **structured, actionable feedback**. Built with **Streamlit** and powered by **OpenAI’s GPT models**, this tool helps job seekers optimize their resumes for **clarity, impact, and relevance**.

Whether you’re applying for a specific role or seeking general improvement, AI Resume Critiquer offers **personalized suggestions** to enhance your chances of securing interviews.

---

## Features ✨
- **Upload Resumes** – Supports **PDF** and **TXT** formats.
- **Role-Specific Feedback** – Optionally enter a target job role for tailored suggestions.
- **AI-Driven Insights** – Uses OpenAI’s advanced language models for professional-grade resume critiques.
- **Actionable Recommendations** – Guidance on content clarity, skills presentation, and experience descriptions.
- **Interactive UI** – Built with Streamlit for a clean user experience.

---

## Tech Stack 🛠
- **Python 3**
- **Streamlit** – Frontend and UI
- **PyPDF2** – PDF text extraction
- **OpenAI API** – AI analysis
- **python-dotenv** – Environment variable management

---

## Getting Started 🚀

### 1. Clone the repository
```bash
git clone https://github.com/kalbatati/AI-Resume-Critiquer.git
cd AI-Resume-Critiquer

Install dependencies:
pip install -r requirements.txt

Set up your environment variables:
OPENAI_API_KEY=your_openai_api_key_here

Run the application:
streamlit run main.py

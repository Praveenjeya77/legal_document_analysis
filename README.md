🧾 Legal Document Summarizer Using LLMs

This project is an AI-powered web application that analyzes legal documents and generates:

✔ Comprehensive summary
✔ Glossary of legal terms (simplified explanation)
✔ AI-inferred verdict or outcome
✔ Custom Q&A based on document content

It supports PDF, DOCX, and TXT files and uses open-source LLMs to ensure accessibility and scalability.

🚀 Features
Feature	Description
📝 Summary	Extracts key points, legal facts, issues & arguments
📘 Glossary	Identifies and explains legal terminology
⚖️ Verdict Prediction	Infers likely case outcome (non-legal advisory)
❓ Q&A	Ask specific questions based on uploaded document
⬇ Save Summary	Generates downloadable results file
🛠️ Tech Stack
Category	Tool
Framework	Gradio
AI/LLM Models	Pegasus-XSum (Summarization), LaMini-T5 (Text Generation)
Document Extractor	pdfplumber, python-docx
Language	Python
📂 Project Structure
📁 Legal-Summarizer/
│── app.py                 # Main application code
│── requirements.txt       # Dependencies
│── langflow_prd12.json    # Workflow structure (optional)
│── README.md              # Documentation

⚙️ Installation & Setup
🔹 1️⃣ Clone the Repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

🔹 2️⃣ Install Dependencies
pip install -r requirements.txt

🔹 3️⃣ Run the Application
python app.py


The Gradio interface will open in your browser:
👉 http://127.0.0.1:7860/

📌 Usage Instructions

1️⃣ Upload a legal document (PDF/DOCX/TXT)
2️⃣ Click Analyze Document
3️⃣ View:

Extracted text

AI summary

Glossary

Predicted verdict

4️⃣ Ask follow-up questions for deeper insights
5️⃣ Download the generated report if needed

🌐 Models Used
Model	Purpose
google/pegasus-xsum	High quality summarization
MBZUAI/LaMini-T5-738M	Legal glossary + verdict reasoning

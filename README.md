# 🧾 Legal Documentation Assistant

The **Legal Documentation Assistant** is a data science-based web application designed to help users easily analyze, summarize, and manage legal documents. It provides a simple interface where users can upload documents, extract important details, and get automated summaries using natural language processing (NLP).

---

## 🚀 Overview

This project combines **Flask (backend)**, **MySQL (database)**, and a **React frontend** to deliver an intelligent legal assistant system. It helps users handle lengthy legal documents efficiently by applying text preprocessing, keyword extraction, and summarization techniques — making legal document analysis faster and more accessible.

---

## ✨ Features

- 📄 **Upload and Process Legal Documents** — Upload legal documents for automatic analysis and storage.  
- 🧠 **Text Summarization and Keyword Extraction** — Uses NLP to summarize and highlight key legal terms.  
- 💬 **Interactive Frontend Interface** — Clean and user-friendly interface built with React.  
- 🗄️ **Database Integration** — All document data and summaries are securely stored in MySQL.  
- ⚙️ **Flask REST API** — Backend service that connects the frontend with NLP processing and database operations.

---

## 🛠️ Tech Stack

| Component | Technology Used |
|------------|----------------|
| Frontend | React.js |
| Backend | Flask (Python) |
| Database | MySQL |
| NLP | NLTK |
| Deployment | Localhost / Any server |
| Language | Python, JavaScript |

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/adhithya2525/DataScience_project.git
cd DataScience_project
2. Backend Setup
bash
Copy code
cd server
pip install -r requirements.txt
python app.py
3. Frontend Setup
bash
Copy code
cd ../client
npm install
npm start
Your backend will run on http://127.0.0.1:5000/
Frontend will run on http://localhost:3000/

💡 How It Works
The user uploads or enters a legal document.

Flask backend processes the text using NLP (tokenization, summarization).

Extracted summaries and key points are stored in MySQL.

The React frontend displays the results in a structured and readable format.

🧩 Folder Structure
bash
Copy code
Legal-Documentation-Assistant/
│
├── client/          # React frontend
├── server/          # Flask backend
├── model/           # NLP processing scripts
├── assets/          # Images or icons
└── README.md        # Project documentation

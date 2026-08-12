# 🤖 AI Resume Reviewer

An **AI-powered Resume Reviewer** that analyzes resumes and provides smart feedback to help users improve their resumes and make them more job-ready.

## 📌 About the Project

AI Resume Reviewer is a web-based application that uses **Artificial Intelligence and Natural Language Processing (NLP)** to analyze a user's resume.

The system extracts important information from the uploaded resume, checks skills and keywords, evaluates the resume, and provides useful suggestions for improvement.

Users can also provide a **Job Description** to compare their resume with the requirements of a particular job.

## ✨ Features

* 📄 Upload Resume in PDF format
* 🤖 AI-based Resume Analysis
* 📊 Resume Score
* 🎯 ATS Compatibility Analysis
* 🔍 Skill Detection
* 🔑 Keyword Analysis
* 📝 Job Description Matching
* ❌ Missing Skills and Keywords Detection
* ✅ Resume Strengths Identification
* 💡 Personalized Improvement Suggestions
* 📈 Job Match Percentage
* 📱 Simple and User-Friendly Interface

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Python, Flask
* **AI/NLP:** Natural Language Processing
* **PDF Processing:** PyMuPDF
* **Machine Learning:** Scikit-learn
* **Database:** SQLite
* **Version Control:** Git & GitHub
* **IDE:** Visual Studio Code

## ⚙️ How It Works

```text
User Uploads Resume
        ↓
PDF Text Extraction
        ↓
Resume Information Extraction
        ↓
AI/NLP Analysis
        ↓
Skills & Keyword Detection
        ↓
ATS Analysis
        ↓
Job Description Matching
        ↓
Score & Feedback Generation
        ↓
Personalized Suggestions
```

## 📂 Project Structure

```text
AI-Resume-Reviewer/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   └── result.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── utils/
│   ├── pdf_parser.py
│   ├── resume_analyzer.py
│   └── keyword_matcher.py
│
├── uploads/
│
└── screenshots/
```

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Resume-Reviewer.git
```

### 2. Open the Project

```bash
cd AI-Resume-Reviewer
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python app.py
```

### 7. Open in Browser

```text
http://127.0.0.1:5000/
```

## 📊 Resume Analysis

The application evaluates different aspects of a resume, such as:

* Skills
* Projects
* Education
* Experience
* Keywords
* Job Description Match
* Resume Structure

The system then generates a score and provides recommendations for improvement.

## 🎯 Job Description Matching

Users can paste a job description into the application.

The system compares the job requirements with the candidate's resume and identifies:

* Matching skills
* Missing skills
* Relevant keywords
* Job match percentage

## 💡 Example Feedback

```text
Resume Score: 82%

Strengths:
✓ Good technical skills
✓ Projects are included
✓ Clear education section

Missing Keywords:
• REST API
• Docker
• AWS

Suggestions:
→ Add measurable achievements to projects.
→ Include relevant job-specific keywords.
→ Improve the professional summary.
```

## 🔮 Future Scope

* AI-generated resume improvement
* AI-generated professional summary
* Interview questions based on resume
* GitHub project analysis
* Resume comparison with multiple job descriptions
* Resume improvement recommendations
* Multiple resume template support
* Cloud deployment
* User authentication and resume history

## 🔐 Security

* Do not upload passwords, API keys, or other sensitive information to the repository.
* API keys should be stored in environment variables such as `.env`.
* Uploaded resumes should be handled securely.

## ⭐ Project Purpose

This project was developed as an academic and portfolio project to demonstrate the practical use of **Artificial Intelligence, NLP, Python, Flask, and Web Development** in a real-world application.

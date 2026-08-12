# AI Resume Reviewer Using Artificial Intelligence

## 1. Project Objective

The AI Resume Reviewer is a web-based application that uses Artificial Intelligence to analyze and review a user's resume.

The system helps users understand their resume score, ATS compatibility, relevant skills, missing keywords, strengths, weaknesses, and job-description matching.

## 2. Main Features

- Resume Upload (PDF/DOCX)
- AI Resume Analysis
- Overall Resume Score
- ATS Analysis
- Job Description Matching
- Missing Skills and Keywords Detection
- AI Resume Improvement Suggestions
- Dashboard
- Review History

## 3. Technology Stack

### Frontend
- React.js
- HTML
- CSS
- JavaScript
- Bootstrap/Tailwind CSS
- Chart.js/Recharts

### Backend
- Node.js
- Express.js
- REST APIs

### Database
- MongoDB
- MongoDB Atlas

### Artificial Intelligence
- AI/LLM API

### Authentication
- JWT
- Password Hashing

### File Processing
- PDF/DOCX Text Extraction

### Version Control
- Git
- GitHub

## 4. System Workflow

User
↓
Login/Signup
↓
Upload Resume
↓
Extract Resume Text
↓
Select Target Job Role
↓
Enter Job Description
↓
AI Analysis
↓
Resume + Job Description Matching
↓
Generate Results
↓
Dashboard
↓
Improvement Suggestions

## 5. Database Collections

### User
- userId
- name
- email
- password
- createdAt

### Resume
- resumeId
- userId
- fileName
- fileUrl
- extractedText
- uploadedAt

### Review
- reviewId
- userId
- resumeId
- overallScore
- atsScore
- strengths
- weaknesses
- missingSkills
- suggestions
- createdAt

### Job Description
- jobId
- userId
- title
- description
- requiredSkills
- createdAt

## 6. API Planning

### Authentication
- POST /api/auth/register
- POST /api/auth/login

### Resume
- POST /api/resume/upload
- GET /api/resume
- GET /api/resume/:id
- DELETE /api/resume/:id

### AI Review
- POST /api/review/analyze
- GET /api/review/:id
- GET /api/review/history

### Job Matching
- POST /api/job/match
- POST /api/job/analyze

## 7. Project Outcome

The final system will allow users to upload a resume and receive AI-based analysis including resume score, ATS score, strengths, weaknesses, missing skills, job match percentage, and improvement suggestions.

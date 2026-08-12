# Database Design

The project will use MongoDB as the database.

## 1. User Collection

Fields:

- userId
- name
- email
- password
- createdAt

## 2. Resume Collection

Fields:

- resumeId
- userId
- fileName
- fileUrl
- extractedText
- uploadedAt

## 3. Review Collection

Fields:

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

## 4. Job Description Collection

Fields:

- jobId
- userId
- title
- description
- requiredSkills
- createdAt

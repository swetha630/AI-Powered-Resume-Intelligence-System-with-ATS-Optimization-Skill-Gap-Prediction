# 📄 AI Resume Intelligence System with ATS Optimization & Skill Gap Prediction

<p align="center">

![React](https://img.shields.io/badge/Frontend-React-61DAFB?logo=react)
![Flask](https://img.shields.io/badge/Backend-Flask-000000?logo=flask)
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-success)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

<p align="center">

An AI-powered Resume Analysis platform that evaluates ATS compatibility, identifies skill gaps, matches resumes with job descriptions, and provides personalized recommendations to improve interview opportunities.

</p>

---

# 📖 Overview

Recruiters today receive thousands of resumes for every job opening. Before a recruiter even reviews a resume, it typically passes through an **Applicant Tracking System (ATS)** that filters candidates based on keywords, skills, and relevance to the job description.

Many qualified candidates get rejected—not because they lack the required skills, but because their resumes fail ATS screening.

The **AI Resume Intelligence System** addresses this challenge by leveraging **Artificial Intelligence**, **Natural Language Processing (NLP)**, and **Machine Learning** to analyze resumes, compare them with job descriptions, and provide actionable insights that help candidates improve their chances of getting shortlisted.

---

# ❗ Problem Statement

Modern recruitment processes heavily rely on ATS software to filter resumes automatically.

Common challenges faced by candidates include:

- 📄 Poor ATS compatibility
- 🔍 Missing role-specific keywords
- 🎯 Difficulty understanding recruiter expectations
- 📉 Low job-description match scores
- ❌ Lack of personalized resume feedback

These issues often prevent skilled candidates from progressing to interviews.

---

# 💡 Solution

The AI Resume Intelligence System bridges the gap between candidate potential and recruiter expectations.

The platform automatically:

- 📂 Extracts text from uploaded resumes
- 🤖 Calculates ATS compatibility score
- 🎯 Matches resumes with job descriptions
- 🧠 Identifies missing technical skills
- 💡 Generates personalized improvement suggestions
- 📊 Presents results through an intuitive dashboard

---

# ✨ Key Features

- 📄 Resume PDF Upload
- 🤖 ATS Score Prediction (0–100%)
- 🎯 Job Description Matching
- 🧠 Skill Extraction
- 📉 Skill Gap Analysis
- 📊 Resume Keyword Analysis
- 💡 AI-based Resume Improvement Suggestions
- ⚡ Fast Resume Processing
- 🎨 Interactive Dashboard

---

# 🏗️ System Architecture

```text
                 User Uploads Resume (PDF)
                          │
                          ▼
               PDF Text Extraction
                  (pdfplumber)
                          │
                          ▼
                NLP Processing Layer
      (TF-IDF • Regex • Keyword Extraction)
                          │
                          ▼
             AI Resume Analysis Engine
     ├── ATS Score
     ├── Job Matching
     ├── Skill Gap Detection
     └── Personalized Suggestions
                          │
                          ▼
                Interactive Dashboard
```

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | React, HTML, CSS |
| Backend | Flask |
| Programming Language | Python |
| NLP | TF-IDF, Cosine Similarity |
| Resume Parsing | pdfplumber |
| Text Processing | Regex |
| Machine Learning | Scikit-learn |
| Version Control | Git & GitHub |

---

# ⚙️ Core Technologies

### 🎨 Frontend

- React.js
- HTML5
- CSS3

Provides a responsive dashboard that displays ATS scores, extracted skills, job match percentages, and personalized recommendations.

---

### ⚙️ Backend

**Flask**

Responsible for:

- API Development
- Resume Upload
- Request Handling
- AI Pipeline Integration

---

### 📄 Resume Processing

**pdfplumber**

Used to:

- Extract text from PDF resumes
- Handle multi-page resumes
- Preserve document structure

---

### 🔍 Text Processing

**Regex**

Performs:

- Section Detection
- Skill Identification
- Experience Extraction
- Keyword Parsing

---

### 🤖 NLP Engine

Implemented using **Scikit-learn**

Algorithms Used:

- TF-IDF Vectorization
- Cosine Similarity

Purpose:

- Convert resume text into numerical vectors
- Compare resume with job description
- Measure semantic similarity

---

# 📂 Project Structure

```text
AI-Resume-Intelligence-System/

│── frontend/
│── backend/
│── uploads/
│── static/
│── templates/
│── requirements.txt
│── app.py
│── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/swetha630/AI-Powered-Resume-Intelligence-System-with-ATS-Optimization-Skill-Gap-Prediction.git
```

Navigate to the project

```bash
cd AI-Powered-Resume-Intelligence-System-with-ATS-Optimization-Skill-Gap-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask server

```bash
python app.py
```

Open the React frontend

```bash
npm install

npm start
```

---

# 🚀 How It Works

1️⃣ Upload Resume (PDF)

⬇

2️⃣ Extract Resume Text

⬇

3️⃣ Upload / Enter Job Description

⬇

4️⃣ Perform NLP Analysis

⬇

5️⃣ Generate ATS Score

⬇

6️⃣ Compare Skills

⬇

7️⃣ Identify Missing Keywords

⬇

8️⃣ Display Dashboard with Suggestions

---

# 📊 Results

The platform generates:

| Output | Description |
|----------|-------------|
| ✅ ATS Score | Resume quality score (0–100%) |
| 🎯 Job Match | Resume similarity with Job Description |
| 🧠 Extracted Skills | Technical skills detected |
| 📉 Skill Gap | Missing technologies and keywords |
| 💡 Suggestions | Personalized resume improvement tips |

---


# 🚀 Future Enhancements

- 🤖 LLM-powered Resume Review
- 🎙 AI Interview Preparation
- 🌐 LinkedIn Profile Analysis
- 📑 Resume Version Comparison
- 📈 Resume Analytics Dashboard
- ☁ Cloud Deployment
- 📤 One-click Resume Export
- 🎯 Multi-role Resume Optimization

---

# 🎯 Learning Outcomes

During this project I gained practical experience in:

- NLP Pipeline Development
- Resume Parsing
- Information Retrieval
- TF-IDF & Cosine Similarity
- REST API Development using Flask
- React State Management
- Full Stack AI Application Development

---

# 👩‍💻 Author

## Swetha Mandapuri

**Artificial Intelligence & Machine Learning Undergraduate**

Chaitanya Bharathi Institute of Technology (CBIT), Hyderabad

📧 Connect with me

- GitHub: https://github.com/swetha630
- LinkedIn: https://www.linkedin.com/in/swetha-mandapuri-3346042a3

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Your support motivates me to build more AI-powered applications.



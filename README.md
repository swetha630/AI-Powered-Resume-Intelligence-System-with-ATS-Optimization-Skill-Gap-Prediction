Problem Statement:

In today’s competitive job market, many candidates get rejected not because of lack of skills, but due to poorly structured resumes that fail to pass Applicant Tracking Systems (ATS).

Most users:

Don’t know if their resume is ATS-friendly

Lack clarity on required skills for specific roles

Don’t receive personalized feedback

This creates a gap between candidate potential and recruiter expectations.


Solution:

The AI Resume Analyzer is designed to bridge this gap by using Artificial Intelligence and Natural Language Processing (NLP) to evaluate resumes.

The system:

Extracts key information from resumes

Calculates an ATS compatibility score

Matches resumes with job descriptions

Identifies missing skills

Provides actionable suggestions

This helps users improve their resumes and increases their chances of getting shortlisted.


Architecture Diagram

                +----------------------+
                |   User Uploads PDF   |
                +----------+-----------+
                           |
                           ↓
                +----------------------+
                |   Text Extraction    |
                |   (PDF Parser)       |
                +----------+-----------+
                           |
                           ↓
                +----------------------+
                |  NLP Processing      |
                |  (Skill Extraction,  |
                |   Keyword Analysis)  |
                +----------+-----------+
                           |
                           ↓
                +----------------------+
                |  AI/Logic Engine     |
                |  - ATS Scoring       |
                |  - Job Matching      |
                |  - Skill Gap Analysis|
                +----------+-----------+
                           |
                           ↓
                +----------------------+
                |  Results Dashboard   |
                |  (Score + Insights)  |
                +----------------------+


Tech Stack

 React, HTML, CSS, Flask, Python, Scikit-learn (TF-IDF, Cosine Similarity), pdfplumber, Regex, Git

🎨 FRONTEND
🔹 React (JavaScript)

Handles dynamic UI

Displays scores, skills, suggestions

Manages API responses using state

🔹 HTML + CSS

Structure and styling

Dashboard layout (cards, sections)

Visual clarity for ATS-like interface

⚙️ BACKEND
🔹 Flask (Python Web Framework)

API development (/analyze)

Handles file upload + requests

Orchestrates entire pipeline

🧠 CORE LANGUAGE
🔹 Python

Main backend language

Implements parsing, scoring, logic

Handles data structures (sets, dicts)

📄 RESUME PROCESSING
🔹 pdfplumber

Extracts text from PDF resumes

Page-wise extraction

Handles structured text better than basic libraries

🔍 TEXT PROCESSING
🔹 Regex (re)

Detects resume sections (skills, projects, etc.)

Extracts experience indicators

Flexible pattern matching

🤖 NLP COMPONENT
🔹 Scikit-learn

Used for:

TfidfVectorizer

cosine_similarity

Purpose:

Convert text → vectors

Measure resume ↔ job similarity

Results / Output

The system provides the following outputs:

✅ ATS Score (0–100%) indicating resume quality

✅ Extracted Skills & Keywords

✅ Job Description Match Percentage

✅ Skill Gap Analysis (missing skills for target role)

✅ Personalized Suggestions to improve resume



Problem Statement:
In today’s competitive job market, many candidates get rejected not because of lack of skills, but due to poorly structured resumes that fail to pass Applicant Tracking Systems (ATS).

Most users:
Don’t know if their resume is ATS-friendly
Lack clarity on required skills for specific roles
Don’t receive personalized feedback
This creates a gap between candidate potential and recruiter expectations.
#############################################################################
Solution:
The AI Resume Analyzer is designed to bridge this gap by using Artificial Intelligence and Natural Language Processing (NLP) to evaluate resumes.

The system:
Extracts key information from resumes
Calculates an ATS compatibility score
Matches resumes with job descriptions
Identifies missing skills
Provides actionable suggestions

This helps users improve their resumes and increases their chances of getting shortlisted.
###################################################################################
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
  ##############################################################################
Tech Stack
Frontend:
HTML
CSS
JavaScript

Backend:
Node.js / Express 

AI / ML Techniques:
Natural Language Processing (NLP)
Keyword Extraction
TF-IDF / Similarity Matching
####################################################################################
Results / Output
The system provides the following outputs:

✅ ATS Score (0–100%) indicating resume quality
✅ Extracted Skills & Keywords
✅ Job Description Match Percentage
✅ Skill Gap Analysis (missing skills for target role)
✅ Personalized Suggestions to improve resume



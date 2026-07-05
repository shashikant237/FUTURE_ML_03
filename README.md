# 📄 AI Resume Screening & Candidate Ranking System using NLP

> **Future Interns - Machine Learning Internship (Task 3)**

An AI-powered Resume Screening and Candidate Ranking System that uses Natural Language Processing (NLP) to compare resumes with a job description, calculate similarity scores, identify matched and missing skills, and rank candidates based on their suitability for a role.

---

## 📌 Project Overview

Recruiters often receive hundreds of resumes for a single job opening, making manual screening time-consuming and inconsistent.

This project automates the initial screening process by using **Natural Language Processing (NLP)** and **Machine Learning** techniques to evaluate resumes against a target job description.

The system calculates a match score, identifies skill gaps, and recommends the most suitable candidates.

---

## 🎯 Objectives

- Clean and preprocess resume text
- Extract relevant skills from resumes
- Compare resumes with a job description
- Rank candidates based on similarity score
- Identify matched and missing skills
- Generate recruiter-friendly recommendations

---

## 📂 Dataset

**Dataset Used:** Resume Dataset

The dataset contains resumes from multiple professional domains such as:

- Data Science
- Python Developer
- Java Developer
- HR
- DevOps
- Testing
- Business Analyst
- Web Designing
- Sales
- Mechanical Engineering
- And more...

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- Scikit-learn
- Joblib
- Google Colab

---

## 🧠 NLP Techniques

- Text Cleaning
- Lowercase Conversion
- Stopword Removal
- Punctuation Removal
- Number Removal
- Lemmatization
- TF-IDF Vectorization
- Cosine Similarity

---

## 🤖 Machine Learning Workflow

1. Load Resume Dataset
2. Clean Resume Text
3. Preprocess Text using NLP
4. Create TF-IDF Features
5. Compare Resume with Job Description
6. Calculate Similarity Score
7. Extract Skills
8. Detect Missing Skills
9. Rank Candidates
10. Generate Recommendations

---

## 💼 Features

- Resume Text Preprocessing
- AI-based Resume Screening
- Candidate Ranking
- Match Score Calculation
- Skill Extraction
- Missing Skill Detection
- Interactive Resume Screening
- Recruiter-Friendly Report

---

## 📊 Sample Output

### Input Job Role

```text
AI Engineer
```

### Candidate Result

```text
Match Score:
91.8%

Matched Skills
✔ Python
✔ Machine Learning
✔ TensorFlow
✔ SQL
✔ Pandas
✔ NumPy
✔ Git

Missing Skills
✖ Docker
✖ Kubernetes

Recommendation
⭐⭐⭐⭐⭐ Highly Recommended
```

---

## 📈 Project Workflow

```
Resume
        │
        ▼
Text Cleaning
        │
        ▼
NLP Preprocessing
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Cosine Similarity
        │
        ▼
Skill Extraction
        │
        ▼
Candidate Ranking
        │
        ▼
Recommendation
```

---

## 📁 Repository Structure

```text
FUTURE_ML_03
│
├── FUTURE_ML_03_Resume_Screening_System.ipynb
├── Resume.csv
├── Final_Candidate_Ranking.csv
├── tfidf_vectorizer.pkl
├── README.md
└── requirements.txt
```

---

## 📊 Business Impact

This project can help organizations:

- Reduce manual resume screening time
- Improve recruitment efficiency
- Identify qualified candidates quickly
- Detect missing skills automatically
- Support data-driven hiring decisions

---

## 🚀 Future Improvements

- Resume PDF Parsing
- Multiple Job Role Support
- Skill Weighting
- Resume Upload Interface
- Streamlit Web Application
- BERT-based Resume Matching
- Integration with ATS Platforms

---

## 👨‍💻 Author

**Shashikant Jha**

B.Tech CSE (AI & ML)

Machine Learning Intern – Future Interns

GitHub: https://github.com/shashikant237

# 🛡️ Scam Job Detection System

This project is a machine learning-based **Fraud Job Detection System** that helps identify whether a job posting is **real** or **fake**. The system analyzes job descriptions and related metadata to classify postings, protecting job seekers from potential scams.

## 📌 Features

- Binary classification: **Real** vs **Fake** job posts
- Natural Language Processing (NLP) on job descriptions
- Data cleaning and preprocessing
- Model training using classification algorithms
- Evaluation using accuracy, precision, recall, and F1 score
- Tested on the popular `fake_job_postings.csv` dataset

## 🧠 Model Capabilities

- Detects scam job postings with high accuracy
- Understands textual features like:
  - Job title
  - Location
  - Company profile
  - Job description
  - Required qualifications

## 🗂️ Dataset

- Dataset used: `fake_job_postings.csv`
- Fields include:
  - `title`, `location`, `department`, `salary_range`, `company_profile`, `description`, etc.
- Target column: `fraudulent` (1 = Fake, 0 = Real)

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- Libraries: Pandas, NumPy, Scikit-learn, NLTK / SpaCy, Matplotlib, Seaborn


# Fraud-Detection-System
A machine learning-based Scam Job Detection System that classifies job postings as real or fake using features from the job description and related fields. This helps prevent users from falling for fraudulent job advertisements.

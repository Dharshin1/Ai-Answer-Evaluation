# AI Answer Evaluation for Sustainable AI Systems 🌱

## 📘 Overview
This project focuses on developing an **AI Answer Evaluation system** that can automatically assess the correctness, relevance, and sustainability impact of AI-generated responses.  
It aims to support **responsible and efficient AI usage** by reducing manual evaluation effort and ensuring AI systems produce reliable, unbiased, and energy-efficient answers.

---

## 🎯 Objectives
- Automate evaluation of AI-generated answers using NLP-based techniques.
- Promote sustainable and ethical AI development.
- Reduce human effort and time in response validation.
- Build a foundation for AI models that align with responsible computing goals.

---

⚙️ Technologies Used

Python

Sentence Transformers (MiniLM)

Scikit-learn

Pandas / NumPy

Google Colab

GitHub for version control

📂 Repository Structure
Ai-Answer-Evaluation/
│
├── Final_Project_Notebook.ipynb      # One-cell complete training code
├── classifier.pkl                     # Trained ML model
├── ai_dataset.tsv                     # Clean QA dataset
├── README.md                          # Project description
└── PROJECT_REPORT.md                  # Full written report (optional)

🧠 How It Works

Convert AI answer + expected answer into embeddings

Generate similarity score

Feed similarity into Logistic Regression

Predict:

1 → Correct

0 → Incorrect

This model is extremely lightweight and runs fast → sustainable AI ✔.

📈 Model Performance

Sentence Transformer: all-MiniLM-L6-v2

Classifier: Logistic Regression

Achieved Accuracy: (paste your accuracy here)

🧪 Files Included
File	Purpose
Final_Project_Notebook.ipynb	Full training + evaluation pipeline
classifier.pkl	Saved trained model
ai_dataset.tsv	Clean training dataset
README.md	Documentation
🚀 Future Improvements

Build a complete website interface

Add more datasets for training

Deploy model as an API

Add sustainability scoring metrics

👩‍💻 Developer

Developed by Dharshini D
Course: Sustainable AI Project
2025

**GitHub Repository Link:**  
👉 [https://github.com/Dharshin1/Ai-Answer-Evaluation](https://github.com/Dharshin1/Ai-Answer-Evaluation)

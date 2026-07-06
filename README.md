# Auto Tagging Support Tickets Using LLM

## 📌 Project Overview

This project was developed as part of the **DevelopersHub Corporation AI/ML Engineering Advanced Internship – Task 5**.

The objective of this project is to automatically classify IT support tickets into the appropriate department and generate the **top 3 relevant tags** using a Large Language Model (LLM). The project compares **Zero-Shot Prompting** and **Few-Shot Prompting** techniques to evaluate the effectiveness of prompt engineering for text classification.

---

# 🎯 Objective

The main objectives of this project are:

* Automatically classify support tickets into the correct department.
* Generate the top 3 most relevant tags for each ticket.
* Compare Zero-Shot and Few-Shot prompting approaches.
* Evaluate classification performance using machine learning metrics.

---

# 📂 Dataset

**Dataset:** IT Support Ticket Data

The dataset contains real-world IT support tickets with the following columns:

* Body (Support Ticket Description)
* Department (Target Label)
* Priority
* Tags

The **Department** column is used as the ground-truth label for evaluation.

---

# 🛠️ Technologies Used

* Python
* Google Colab
* OpenAI API
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

# 🤖 Large Language Model

Model Used:

* GPT-4.1-mini

Techniques:

* Zero-Shot Prompting
* Few-Shot Prompting

---

# ⚙️ Project Workflow

### 1. Data Loading

* Loaded the IT Support Ticket dataset.
* Explored dataset structure and checked for missing values.

### 2. Data Preprocessing

* Selected the required columns.
* Sampled a subset of tickets for API-based evaluation.
* Cleaned prediction outputs before evaluation.

### 3. Zero-Shot Classification

The model classified support tickets without providing any examples.

Output:

* Predicted Department
* Top 3 Tags

### 4. Few-Shot Classification

The model was provided with example support tickets before making predictions.

Output:

* Predicted Department
* Top 3 Tags

### 5. Performance Evaluation

The predicted departments were compared with the actual departments using:

* Accuracy
* Classification Report
* Confusion Matrix

---

# 📊 Results

The model successfully classified IT support tickets and generated relevant tags using prompt engineering.

Observed Accuracy (Sample Evaluation):

* Zero-Shot Accuracy: **25%**
* Few-Shot Accuracy: **25%**

The results indicate that prompt engineering can effectively automate ticket classification. The performance is influenced by the dataset quality, ticket ambiguity, and overlap between department categories.

---

# 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# 📁 Project Structure

```
Task-5-Auto-Tagging-LLM/
│
├── Task5_Auto_Tagging.ipynb
├── IT Support Ticket Data.csv
├── predictions.csv
├── requirements.txt
├── README.md
└── images/
    ├── confusion_matrix.png
    └── accuracy_comparison.png
```

---

# 🚀 Features

* LLM-based Support Ticket Classification
* Zero-Shot Prompting
* Few-Shot Prompting
* Automatic Department Prediction
* Top 3 Tag Generation
* Performance Evaluation
* Export Predictions to CSV

---

# 💾 Output

The notebook generates:

* Department predictions
* Top 3 tags
* Prediction CSV file
* Evaluation metrics
* Visualizations

---

# 📌 Future Improvements

* Improve prompt engineering with more representative examples.
* Evaluate additional LLMs.
* Fine-tune an open-source language model for higher accuracy.
* Build a Streamlit web application for real-time ticket classification.
* Implement Retrieval-Augmented Generation (RAG) for knowledge-aware ticket routing.

---

# 🎓 Internship Task

**DevelopersHub Corporation**

**AI/ML Engineering Advanced Internship**

**Task 5 – Auto Tagging Support Tickets Using LLM**

---

# 👩‍💻 Author

**Gule Sakeena**

AI/ML Engineering Intern

DevelopersHub Corporation

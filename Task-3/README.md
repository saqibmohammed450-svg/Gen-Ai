# 📄 AI Resume Screening System using NLP & LLMs

## 📌 Project Overview

This project builds an **AI-powered Resume Screening System** that automatically analyzes resumes and matches them with job descriptions using **Natural Language Processing (NLP)** and **Large Language Models (LLMs)**.

The system helps streamline the recruitment process by identifying the most relevant candidates efficiently.

---

## 🎯 Objective

* Automate resume screening using AI
* Extract meaningful information from resumes
* Match candidate profiles with job requirements
* Improve hiring efficiency using NLP techniques

---

## 🛠️ Tech Stack

* Python 🐍
* LangChain 🔗
* OpenAI / Hugging Face 🤖
* NLP (Text Processing)
* Jupyter Notebook

---

## ⚙️ Key Features

* 📄 Resume parsing and text extraction
* 🧠 Skill and keyword identification
* 🎯 Job-description matching
* 📊 Scoring and ranking candidates
* 🔍 Tracing and debugging LLM responses

---

## 🔄 Workflow

```id="flow1"
Resume Input → Text Processing → Feature Extraction → LLM Analysis → Matching Score → Ranked Output
```

---

## 🚀 Implementation Steps

### 1️⃣ Data Input

* Load resumes (PDF/Text)
* Input job description

### 2️⃣ Preprocessing

* Clean and normalize text
* Tokenization

### 3️⃣ LLM Integration

* Use LangChain for structured prompts
* Analyze resume content

### 4️⃣ Matching Logic

* Compare skills with job requirements
* Generate similarity score

### 5️⃣ Output

* Rank candidates based on relevance

---

## 💻 Example Code Snippet

```python id="code1"
from langchain.llms import OpenAI

llm = OpenAI()

response = llm("Analyze this resume and match it with the job description")
print(response)
```

---

## 🧠 Key Learnings

* Practical use of LLMs in real-world applications
* Importance of prompt engineering
* Workflow design using LangChain
* Handling unstructured text data

---

## ⚠️ Limitations

* Dependent on resume quality
* May miss context in complex resumes
* Requires fine-tuning for higher accuracy

---

## 🚀 Future Improvements

* Add PDF parsing support
* Use embeddings for better matching
* Build a web interface (Streamlit)
* Deploy as a hiring assistant API

---

## 👨‍💻 Author

**Mohammed Saqib**

---

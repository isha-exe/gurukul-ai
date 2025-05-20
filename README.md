# 📚 Gurukul AI

> Building a responsive, AI-powered educational platform tailored for the Indian school system.

![Gurukul AI Banner](https://github.com/isha-exe/gurukul-ai/blob/main/logo.png)

---

## 🎥 Demo Video

Watch a walkthrough of Gurukul AI in action:

👉 [Watch Demo](https://github.com/isha-exe/gurukul-ai/blob/main/gurukul.mp4)

---

## 🚀 Overview

**Gurukul AI** is an open-source initiative designed to enhance school education in India using state-of-the-art AI techniques. It leverages large language models (LLMs), retrieval-augmented generation (RAG), and curated curriculum-aligned datasets to provide accurate, personalized, and accessible educational support for students.

The platform supports:
- Curriculum-based question answering (CBSE, NCERT-aligned)
- Multilingual inputs (English and Hindi)
- Subject-wise and chapter-wise practice tools
- AI-generated and curated datasets for QA and MCQs
- Fine-tuned LLaMA models for improved performance in education

---

## 🧠 Key Features

- ✅ **Fine-tuned LLaMA 3.1 8B** on curriculum-specific QA data
- ✅ **RAG-based retrieval** for contextual answering from textbooks
- ✅ **MCQ Practice Tool** with class, subject, and chapter filters
- ✅ **Support for Hindi & English**
- ✅ **Interactive Chatbot Interface** for students
- ✅ **Evaluation with ROUGE & semantic similarity**
- ✅ **Robustness to typos and informal queries**

---

## 📦 Dataset Sources

We use structured and semi-structured datasets:
- Textbook-derived content (NCERT, CBSE)
- Past year questions (PYQs)
- Model answers curated by educators
- Bilingual content (Hindi-English)

Dataset types:
- `QA` (question-answer pairs)
- `MCQ` (multiple-choice questions with explanations)
- `Chapters` (indexed for retrieval)

> Note: Full proprietary datasets are kept in the private repository. This public repo contains sanitized examples and formats.

---

## 🔧 Technologies Used

| Component          | Tech Stack                        |
|--------------------|-----------------------------------|
| Model              | LLaMA 3.1 8B + LoRA (Unsloth)     |
| Embeddings         | sentence-transformers    |
| Retrieval          | FAISS                            |
| Reranking          | BAAI/bge-reranker-base            |
| Backend            | Flask (Python)                    |
| Frontend           | HTML, JS, Bootstrap (Simple UI)   |
| Evaluation         | ROUGE, Cosine Similarity (BGE)    |

---

## 🧪 Evaluation

We evaluate model performance using:
- 🧾 **ROUGE scores** for content overlap
- 🔍 **Semantic similarity** using BGE-M3 embeddings
- 📊 **Ablation studies** for:
  - Pretrained vs fine-tuned
  - With vs without RAG
  - Robustness to typos and informal language

> A curated test set of 700+ real exam questions across subjects is used for evaluation.

---

## 🌐 Gurukul AI Portal

Try the web interface here:  
🔗 [https://lingo.iitgn.ac.in/gurukulai/home](https://lingo.iitgn.ac.in/gurukulai/home)

Key components:
- **Ask a Question**: Chatbot-style QA interface
- **Practice Portal**: Filter by class, subject, chapter
- **Feedback Collection**: Improve QA via student responses



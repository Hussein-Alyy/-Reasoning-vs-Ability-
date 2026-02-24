# 🧠 Advanced Sentiment Analysis with Gemini (Reasoning vs Direct Comparison)

An AI-powered sentiment analysis experiment that compares:

* 🔎 **Reasoning-based classification**
* ⚡ **Direct classification**
* 🤖 Using Google Gemini
* 📊 With full evaluation & confusion matrix
* 🌍 Handling mixed Arabic/English texts
* 😏 Detecting sarcasm & idioms

---

## 📌 Project Overview

This project evaluates Large Language Model performance on complex sentiment tasks including:

* Sarcasm detection
* Mixed-language text (Arabic + English)
* Idioms and figurative expressions
* Conflicting emotions
* Real-world noisy data

Two approaches were tested:

### 1️⃣ Reasoning Task

The model:

* Identifies emotional triggers
* Detects sarcasm
* Explains sentiment reasoning
* Outputs structured JSON

### 2️⃣ Direct Task

The model:

* Classifies sentiment directly
* Returns only label (Positive / Negative / Neutral)

---

## 📊 Dataset

* 60 challenging multilingual samples
* Contains:

  * Sarcasm
  * Mixed Arabic-English text
  * Idiomatic expressions
  * Realistic user reviews
* Designed to stress-test LLM reasoning ability

---

## 🛠️ Technology Stack

* Python
* Google Gemini (`gemini-2.5-flash`)
* LangChain
* Pandas
* JSON processing
* Streamlit-ready structure (optional extension)

---

## 🧠 Model Configuration

* Temperature: 0 (deterministic outputs)
* Output format: Strict JSON
* No markdown allowed in responses
* Structured prompt engineering

---

## 🔬 Evaluation Method

After generating predictions from both approaches:

* Results were stored as JSON
* Converted to DataFrames
* Compared using:

  * Cross-tabulation (Confusion Matrix)
  * Visual comparison
  * Direct label alignment

---

## 📉 Results Summary

### 🔹 Reasoning Task

* High-quality explanations
* Detected sarcasm correctly
* Strong contextual understanding
* Produces structured analytical output

### 🔹 Direct Task

* Accurate classification
* Faster inference
* Simple sentiment labels

---

## 📊 Confusion Matrix Result

The comparison showed strong alignment between both methods, with consistent sentiment predictions across samples.

This confirms:

* Stability of the model
* Reliability of structured prompting
* Strong performance on complex multilingual data

---

## 🎯 Key Highlights

* Comparative LLM evaluation
* Sarcasm-aware sentiment testing
* Multilingual robustness
* Structured output validation
* Production-style prompt engineering
* JSON enforcement strategy

---

## 🚀 Use Cases

* Social media sentiment analysis
* Customer review analysis
* Brand monitoring
* Multilingual NLP systems
* LLM benchmarking
* AI evaluation research

---

## 🔮 Future Improvements

* Add traditional ML baseline (TF-IDF + SVM)
* Add transformer fine-tuned model comparison
* Compute full metrics (Accuracy, Macro-F1)
* Add automated evaluation pipeline
* Extend dataset size
* Deploy as interactive dashboard

---

## 📁 Project Structure

```id="proj1"
sentiment-evaluation/
│
├── analysis_notebook.ipynb
├── reasoning_results.json
├── ability_results.json
├── evaluation_metrics.py
└── README.md
```

---

## 🏆 Project Value

This project demonstrates:

* Advanced prompt engineering
* Structured LLM outputs
* Comparative model evaluation
* Handling of real-world noisy text
* Reasoning vs direct inference analysis

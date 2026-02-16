# 🤖 AI-Powered Learning Path Analyzer

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Gemini AI](https://img.shields.io/badge/Powered%20By-Google%20Gemini-orange.svg)](https://ai.google.dev/)

An advanced career-tech tool that bridges the gap between your current resume and your dream job. This application uses a hybrid approach: **TF-IDF Vectorization** for statistical keyword matching and **Google Gemini 1.5** for semantic intelligence.

---

## 🌟 Key Features

* **Dual-Layer Analysis:** * *Statistical:* Uses Scikit-learn to calculate a baseline compatibility score.
    * *Semantic:* Uses Gemini AI to understand the context of your experience versus job requirements.
* **Skill-Project Verification:** Automatically ranks your skills based on how often they appear in your "Projects" or "Work History" to verify practical application.
* **Dynamic Visualization:** Generates a **Simulated Density Curve** using `Matplotlib` to visualize where your profile sits in the relevance distribution.
* **AI Career Coach:** Returns a structured **5-step actionable learning path** to bridge identified skill gaps.
* **Automated Parsing:** Extracts contact information (Name, Email, Phone) and specific resume sections using Regex and NLTK.

---

## 🛠️ Tech Stack

* **Frontend:** [Streamlit](https://streamlit.io/)
* **AI Model:** [Google Gemini API](https://ai.google.dev/)
* **Natural Language Processing:** [NLTK](https://www.nltk.org/), [Scikit-learn](https://scikit-learn.org/)
* **PDF Processing:** [PyPDF2](https://pypi.org/project/PyPDF2/)
* **Data & Plotting:** [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/)

---

## 🚀 Getting Started

### 1. Prerequisites
* Python 3.9 or higher.
* A Google Gemini API Key. [Get it here](https://aistudio.google.com/).

### 2. Installation
```bash
# Clone the repository
git clone [https://github.com/your-username/ai-learning-path-analyzer.git](https://github.com/your-username/ai-learning-path-analyzer.git)
cd ai-learning-path-analyzer

# Install dependencies
pip install -r requirements.txt

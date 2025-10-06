# IntelliCode: AI-Powered Python Optimizer & Explainer

[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## 🚀 Overview

**IntelliCode** is a Google Colab project that leverages **Google Gemini AI** to help Python developers:

- Understand their code with **beginner-friendly explanations**  
- Optimize code with **Pythonic, efficient rewrites**  
- Analyze **time and space complexity**  
- Compare original vs optimized code clearly  

It is designed for rapid code insights, teaching, and productivity improvement.

---

## ⚡ Features

- **Static code analysis**: Lines, functions, loops, recursion, and imports  
- **Automated optimization**: Improved readability, performance, and maintainability  
- **Complexity insights**: Big-O analysis with detailed explanations  
- **Interactive Colab notebook**: No local setup required  
- **Supports single or multiple Python files**  

---

## 🛠️ Getting Started

### Prerequisites

1. Google account (for Colab)  
2. **Gemini API key** from [Google Generative AI](https://developers.generativeai.google/)

### Steps

1. Open the Colab notebook: [Link to your notebook]  
2. Add your `GEMINI_API_KEY` in Colab Secrets (Sidebar → Secrets)  
3. Run the notebook  
4. Upload your Python file(s)  
5. Receive explanations, optimizations, and complexity analysis  

---

## 📝 Example

**Original code:**

```python
def is_palindrome(s):
    return s == s[::-1]

print(is_palindrome("racecar"))

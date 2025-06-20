# 💡 Gemini API Healthcare Demo

This Jupyter notebook demonstrates how to use the `google-generativeai` Python SDK to interact with **Gemini 1.5 Flash** and generate useful content for healthcare machine learning scenarios.

## 🔍 What It Does
- Connects to the Gemini API via Python
- Sends a prompt asking to summarize the role of ML in healthcare
- Prints a structured, markdown-style answer suitable for reports, posts, or presentations

## 📂 Files Included
- `gemini_healthcare_demo.ipynb`: Jupyter notebook to run and modify
- `README.md`: This file

## 🚀 How to Use

1. Clone this repo or download the notebook
2. Install dependencies in your virtual environment:
   ```bash
   pip install --break-system-packages google-generativeai
   ```
3. Open the notebook:
   ```bash
   jupyter lab
   ```
4. Replace the placeholder `your-api-key-here` with your [Gemini API key](https://makersuite.google.com/app/apikey)
5. Run all cells

## 📌 Notes
- The notebook uses `gemini-1.5-flash`, which has more generous free-tier limits than `gemini-1.5-pro`

## 🧠 Prompt Example

> Summarize the role of machine learning in healthcare.

Enjoy building with GenAI!

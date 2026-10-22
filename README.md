# Mental Health Score (Mansik-Santulan-Score)

An interactive Machine Learning web application that predicts a student's mental health score based on social media usage patterns, study habits, physical activity, sleep, and stress levels.

## 📌 Project Overview

- **Machine Learning**: Model trained on student social media impact dataset (`ML_Project.ipynb`), exported to `Mental_Health_Model.pkl`.
- **Backend API**: Built with **FastAPI** (`main.py`) providing a `/predict` endpoint validated using Pydantic.
- **Frontend**: Clean and responsive web interface (`index.html`, `style.css`, `script.js`) allowing students to input lifestyle metrics and view their predicted mental health score in real-time.

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python 3.8+ installed.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the FastAPI Backend
```bash
uvicorn main:app --reload
```
The server will start at `http://127.0.0.1:8000`.

### 4. Open the Web Frontend
Open `index.html` in your browser (or use Live Server). Enter your lifestyle and study metrics to get your predicted mental health score!

---

## 📁 Repository Structure

```text
├── index.html                                      # Frontend interface
├── style.css                                       # Frontend styling
├── script.js                                       # Frontend API integration logic
├── main.py                                         # FastAPI server & prediction endpoint
├── Mental_Health_Model.pkl                         # Trained Scikit-Learn model
├── ML_Project.ipynb                                # Data analysis & model training notebook
├── ML Project.html                                 # Exported notebook HTML
├── Student Social Media And Mental Health Impact.csv # Dataset
├── requirements.txt                                # Python dependencies
└── .gitignore                                      # Ignored files (pycache, etc.)
```

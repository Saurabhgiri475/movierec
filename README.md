# 🎬 AI Movie Recommendation System

A full-stack Machine Learning web application that recommends movies using content-based filtering and real-time data from the TMDB API.

🌐 **Live Demo:**  
https://movierec-1-98sh.onrender.com/

---

## 🚀 Project Overview

This project is a Content-Based Movie Recommendation System built using TF-IDF similarity.

Users can:
- Search for movies
- View movie posters and details
- Get intelligent recommendations based on content similarity

The system is fully deployed on the cloud and accessible from any device.

---

## 🧠 Features

- 🔍 Movie search functionality
- 🎯 Content-based recommendations (TF-IDF model)
- 🖼 Movie posters & metadata using TMDB API
- ⚡ FastAPI backend (REST API)
- 🎨 Interactive Streamlit frontend
- ☁ Cloud deployment using Render
- 🔄 Automatic deployment from GitHub

---

## 🏗 System Architecture

User (Browser)  
↓  
Streamlit Frontend  
↓  
FastAPI Backend  
↓  
TF-IDF Model + TMDB API  

---

## 🛠 Tech Stack

- Python
- Scikit-learn
- FastAPI
- Streamlit
- TMDB API
- Git & GitHub
- Render (Cloud Deployment)

---

## 📂 Project Structure

```
movierec/
│
├── app.py                  # Streamlit frontend
├── main.py                 # FastAPI backend
├── requirements.txt        # Project dependencies
├── df.pkl                  # Movie dataset
├── tfidf_matrix.pkl        # TF-IDF matrix
├── indices.pkl             # Movie index mapping
├── movies_metadata.csv     # Raw dataset
├── .gitignore
└── README.md
```

---

## ⚙ How To Run Locally

### 1️⃣ Clone Repository

```
git clone https://github.com/Saurabhgiri475/movierec.git
cd movierec
```

### 2️⃣ Create Virtual Environment

Windows:
```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Add TMDB API Key

Create a file named `.env` and add:

```
TMDB_API_KEY=your_api_key_here
```

### 5️⃣ Run Backend

```
uvicorn main:app
```

### 6️⃣ Run Frontend

```
streamlit run app.py
```

---

## ☁ Deployment

This project is deployed on **Render Cloud Platform**.

Every push to the `main` branch automatically triggers a redeployment.

Live App:
https://movierec-1-98sh.onrender.com/

---

## 🎓 Academic Purpose

Developed as a Major Project to demonstrate:

- Machine Learning model implementation
- Model deployment
- REST API development
- Full-stack application architecture
- Cloud deployment
- DevOps basics

---

## 👨‍💻 Author

**Saurabh Giri**  
Babu Banarasi Das Northern India Institute of Technology  
Artificial Intelligence Enthusiast | Python Developer | ML Learner  

GitHub: https://github.com/Saurabhgiri475

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
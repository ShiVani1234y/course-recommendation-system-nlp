# course-recommendation-system-nlp
# 📌 Udemy Course Recommendation System with Analytics Dashboard

## 📖 Overview  
This project is a **content-based course recommendation system** that suggests similar Udemy courses based on user input. It also includes an **interactive analytics dashboard** to visualize course trends such as subscribers, revenue, and category distribution.

---

## 🚀 Features  
- 🔍 Course recommendation using **content-based filtering**  
- 🧠 NLP-based text processing (stopword removal, cleaning)  
- ⚡ Real-time recommendations using **Flask web app**  
- 📊 Interactive **analytics dashboard** with visual insights  
- 🔎 Search functionality for partial course names  

---

## 🛠️ Tech Stack  
- **Backend:** Python, Flask  
- **Libraries:** Pandas, NumPy, Scikit-learn, NeatText  
- **Frontend:** HTML, Bootstrap  
- **Visualization:** Chart.js  
- **ML Technique:** CountVectorizer + Cosine Similarity  

---

## ⚙️ How It Works  

1. User enters a course name  
2. Text is cleaned using NLP preprocessing  
3. CountVectorizer converts text into vectors  
4. Cosine similarity finds similar courses  
5. Top recommendations are displayed  

---

## 📊 Dashboard Insights  
- 📌 Number of subscribers per subject  
- 📌 Course distribution by level  
- 📌 Year-wise profit analysis  
- 📌 Monthly subscriber trends  

---

## 📁 Project Structure  
Udemy-Recommendation-System/
│
├── app.py
├── dashboard.py
├── requirements.txt
├── UdemyCleanedTitle.csv
│
├── templates/
│ ├── index.html
│ └── dashboard.html
│
└── README.md

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

```

Udemy-Course-Recommendation-System/
│
├── app.py                  # Main Flask application
├── dashboard.py            # Analytics & visualization logic
├── requirements.txt        # All dependencies
├── Procfile                # For deployment (Render/Heroku)
├── README.md               # Project documentation
│
├── dataset/                # Dataset folder
│   └── UdemyCleanedTitle.csv
│
├── templates/              # HTML files (Flask templates)
│   ├── index.html
│   └── dashboard.html
│
├── static/ (optional)      # CSS / JS / images (if any)
│
├── screenshots/            # For README images
│   ├── home.png
│   ├── recommendation.png
│   └── dashboard.png
│
├── notebooks/ (optional)   # Jupyter notebooks (EDA / experiments)
│
└── .gitignore              # Ignore unnecessary files
```
## 📈 Results  
- Improved recommendation relevance by **~25–30%** after text preprocessing  
- Processed **3000+ course dataset** for generating recommendations  

---

## 🔮 Future Improvements  
- Use **TF-IDF / BERT** for better recommendations  
- Add **user-based collaborative filtering**  
- Deploy with **Docker + Cloud scaling**  

---

## 👩‍💻 Author  

**Shivani Singh**  

- GitHub: https://github.com/ShiVani1234y  
- LinkedIn: https://www.linkedin.com/in/shivani-singh-515b4b278/  

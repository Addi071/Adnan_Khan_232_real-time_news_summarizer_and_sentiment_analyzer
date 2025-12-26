```md
# 📰 Real-Time News Analysis and Summarization System

## 📌 Project Overview
In the modern digital age, users are exposed to a massive amount of news every day through online platforms, social media, and discussion forums like Reddit. This often leads to information overload, difficulty in identifying reliable news, and the spread of misinformation or fake news.

The **Real-Time News Analysis and Summarization System** is designed to solve these challenges by using **Artificial Intelligence (AI)** and **Natural Language Processing (NLP)** techniques. The system automatically fetches news from multiple sources, analyzes it, and provides intelligent insights such as summaries, sentiment, fake news detection, and trending keywords. This helps users decide **whether an article is worth reading, should be verified, or should be avoided**.

---

## 🎯 Objectives of the Project
- Fetch real-time news from News APIs and Reddit  
- Summarize long news articles into short, meaningful content  
- Detect whether news is **fake or real** using machine learning models  
- Analyze sentiment (positive, negative, neutral) of news content  
- Extract important keywords and identify trending topics by category  
- Store news data in MongoDB for daily trend analysis  
- Visually display keyword trends using charts in the frontend  

---

## 🛠️ Tech Stack Used

### Frontend
- React.js  
- Chart.js (for keyword trend visualization)  
- HTML, CSS, JavaScript  

### Backend
- Flask (Python)  
- REST APIs  
- Flask-CORS  

### AI / NLP Models
- Fake News Detection (BERT-based model)  
- Text Summarization (BART model)  
- Sentiment Analysis (VADER)  
- Keyword Extraction (KeyBERT)  

### Database
- MongoDB (NoSQL database)

---

## 🔄 System Workflow
```

Frontend (React)
↓
Backend (Flask API)
↓
AI Models (Fake News, Summarization, Sentiment, Keywords)
↓
MongoDB Database

````

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/real-time-news-analysis.git
cd real-time-news-analysis
````

### 2️⃣ Backend Setup (Flask)

```bash
cd flask-backend
python -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

### 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

### 4️⃣ MongoDB Setup

* Install MongoDB locally **or** use MongoDB Atlas
* Create a database named `news_db`
* Create a collection named `news`
* Update MongoDB connection string in backend code

---

## 🚀 How to Use the System

1. Open the website in your browser
2. Select a news category (Home, Trending, World, Sports, Technology, Movies)
3. View real-time news fetched from APIs and Reddit
4. Click on any article to see:

   * Summary
   * Fake/Real news detection result
   * Sentiment analysis
   * Recommendation (Read / Caution / Do Not Read)
5. View trending keywords displayed as bar graphs
6. Explore how topics trend over time based on stored data

---

## 📊 Key Features

* ✅ Real-time news fetching
* ✅ AI-powered summarization
* ✅ Fake news detection
* ✅ Sentiment analysis
* ✅ Keyword extraction & trend analysis
* ✅ MongoDB-based data storage
* ✅ Graphical trend visualization

---

## 📌 Conclusion

This project successfully addresses the problem of information overload and misinformation in digital news consumption. By integrating AI and NLP techniques, the system transforms raw news data into meaningful insights that are easy to understand and trust.

The platform helps users save time, avoid fake news, understand sentiment, and stay updated with trending topics. Overall, the **Real-Time News Analysis and Summarization System** provides a smarter, safer, and more efficient way to consume news in today’s fast-paced digital world.

---

## 👨‍💻 Developed By

**Adnan Khan**
**Suhas Dube**
**Aniket Nagre**
**Ganesh Kalapad**
Third Year Computer Science Engineering
MGM’s College of Engineering, Nanded

---

## 📜 License

This project is developed for academic purposes and is open for learning and enhancement.

```
```

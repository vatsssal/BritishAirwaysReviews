# British Airways Reviews Analysis 🛫

This project focuses on **scraping, processing, and analyzing customer reviews** of British Airways from **AirlineQuality.com**. The analysis includes **data cleaning, sentiment classification, and various visualizations** to uncover insights about passenger experiences.

---

## 📌 Project Overview

- **Data Source:** [Airline Quality - British Airways Reviews](https://www.airlinequality.com/airline-reviews/british-airways/)
- **Objective:** To **scrape and analyze** customer reviews, determine sentiment, and visualize patterns over time.
- **Tech Stack:**
  - **Web Scraping:** `requests`, `BeautifulSoup`
  - **Data Processing:** `pandas`, `numpy`
  - **Visualization:** `matplotlib`, `seaborn`, `wordcloud`
  - **Notebook Environment:** Jupyter Notebook (`.ipynb`)

---

## 📂 Project Structure

📁 British_Airways_Review_Analysis  
│-- 📜 british_airways_reviews.ipynb  # Jupyter Notebook for scraping & analysis  
│-- 📜 british_airways_reviews.csv    # Scraped data in CSV format  
│-- 📜 README.md                       # Project documentation (this file)  

---

## 🔍 Features & Analysis

✅ **Web Scraping:**  
- Scrapes **393 pages** of British Airways reviews.  
- Extracts **review text, reviewer name, rating, seat type, and date**.  

✅ **Data Preprocessing:**  
- Handles missing values and standardizes date formats.  
- Cleans **"Verified"** and **"Non-Verified"** review tags.  

✅ **Sentiment Analysis:**  
- Classifies reviews as **Positive, Neutral, or Negative** based on star ratings.  
- Counts **Verified vs. Non-Verified** reviews.  

✅ **Data Visualization:**  
- **Star Rating Distribution** (Histogram).  
- **Sentiment Breakdown** (Count Plot).  
- **Review Trends Over Time** (Line Chart).  
- **Seat Type vs. Ratings** (Box Plot & Heatmap).  
- **Word Clouds** for Positive & Negative Reviews.  

---

## 📊 Example Visualizations  

### ⭐ Star Rating Distribution  
A histogram showing how customer ratings are distributed.  

### 📅 Average Rating Over Time  
A line chart comparing **Verified vs. Non-Verified** ratings by month.  

### 🪑 Seat Type Sentiment Analysis  
A bar chart and heatmap analyzing **review sentiment by seat type**.  

### ☁️ Word Clouds  
Generated **word clouds** for positive and negative reviews.

---

## 🛠 How to Run This Project  

1️⃣ **Clone the Repository**  

git clone https://github.com/vatsssal/BAreviews.git


2️⃣ **Install Dependencies**  

pip install -r requirements.txt



3️⃣ **Open Jupyter Notebook**  

4️⃣ **Run `BAreviews.ipynb`** step by step.

---

## 📌 Dependencies  

Ensure you have the following Python libraries installed:  

pip install requests beautifulsoup4 pandas numpy matplotlib seaborn wordcloud


---

## 📜 License  

This project is **open-source** and free to use.

---

## 🤝 Contributing  

Feel free to **fork the repo** and contribute! If you find any issues, open a pull request. 😊  

---

## 📬 Contact  

If you have any questions, feel free to reach out:  
📧 Email: vatsssal@gmail.com
---

🚀 **Happy Coding & Data Crunching!** 🚀

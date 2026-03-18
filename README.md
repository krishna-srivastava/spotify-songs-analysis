# 🎧 Spotify Songs EDA (2023)

## 📊 Project Overview
This project performs Exploratory Data Analysis (EDA) on a Spotify songs dataset to understand the key factors that influence song popularity.

---

## 🎯 Objectives
- Identify patterns behind high-performing (hit) songs  
- Analyze the impact of playlists and charts  
- Understand how audio features affect popularity  
- Detect viral and overhyped songs  

---

## 🧹 Data Cleaning & Preparation
- Converted columns to appropriate data types  
- Handled missing values using mean/mode  
- Created a unified `release_date` column  
- Processed multiple artists using split & explode  
- Feature engineering:
  - `total_playlist`
  - `total_chart`
  - `dance_bucket`

---

## 📈 Key Analysis

### 🔹 Popularity Analysis
- Top & bottom songs based on streams  
- Streams distribution  

### 🔹 Artist Analysis
- Top artists by total streams  
- Solo vs collaboration comparison  

### 🔹 Time Analysis
- Songs released per year  
- Year-wise stream trends  

### 🔹 Platform Analysis
- Playlist & chart presence across platforms  
- Correlation with streams  

### 🔹 Audio Features Analysis
- Danceability, energy, valence, BPM impact  
- Feature-based grouping  

### 🔹 Advanced Insights
- Viral songs (high streams, low playlists)  
- Overhyped songs (low streams, high playlists)  
- Correlation heatmaps  

---

## 🔥 Key Insights
- High danceability & energy songs tend to perform better  
- Collaborations often have higher average streams  
- Playlist presence boosts visibility but doesn’t guarantee success  
- Some songs go viral organically  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🚀 Conclusion
Song success depends on both platform exposure and audio characteristics.

---

## 📂 Dataset
Spotify Songs Dataset (2023)

---

## 💡 Author
Krishna Srivastava

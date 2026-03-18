🎧 Spotify Songs EDA (2023)

📊 Project Overview:
This project performs Exploratory Data Analysis (EDA) on a Spotify songs dataset to understand the key factors that influence song popularity.

The analysis focuses on:
Streams (popularity)
Platform presence (Spotify, Apple, Deezer, Shazam)
Audio features (danceability, energy, BPM, etc.)
Artist patterns and release trends

🎯 Objectives:
Identify patterns behind high-performing (hit) songs
Analyze the impact of playlists and charts
Understand how audio features affect popularity
Detect viral and overhyped songs

🧹 Data Cleaning & Preparation:
Converted columns to appropriate data types
Handled missing values using mean/mode
Created a unified release_date column
Processed multiple artists using split & explode
Engineered new features:
total_playlist
total_chart
dance_bucket

📈 Key Analysis Performed:
🔹 1. Popularity Analysis
Top & bottom songs based on streams
Distribution of streams

🔹 2. Artist Analysis
Top artists by total streams
Solo vs Collaboration comparison
Artist-wise performance trends

🔹 3. Time-Based Analysis
Songs released per year
Year-wise stream trends

🔹 4. Platform Analysis
Playlist and chart presence across platforms
Correlation between playlists/charts and streams
Multi-platform impact on song success

🔹 5. Audio Feature Analysis
Relationship between streams and:
Danceability
Energy
Valence
BPM
Feature bucketing for deeper insights

🔹 6. Advanced Insights
Identified viral songs (high streams, low playlist presence)
Identified overhyped songs (high playlist presence, low streams)
Correlation heatmaps for feature relationships

🔥 Key Insights:
Songs with higher danceability and energy tend to perform better
Collaborations often achieve higher average streams than solo songs
Playlist presence strongly correlates with streams, but does not guarantee success
Some songs go viral organically without heavy platform promotion
Both platform exposure and audio characteristics influence popularity

🛠️ Tech Stack
Python 🐍
Pandas
Matplotlib
Seaborn

🚀 Conclusion:
This analysis shows that while platform exposure increases visibility, the audio characteristics and audience preferences ultimately determine whether a song becomes a hit.

📌 Future Improvements:
Apply Machine Learning models for prediction
Build a recommendation system
Perform genre-based analysis

📂 Dataset:

Spotify Songs Dataset (2023)

💡 Author:

Krishna Srivastava

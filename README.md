# EDA---Spotify-Data-Popular-Hip-hop-Artists-and-Tracks-
🎧 Exploratory Data Analysis of Spotify data focused on popular Hip-hop artists and tracks — uncovering trends in popularity, audio features, and listener behavior in the Hip-hop genre.

This project presents an **Exploratory Data Analysis (EDA)** of a curated Spotify dataset focused on the most celebrated **Hip-hop artists and tracks**. The dataset comprises approximately **500 entries**, offering a deep dive into the **trends, popularity, and collaboration patterns** shaping the hip-hop music landscape.

---

## 📁 Dataset Overview

The dataset titled **"Spotify Data: Popular Hip-hop Artists and Tracks"** provides valuable insight into the musical and cultural dynamics of hip-hop. It includes track-level and artist-level information, capturing how **global listeners engage with the genre**.

### 📌 Features:

- **Artist**: The performer or creator of the track.
- **Track Name**: Title of the hip-hop song.
- **Popularity**: Numeric score (0–100) representing how well-received the track is among Spotify users.
- **Duration (ms)**: The full length of the track in milliseconds.
- **Track ID**: Spotify’s unique identifier for referencing and further exploration.

---

## 🎯 Project Objectives

- Analyze the **popularity dynamics** of hip-hop tracks over recent years.
- Identify **top-performing artists** and their characteristics.
- Explore **track-level audio features** (if available) such as duration trends.
- Visualize **collaborative patterns** among hip-hop artists.
- Lay the foundation for **predictive modeling** (e.g., predicting track popularity).

---

## 🧰 Tools & Libraries Used

- **Python 3.x**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** & **Seaborn** – static visualizations
- **Plotly / NetworkX (optional)** – interactive and network graphs
- **Jupyter Notebook** – for iterative exploration

---

## 🔍 EDA Workflow

1. **Data Cleaning**
   - Standardizing column names
   - Removing duplicates or missing entries
   - Formatting track durations

2. **Univariate Analysis**
   - Distribution of popularity scores
   - Track length comparisons

3. **Bivariate & Multivariate Analysis**
   - Correlation between popularity and duration
   - Artist frequency and repeated appearances

4. **Collaborative Network (Optional)**
   - Using artist collaborations to create a network graph

5. **Visualization**
   - Bar charts, heatmaps, histograms, and scatter plots

---

## 📊 Sample Insights

- Artists with frequent collaborations tend to have higher cumulative popularity.
- Most top hip-hop tracks fall within a specific duration range (~2.5 to 4 minutes).
- A handful of artists dominate the top tracks list, indicating genre influence.

---

## 📁 Project Structure

spotify-hiphop-eda/
│
├── data/ # Original and cleaned dataset
├── notebooks/ # Jupyter Notebook with EDA
│ └── Spotify_HipHop_EDA.ipynb
├── images/ # Charts and plots (optional)
├── README.md # Project documentation
└── requirements.txt # Python dependencies (optional)

yaml
Copy
Edit

---

## 🚀 Future Work

- Integrate Spotify's Web API to enrich the dataset with audio features (e.g., tempo, danceability)
- Perform sentiment analysis on lyrics (if available)
- Build predictive models to estimate popularity based on track metadata

---

## 📚 References

- Dataset Source: *Kaggle / Spotify Curated Dataset*  
  *(Insert the dataset link if public)*  
- Spotify API documentation: https://developer.spotify.com/

---

## 👨‍🎤 Author

**[Aditya Kumar]**  
Production Planner | Aspiring Data Analyst  

---

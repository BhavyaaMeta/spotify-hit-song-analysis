# 🎵 The Anatomy of a Hit Song

A data-driven analysis of 114,000 Spotify tracks to explore whether audio features influence song popularity.

## 📌 Project Overview

This project analyzes Spotify song data using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The objective was to investigate whether characteristics such as danceability, energy, loudness, tempo, acousticness, and genre have any significant relationship with a song's popularity.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📊 Dataset

The dataset contains approximately **114,000 Spotify tracks** and includes:

* Track popularity
* Danceability
* Energy
* Loudness
* Tempo
* Acousticness
* Instrumentalness
* Valence
* Genre
* Explicit content indicator
* Other audio-related features

---

## 🔍 Analysis Performed

### 1. Data Cleaning

* Removed unnecessary columns
* Handled missing values
* Corrected data type inconsistencies

### 2. Exploratory Data Analysis (EDA)

* Dataset overview
* Summary statistics
* Popularity distribution analysis

### 3. Correlation Analysis

* Examined relationships between popularity and audio features
* Generated a correlation matrix and heatmap

### 4. Explicit vs Non-Explicit Songs

* Compared average popularity of songs containing explicit lyrics versus non-explicit songs

### 5. Genre Analysis

* Identified the most popular genres
* Identified the least popular genres

### 6. Top Songs vs Low Popularity Songs

* Compared audio characteristics of highly popular and less popular tracks

---

## 📈 Visualizations

### Popularity Distribution

<img width="1420" height="866" alt="image" src="https://github.com/user-attachments/assets/e950e8f0-9f2f-4481-85ed-4c30db82d84f" />


### Correlation Heatmap

<img width="1422" height="1200" alt="image" src="https://github.com/user-attachments/assets/da2847a7-559e-42de-8f93-9d81cf535ca8" />


### Top 10 Genres by Average Popularity

<img width="1420" height="978" alt="image" src="https://github.com/user-attachments/assets/be8fa60f-de4d-44eb-9225-18462426c85b" />

### Top Songs vs Low Popularity Songs Comparison

<img width="1352" height="948" alt="image" src="https://github.com/user-attachments/assets/94e506e9-4340-4cce-90cd-5138c9231389" />


---

## 💡 Key Findings

* Popularity showed only weak correlations with individual audio features.
* Instrumentalness had the strongest negative relationship with popularity.
* Loudness showed a slight positive relationship with popularity.
* Genre appeared to influence popularity more than individual audio characteristics.
* Explicit and non-explicit songs showed differences in average popularity.
* Audio features alone cannot fully explain why a song becomes popular.

---

## 🎯 Conclusion

The analysis suggests that there is no single audio feature that guarantees a song's success.

While certain characteristics show weak relationships with popularity, factors beyond audio features—such as artist popularity, marketing, playlist placement, social media influence, and listener trends—likely play a major role in determining a song's overall success.

---

## 🚀 Future Improvements

* Build a machine learning model to predict song popularity
* Perform artist-wise popularity analysis
* Develop a music recommendation system
* Explore popularity trends across different time periods

---

## 📂 Project Structure

```text
spotify-hit-song-analysis/
│
├── spotify_analysis.ipynb
└── README.md
```

---

## 👨‍💻 Author

Bhavyaa

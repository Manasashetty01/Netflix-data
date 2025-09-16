
# 🎬 Netflix Movies & TV Shows Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![PowerBI](https://img.shields.io/badge/Visualization-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-green)
![License](https://img.shields.io/badge/License-MIT-success)

---

## 📌 Project Overview

This project analyzes **Netflix Movies and TV Shows dataset** to uncover trends in:

* 📊 **Content distribution** across years, genres, and countries
* 🌍 **Global contribution** of countries and directors
* 🔞 **Rating patterns** to see the audience focus
* 🎭 **Genre insights** for Movies vs TV Shows
* 📈 **Growth trends** in yearly and monthly releases

📂 *Dataset size:* **8,790 records × 10 columns**

---

## 🗂 Dataset Description

| Feature        | Description                           |
| -------------- | ------------------------------------- |
| `show_id`      | Unique ID for each title              |
| `type`         | Movie or TV Show                      |
| `title`        | Title of the content                  |
| `director`     | Director of the movie/show            |
| `country`      | Country of origin                     |
| `date_added`   | Date added to Netflix                 |
| `release_year` | Year of original release              |
| `rating`       | Audience rating (TV-MA, PG-13, etc.)  |
| `duration`     | Minutes (movies) / Seasons (TV shows) |
| `listed_in`    | Genre(s)                              |

---

## 🔍 Exploratory Data Analysis

### 📅 Content Distribution Over Years

➡️ Titles grew rapidly after 2000, showing Netflix’s aggressive expansion.

### 🌍 Country-wise Contribution

➡️ **United States dominates**, followed by India, UK, and other regions.

### 🔞 Ratings Analysis

➡️ **TV-MA** and **TV-14** are the most frequent → Netflix targets adults & teens.

### 🎭 Content Categories

➡️ **Dramas & International Movies** dominate; Documentaries and Comedies are also strong.

### 🎬 Directors

➡️ **Rajiv Chilaka**, **Alastair Fothergill**, and **Raúl Campos & Jan Suter** top the list, alongside global icons like **Scorsese**.

### 🎥 Genre Insights

➡️ Movies → Drama & Documentaries;
➡️ TV Shows → Kids’ TV & International Dramas.

### 📈 Yearly Releases

➡️ Sharp growth after 2015, especially for TV Shows (rise of Originals).

### 📆 Monthly Releases

➡️ Peaks in **September & December** due to premieres and holiday content.

---

## 💡 Key Findings

✔️ US leads, but **international expansion is strong**

✔️ Netflix’s catalog is **adult-oriented** (TV-MA, TV-14 dominate)

✔️ **Drama rules** across Movies and TV Shows

✔️ **TV Shows surged after 2015**, reflecting Netflix’s Originals push

✔️ Seasonal peaks in releases match industry cycles

---

## 🚧 Limitations

* No **viewership data** → cannot measure popularity
  
* Multiple genres per title → needs advanced text cleaning
  
* Dataset static → no real-time updates

---

## 🚀 Future Work

* Add **NLP analysis** of genres and descriptions
  
* Compare with **competitors (Prime, Disney+)**
  
* Analyze **time-to-Netflix** (release vs added date)
  
* Predict content popularity using ML

---

## 📂 Repository Structure

```bash
📦 Netflix-Analysis
 ┣ 📜 README.md
 ┣ 📂 data
 ┃ ┗ netflix1.csv
 ┣ 📂 notebooks
 ┃ ┗ NetflixAnalysis.ipynb
 ┣ 📂 reports
 ┃ ┗ NetflixData_Report.pdf
```

---

## 🛠 Tools & Libraries

* **Python** (Pandas, NumPy)
* **Matplotlib, Seaborn** (Visualizations)
* **Jupyter Notebook**

---

## 📜 License

MIT License.

---

✨ If you found this project insightful, don’t forget to ⭐ star the repo!



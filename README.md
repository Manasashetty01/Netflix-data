
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
<img width="875" height="899" alt="image" src="https://github.com/user-attachments/assets/532c6603-fe7a-4fa8-97db-9e2dfa365bf9" />


### 🌍 Country-wise Contribution

➡️ **United States dominates**, followed by India, UK, and other regions.
<img width="940" height="814" alt="image" src="https://github.com/user-attachments/assets/d6f2e8e5-5ec8-4cb2-a88b-e35848253046" />

<img width="940" height="643" alt="image" src="https://github.com/user-attachments/assets/037e5770-fa00-4d14-8dfb-53b755971ba9" />

### 🔞 Ratings Analysis

➡️ **TV-MA** and **TV-14** are the most frequent → Netflix targets adults & teens.
<img width="902" height="589" alt="image" src="https://github.com/user-attachments/assets/e4c8de69-1a94-4505-8153-7443d272744a" />

### 🎭 Content Categories

➡️ **Dramas & International Movies** dominate; Documentaries and Comedies are also strong.
<img width="819" height="942" alt="image" src="https://github.com/user-attachments/assets/fca9b4dc-f9bb-4266-b3e6-53bcbb09e340" />

### 🎬 Directors

➡️ **Rajiv Chilaka**, **Alastair Fothergill**, and **Raúl Campos & Jan Suter** top the list, alongside global icons like **Scorsese**.
<img width="844" height="778" alt="image" src="https://github.com/user-attachments/assets/63373ac1-16ea-4eab-9575-a91eea242670" />


### 🎥 Genre Insights

➡️ Movies → Drama & Documentaries;
<img width="861" height="913" alt="image" src="https://github.com/user-attachments/assets/203b0322-e2b4-4624-8504-53ce236ac1ca" />

➡️ TV Shows → Kids’ TV & International Dramas.
<img width="940" height="901" alt="image" src="https://github.com/user-attachments/assets/6e3a59c3-277c-4117-a972-0ee0082dbdf8" />


### 📈 Yearly Releases

➡️ Sharp growth after 2015, especially for TV Shows (rise of Originals).
<img width="940" height="635" alt="image" src="https://github.com/user-attachments/assets/c0829edc-0342-4dd6-9ff3-92adc1d94283" />

### 📆 Monthly Releases

➡️ Peaks in **September & December** due to premieres and holiday content.
<img width="940" height="776" alt="image" src="https://github.com/user-attachments/assets/0b211447-2a4c-47ef-9ac5-c3eba67d8989" />

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



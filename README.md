# 🎬 Netflix Content Analysis — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.2-150458?style=flat-square&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4EACD0?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

> An end-to-end exploratory data analysis on 8,000+ Netflix titles — uncovering content trends, genre distributions, country-wise patterns, and growth over time.

---

## 📌 Project Overview

This project explores the Netflix titles dataset to answer key business questions:

- How has Netflix's content library grown over the years?
- What is the split between Movies and TV Shows?
- Which countries produce the most content on Netflix?
- What genres dominate the platform?
- How has content rating distribution changed over time?

---

## 📊 Key Insights

- 🎥 **Movies outnumber TV Shows** — roughly 70% of Netflix's catalogue is movies
- 📈 **Content additions peaked around 2019**, followed by a slowdown post-2020
- 🌍 **USA, India, and the UK** are the top three content-producing countries
- 🎭 **Dramas and Comedies** are the most represented genres globally
- 🔞 **TV-MA and TV-14** are the most common content ratings on the platform

---

## 🗂️ Repository Structure

```
netflix-content-eda/
│
├── netflix_eda.ipynb        # Main Jupyter Notebook with full analysis
├── README.md                # Project documentation (you're here!)
├── requirements.txt         # Python dependencies
│
├── data/
│   └── netflix_titles.csv   # Raw dataset (sourced from Kaggle)
│
└── visuals/                 # Exported charts and plots
    └── (auto-generated when you run the notebook)              
    ├── content_type_split.png
    ├── top_genres.png
    ├── yearly_additions.png
    └── top_countries.png
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.10+ | Core programming language |
| Pandas | Data loading, cleaning & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Base plotting |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis environment |

---

## 🚀 How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-content-eda.git
cd netflix-content-eda
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open the notebook
Click on `netflix_eda.ipynb` and run all cells (`Kernel → Restart & Run All`)

---

## 📁 Dataset

- **Source:** [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size:** ~8,800 titles
- **Features:** Title, Type, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre

---

## 👤 Author

**Porush**
- 🔗 [LinkedIn](https://linkedin.com/in/your-profile)
- 💻 [GitHub](https://github.com/your-username)
- 🌐 [Portfolio](https://your-portfolio.com)


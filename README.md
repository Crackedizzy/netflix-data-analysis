# 📺 Netflix Data Analysis

## 🔍 Overview
This project performs an exploratory data analysis (EDA) on Netflix's Movies and TV Shows dataset to uncover insights about content type, release patterns, country distribution, and more.

## 📊 Dataset
- **File**: `data/netflix_titles.csv`
- **Source**: [Kaggle – Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Size**: ~8,800 entries
- **Fields**: `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, etc.


## 🧠 Key Insights
- ✅ Netflix has significantly more **Movies** than **TV Shows**
- 📈 The majority of content was added between **2017–2020**
- 🌍 **United States** leads in number of titles
- 🔞 The most common rating is **TV-MA**
- 📺 Most TV shows on Netflix have only **1 season**

---

## 🛠️ Tools & Libraries Used
- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📁 Project Structure

netflix-data-analysis/

├── data/

│ └── netflix_titles.csv

├── netflix_eda_project.ipynb

├── README.md

---

## 🚀 How to Run This Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/netflix-data-analysis.git
   cd netflix-data-analysis
2. **Open the notebook**:
  - Use Google Colab or Jupyter Notebook
  - Open netflix_eda_project.ipynb

3. Run all cells to view the analysis

✅ The dataset netflix_titles.csv is already included in the data/ folder.

## ✅ Future Ideas
- Add interactivity with Streamlit
- Perform clustering by content type
- Build a genre-based recommender

---

🧑‍💻 Made by [Israel](https://github.com/crackedizzy)

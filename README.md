
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" alt="Netflix Logo" height="120">
</p>

<h1 align="center">📊 Netflix Data Analysis Project</h1>

<p align="center">
  An insightful data analysis project that explores, cleans, and visualizes Netflix movies data to extract key trends and patterns.
</p>

---

## 📂 Project Structure

```

Netflix data Analysis/
│
├── movie data analysis netflix.ipynb      # Main Jupyter notebook
├── movie data analysis netflix.pdf        # PDF output of the notebook
├── movie data analysis netflix.html       # HTML version (for browser viewing)
├── Netflix\_dataset.csv                    # Dataset used for analysis
└── Presentation.pptx                      # Summary presentation with key insights

````

---

## 🧠 Overview

This project involves exploratory data analysis on a dataset containing Netflix movie records.  
The core objectives include:

- Data cleaning and preprocessing
- Feature engineering (like converting dates and extracting years)
- Outlier detection and handling
- Category-wise segmentation
- Visualization of trends in popularity, genres, and ratings

---

## 📌 Dataset Highlights

- **Total Records:** 9827
- **Columns:** 9 (initially), dropped 3 unnecessary ones
- **No Nulls / Duplicates** found – dataset is clean!
- **Outliers Found:** In `popularity` column  
- **Date Conversion:** `Release_Date` converted to datetime  
- **Genres:** Cleaned and grouped into broader categories  
- **Vote_Average:** Grouped into rating levels (e.g., High, Medium, Low)

---

## 📊 Key Visual Insights

- 📈 Most movies released after **2010**
- 🎭 **Drama**, **Action**, and **Comedy** are the top 3 genres
- 🌐 English is the dominant language
- 🔥 Popularity score has a few **major outliers**
- ⭐ Voting trends show most movies lie in the **6–8** average range

---

## 🚀 How to Run the Project

### 1. Install Required Libraries:
```bash
pip install pandas matplotlib seaborn
````

### 2. Launch Jupyter Notebook:

```bash
jupyter notebook "movie data analysis netflix.ipynb"
```

---

## 📥 Data Source

The dataset was obtained from a publicly available source and includes the following fields:

* Title
* Release Date
* Popularity
* Genres
* Vote Average
* Language

---

## 🎓 Tools & Technologies Used

* **Python** (Pandas, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **Data Cleaning & Feature Engineering**
* **Visualizations** for insight extraction

---

## 📽️ Output Formats

* ✅ Notebook (.ipynb)
* ✅ PDF Report
* ✅ HTML View
* ✅ PPTX Summary

---

## 🙌 Acknowledgements

* Tutorial Reference: [Netflix Analysis Walkthrough](https://www.youtube.com/watch?v=tjIWRqqMDaw)
* Special thanks to open-source contributors & data science community

---

## 📄 License

This project is licensed for **educational purposes only**.
Feel free to fork, explore, and improve!

---

> Made with ❤️ for Data Science and Netflix lovers!

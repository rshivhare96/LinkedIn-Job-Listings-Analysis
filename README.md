# LinkedIn Job Listings Analysis

This project analyzes job postings data scraped from LinkedIn across **Africa**, **Canada**, and the **United States**. The goal is to extract valuable insights about hiring trends, popular job roles, industries, and employment types, with a focus on data and tech positions.

---

## 📂 Data

The project uses three datasets:

- **linkedin-jobs-africa.csv**  
- **linkedin-jobs-canada.csv**  
- **linkedin-jobs-usa.csv**

Each dataset contains job title, company, employment type, location, seniority level, date posted, and other metadata related to job postings.

---

## 🔍 Analysis Workflow

The end-to-end analysis includes:

- Loading and merging datasets  
- Arabic-to-English normalization of categorical fields  
- Cleaning job titles, industries, and criteria fields  
- Parsing and preprocessing job description criteria  
- Tokenization and stopword removal for job title analysis  
- Generating **word clouds** and **frequency plots**  
- Exploratory visualizations using **Plotly** and **Matplotlib**  
- Time series breakdown of job postings by year/month  
- Country-wise breakdown of job types and industries  

---

## 📊 Key Insights

- **Full-time** and **Entry-Level** roles dominate across regions.  
- Top job titles include "Data Analyst", "Software Engineer", and "Project Manager".  
- Significant hiring activity observed in **Canada** and **US**, with Africa trailing behind.  
- Distinct trends in **industries** and **job functions** between countries.  

---

## 📁 Notebooks & Scripts

- `linkedin_jobs_analysis.ipynb`: Full exploratory analysis notebook with data cleaning, preprocessing, and visualization.

---

## 🛠️ Libraries Used

- **Data Processing**: `pandas`, `numpy`, `re`, `string`  
- **Visualization**: `matplotlib`, `plotly.express`, `WordCloud`  
- **Text Processing**: `nltk` (`stopwords`, `word_tokenize`)  

---

## ✅ Usage

To reproduce the analysis:

1. Clone the repository  
2. Place the job CSV files in the root project directory  
3. Run the notebook `linkedin_jobs_analysis.ipynb`  
4. Explore the generated plots and word clouds for insights  

**Optional Enhancements**:
- Add classification/clustering to segment job roles  
- Build a dashboard (e.g., using Streamlit)  
- Apply NLP to analyze job descriptions in-depth  

---

## 👤 Author

**Rohit Shivhare**  
[LinkedIn](https://www.linkedin.com/in/rohit-shivhare-a857a4233/)  
*MSc Data Science – Brunel University, London*

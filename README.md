# 📊 Netflix Movies and TV Shows Analysis

##  Project Overview
This project analyzes the Netflix Movies and TV Shows dataset to uncover insights about:
- Content distribution over the years
- Popular genres and ratings
- Trends in movie/TV show releases
- Word cloud of descriptions
- Top directors on Netflix
- Data cleaning
- Visualization (Top Directors, Ratings, Release Year Trends, etc.)
- WordCloud for descriptions

![Rating Distribution](images/rating_distribution.png)


---

## 📂 Dataset
- **netflix_titles.csv** → Original dataset containing Netflix content details.
- **netflix_cleaned.csv** → Cleaned dataset after preprocessing.

Dataset contains:
- `type` → Movie or TV Show  
- `title` → Name of the content  
- `director` → Director name  
- `cast` → Main actors/actresses  
- `country` → Country of production  
- `date_added` → Date added to Netflix  
- `release_year` → Release year  
- `rating` → Content rating (e.g., TV-MA, PG-13)  
- `duration` → Duration (in minutes or seasons)  
- `listed_in` → Genre(s)  
- `description` → Short summary  

---

##  Tools & Libraries
- **Python** (Data Analysis)
- **Pandas** (Data Handling)
- **Matplotlib** & **Seaborn** (Visualization)
- **WordCloud** (Text Analysis)
- **Jupyter Notebook** (Interactive Analysis)

---

##  Analysis & Visualizations
1. **Content Added Over the Years**
   ![Added by Year](images/added_by_year.png)

2. **Release Year Trends**
   ![Release Year Trend](images/release_year_trend.png)

3. **Top Directors**
   ![Top Directors](images/top_directors.png)

4. **Rating Distribution**
   ![Rating Distribution](images/rating_distribution.png)

5. **Word Cloud from Descriptions**
   ![Description Word Cloud](images/description_wordcloud.png)

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/nidhi-yadav20799/Netflix-Analysis.git

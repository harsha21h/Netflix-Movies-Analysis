# 🎬 Netflix Movies Analysis Using Python

## 📌 Project Objective

To analyze a dataset of movies available on Netflix and extract valuable insights such as genre popularity, content trends by year, movie ratings, and language preferences. The project utilizes Python-based data analysis techniques to explore and visualize key patterns that define Netflix's movie offerings.

---

## 📁 Dataset

- **File Name**: <a href="https://github.com/harsha21h/Netflix-Movies-Analysis/blob/main/mymoviedb.csv">`mymoviedb.csv`</a>
- **Source**: Custom dataset containing details of movies on Netflix
- **Key Features**:
  - Title
  - Genre
  - Director
  - Cast
  - Country
  - Release Year
  - Duration
  - Rating
  - Language

---

## ❓ Key Questions Explored

- What are the most common genres on Netflix?
- Which directors have the most titles on Netflix?
- What is the distribution of movies by release year?
- What are the most common movie ratings (e.g., TV-MA, PG-13)?
- How many movies are produced per country?
- Which languages are most frequently used?

---

## ⚙️ Workflow

### 🔹 Data Cleaning

- Checked for null values and dropped/filled them accordingly
- Converted columns (e.g., `Release_Date`) to datetime
- Removed duplicates

### 🔹 Data Analysis

- Used `groupby()`, `value_counts()`, and aggregation techniques to summarize:
  - Genre trends
  - Director appearances
  - Year-wise movie release frequency
  - Rating distribution

### 🔹 Data Visualization

- Libraries used: `matplotlib`, `seaborn`
- Created:
  - Bar charts of genre and rating frequency
  - Count plots for top countries and directors
  - Line plots for yearly trends
 
  - <img width="293" alt="Genre Distibution" src="https://github.com/user-attachments/assets/f4f70d75-1a0c-4aa4-b4ca-6bc17f83376f" />


---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📌 Key Insights

- **Drama**, **Comedy**, and **Action** are the most common genres.
- A few directors dominate the platform with multiple films.
- Netflix content has seen consistent growth in recent years.
- **English** is the most used language, followed by **Hindi** and **Spanish**.
- The platform includes a wide variety of ratings, with **TV-MA** being the most frequent.

---


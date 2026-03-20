# 🎬 Movie Cast & Crew Analysis

## 📌 Project Overview
This project focuses on analyzing and visualizing a movie dataset containing information about cast and crew members. The goal is to explore patterns in movie production teams and extract meaningful insights using data analysis techniques.

---

## 🎯 Objectives
- Clean and preprocess raw movie data
- Transform unstructured data into usable formats
- Perform exploratory data analysis (EDA)
- Visualize patterns in cast and crew distributions
- Extract insights from real-world datasets

---

## 🧰 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Description
The dataset contains the following key columns:

- `movie_id` → Unique identifier of each movie  
- `title` → Movie title  
- `cast` → List of actors (JSON format)  
- `crew` → List of crew members (JSON format)  

---

## 🧹 Data Cleaning Steps
- Removed unnecessary columns (Unnamed columns)
- Handled missing values
- Converted JSON-like text data into Python objects using `ast.literal_eval`
- Ensured data consistency for analysis

---

## ⚙️ Feature Engineering
New features were created to simplify analysis:

- `cast_size` → Number of actors per movie  
- `crew_size` → Number of crew members per movie  

---

## 📊 Data Visualization

### 1️⃣ Cast Size Distribution
- Shows how many actors are involved in movies
- Most movies have a moderate number of actors
- A few movies have very large casts (outliers)

### 2️⃣ Crew Size Distribution
- Displays production team sizes
- Most movies have small to medium crews
- Some large productions involve many crew members

---

## 📈 Key Insights
- Movie production sizes vary significantly
- Most films involve relatively small teams
- A small number of movies have very large casts and crews
- Data distributions are right-skewed, indicating outliers

---

## ✅ Conclusion
This project demonstrates how raw and unstructured data can be transformed into meaningful insights through data cleaning, feature engineering, and visualization. It highlights the importance of exploratory data analysis in understanding real-world datasets.

---

## 🚀 Future Improvements
- Extract top actors and directors
- Analyze collaborations between actors and directors
- Add interactive visualizations (Plotly)
- Combine with movie rating datasets for deeper insights

---

## 📎 How to Run the Project

```bash
git clone https://github.com/your-username/movie-cast-crew-analysis.git
cd movie-cast-crew-analysis
jupyter notebook

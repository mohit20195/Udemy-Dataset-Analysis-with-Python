# 📊 Udemy Dataset Analysis  
### Exploratory Data Analysis using Python & Pandas

---

## 📝 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** of the Udemy courses dataset using **Python and Pandas**.  
The objective is to analyze course characteristics, pricing models, popularity trends, and learner engagement to extract **meaningful business insights**.

The analysis focuses on understanding:
- Course distribution across subjects
- Free vs paid course trends
- Subscriber behavior
- Popularity by course level

---

## 📂 Dataset Description
The dataset contains structured information about Udemy courses, including:

- 📘 Course Title  
- 🗂️ Subject Category  
- 💰 Price  
- 🔓 Paid / Free Status  
- 👥 Number of Subscribers  
- 🎓 Course Level (Beginner / Intermediate / Expert)

---

## 🛠️ Tools & Technologies
- 🐍 **Python**
- 📊 **Pandas**
- 📓 **Jupyter Notebook**

---

## 🔍 Key Analysis Performed

### 1️⃣ Subjects Offered on Udemy
- Identified all unique subjects available on the platform.

### 2️⃣ Subject with Maximum Courses
- Determined which subject category offers the highest number of courses.

### 3️⃣ Free Courses Analysis
- Filtered and analyzed all **free courses**.

### 4️⃣ Paid Courses Analysis
- Extracted all **paid courses** for comparative insights.

### 5️⃣ Top-Selling Courses
- Identified courses with the **maximum number of subscribers**.

### 6️⃣ Least-Selling Courses
- Found courses with the **minimum subscriber base**.

### 7️⃣ Affordable Graphic Design Courses
- Analyzed **Graphic Design courses priced below 500**.

### 8️⃣ Python-Based Courses
- Filtered courses containing **“Python”** in the course title using string operations.

### 9️⃣ Most Popular Course by Level
- Identified the **highest subscribed course** for each difficulty level.

---

## 📈 Sample Pandas Operations
```python
# Free courses
data[data['is_paid'] == False]

# Courses containing 'Python'
data[data['course_title'].str.contains('Python', case=False, na=False)]

# Most popular course per level
data.loc[data.groupby('level')['num_subscribers'].idxmax()]

---

## 💡 Key Insights & Learnings

- Practical experience with real-world data analysis
- Strong understanding of Pandas filtering, grouping, and indexing
- Ability to derive actionable insights from raw datasets
- Improved confidence in handling EDA interview questions

---

## 🚀 Future Enhancements

- 📊 Add data visualizations using Matplotlib / Seaborn
- 💹 Perform revenue and pricing trend analysis
- 📈 Build an interactive dashboard

---

## 👤 Author

- Mohit Sharma
- Email: info@deshatanplanner.com

# 📊 SQL Project: International Students & Mental Health  

## 📌 Project Overview  
This project explores and analyzes **students' data** to understand how the **length of stay (stay)** impacts the **average mental health diagnostic scores** of international students.  

We aim to return a table summarizing key insights based on three diagnostic tests:  
- 🧠 **PHQ-9 (todep)** → Depression screening  
- 💭 **SCS (tosc)** → Self-compassion scale  
- ⚡ **ASISS (toas)** → Acculturative stress scale  

---

## 📑 Task Requirements  
✔️ Return a table with **9 rows** and **5 columns**  
✔️ Columns should be aliased as:  

| stay ⏳ | count_int 👥 | average_phq 🧠 | average_scs 💭 | average_as ⚡ |  
|--------|--------------|----------------|----------------|--------------|  

✔️ Calculations:  
- `count_int` → number of international students for each stay length  
- `average_phq`, `average_scs`, `average_as` → averages of the respective columns, **rounded to 2 decimals**  

✔️ Sorting:  
- Results should be **ordered by stay in descending order**  

---

## 🛠️ Tools & Skills  
- 📌 **SQL**: Aggregation, Aliasing, Sorting, Grouping  
- 📌 **Data Analysis**: Exploring relationships between stay duration & mental health scores  

---

## 🚀 How to Run  
1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git

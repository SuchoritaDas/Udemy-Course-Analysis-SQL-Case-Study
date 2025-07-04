# Udemy-Course-Analysis-SQL-Case-Study
SQL-based analysis of Udemy’s 3,600-course dataset to uncover revenue opportunities, pricing gaps, and engagement trends. Advanced SQL (CTEs, Views) identified top subjects, underpriced popular courses and durations. Includes clear SQL scripts, visuals, and recommendations turning raw data into actionable strategy for improved learner experience.
# 📊 Udemy Course Performance Analysis – SQL Case Study



---

## 📌 Project Overview

This project is a **SQL-based analysis** of Udemy’s course dataset to identify revenue opportunities, pricing gaps, and engagement trends.  

Using over 3,600 courses published between 2011 and 2017, I applied advanced SQL techniques—including CTEs, Views, and aggregations—to uncover:  
- Top revenue-generating subjects
- High-demand, underpriced courses
- Free courses causing potential revenue loss
- Optimal course duration for user engagement

Deliverables include clear, documented SQL scripts, a presentation in PDF format, and actionable recommendations.  

---

## 🗂️ Repository Structure
/slides/ -> Presentation deck as PDF
/sql/ -> All SQL scripts with explanations
/docs/ -> Recommendations and project overview
README.md -> This file


---

## 🗄️ Dataset
https://github.com/SuchoritaDas/Udemy-Course-Analysis-SQL-Case-Study/blob/8448eeb61d51096b67accb4095554367978f6a76/Udemy%20Courses.zip
- Source: Kaggle Udemy Courses Dataset
- ~3,672 course records (2011–2017)
- Fields include:
  - Course ID, Title, URL
  - Is Paid, Price
  - Number of Subscribers, Reviews
  - Number of Lectures, Content Duration
  - Published Timestamp, Subject
  - Level (Beginner, Intermediate, Expert, All Levels)

---

## ⚙️ Tools Used

- **SQL / MySQL Workbench**: Primary querying and analysis
- **Advanced SQL**: CTEs, Views, Window Functions, Subqueries
- **Excel**: Visualization and charting
- **PowerPoint**: Presentation design
- **Command Prompt**: Efficient dataset import via `LOAD DATA INFILE`

---

## 📜 SQL Scripts

Each SQL file includes clear header comments describing its purpose.

| Script                          | Description                                               |
|---------------------------------|-----------------------------------------------------------|
| `01_database_setup.sql`         | Creates Udemy database and courses table                  |
| `02_revenue_analysis.sql`       | Analyzes subject-wise and level-wise revenue              |
| `03_free_vs_paid_engagement.sql`| Compares average subscriber engagement for free vs paid   |
| `04_underpriced_courses.sql`    | Identifies high-demand, low-priced course opportunities   |
| `05_yearly_trends.sql`          | Tracks publishing trends over time                        |
| `06_engagement_vs_duration.sql` | Examines engagement patterns based on course duration     |

---

## 📑 Slides

📂 [`/slides/`](./slides/)

> Contains the full presentation exported as PDF (one slide per page) for easy viewing.  

---

## ✅ Key Findings

- **Web Development** courses generated the highest revenue (~₹6.27 Cr).  
- “**All Levels**” courses attracted the broadest audience and highest revenue.  
- A small number of **free courses** caused significant potential revenue loss.  
- **2–5 hour** courses delivered the best learner engagement.  
- Several **underpriced** courses had high demand, suggesting opportunities for repricing or bundling.  
- Publishing trends peaked around **2015**, with possible saturation by 2017.

---

## 📌 Recommendations (Personal Voice)

So, based on this analysis, here’s what I’d personally recommend:

1. **Review Underpriced, High-Demand Courses**  
   - Use enrollment and review data to spot them.
   - Test small, gradual price increases without risking big drop-offs.

2. **Create Bundle Offers**  
   - Group popular courses at an attractive combined price.
   - Improve learner value and overall sales.

3. **Monitor Changes and Feedback**  
   - Track enrollment and learner reactions after pricing changes.
   - Adjust strategy based on real outcomes.

4. **Share Insights with Instructors**  
   - Help instructors align their course design and pricing with what learners actually want.
   - Foster collaboration between platform and instructors to maximize value.

---

## 🎯 Conclusion

This SQL-driven case study demonstrates how structured data analysis can translate raw course data into clear, strategic recommendations.  
It highlights opportunities for Udemy to optimize pricing, improve engagement, and sustain growth—all while using rigorous SQL methods and clear communication.

---

## 💼 About Me

👤 **Suchorita Das**  
📚 Professional School Student | Data Analyst Aspirant  

💼 [LinkedIn Profile](https://www.linkedin.com/in/suchorita-das)  

> Feel free to connect to discuss data analysis, SQL projects, or ed-tech strategy!




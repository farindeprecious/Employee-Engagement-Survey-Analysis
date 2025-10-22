# Employee-Engagement-Survey-Analysis
This project explores what employees value most, identifies areas of low engagement, and provides data-driven recommendations to improve satisfaction and workplace culture.
## Table of Content
- [Project Overview](#project-overview)
- [Dataset Summary](#dataset-summary)
- [Tools Used](#tools-used)
- [Data Preparation](#data-preparation)
- [Visual Representation of the Dashboard](#visual-representation-of-the-dashboard)
- [Analysis and Insights](#analysis-and-insights)
- [Additional Insights](#additional-insights)
- [Dashboard Features](#dashboard-features)
- [Key Takeaways](#key-takeaways)
- [Recommendations](#recommendations)

## Project Overview
This project explores real employee engagement survey responses collected by **Pierce County, WA**.  
The goal was to uncover what employees value most, identify key areas of dissatisfaction, and recommend data-driven strategies to improve workplace satisfaction.

As a Data Analyst, I analyzed **14,725 responses** using Excel Pivot Tables to reveal trends by department, role, and survey question.

---

## Dataset Summary
- **Records:** 14,725  
- **Fields (Columns):** 10  
- **Source:** Pierce County Employee Engagement Survey  
- **Data Type:** Clean (no missing or invalid entries)

---

## Tools Used
- **Microsoft Excel** — for data analysis, visualization, and reporting  
- **Pivot Tables** — to group and summarize responses  
- **Charts** — to visualize department and role trends  
- **Slicers** — for interactivity (Status, Department, Response Text)

---

## Data Preparation
The dataset was already clean, so minimal transformation was required.  
However, to make analysis easier, I:
- Grouped similar responses together:
- *“Agree” + “Strongly Agree” → “Agree”*
- *“Disagree” + “Strongly Disagree” → “Disagree”*
- Ignored *“Not Available”* responses for clarity.
- Created separate Pivot Tables for each analytical question.

---

## Visual Representation of the dashboard




<img width="743" height="542" alt="Employee survey dashboard" src="https://github.com/user-attachments/assets/f33876c0-92ef-44ac-93fe-90f3a73a5bb3" />


---
## Analysis and Insights

### **Question 1:**  
*Which survey questions did respondents agree or disagree with most?*

- The statement **“I know what is expected of me at work”** had the **highest agreement** and **lowest disagreement** rate.  
- The statement **“I have a best friend at work”** had the **highest disagreement** and **lowest agreement** rate.  

*Insight:*  
Employees understand their job expectations clearly but may struggle with building strong workplace friendships or peer connections.

---

### **Question 2:**  
*Do you see any patterns or trends by department or role?*

Using Pivot Tables for **Role (Staff, Supervisor, Manager, Director)** and **Response Text:**

- **Directors** mostly agreed with statements like:
  - *“At work, I have the opportunity to do what I do best.”*
  - *“I know what is expected of me at work.”*
  - *“The mission or purpose of our organization makes me feel my job is important.”*
  - Their main disagreement: *“I have a best friend at work.”*

- **Staff, Supervisors, and Managers** all showed the same pattern:
  - *Highest agreement:* “I know what is expected of me at work.”
  - *Highest disagreement:* “I have a best friend at work.”

🪄 *Insight:*  
All levels of employees have a clear understanding of their roles but face challenges in workplace connection and engagement.

---

### **Question 3:**  
*As an employer, what steps might you take to improve employee satisfaction?*

🗒 **Recommendation Summary:**
> The survey reveals that employees clearly understand their roles and appreciate opportunities for growth and inclusion.  
> However, there are significant gaps in recognition and workplace connection, especially among staff and supervisors.  
> Strengthening recognition programs, promoting team bonding, and improving performance feedback systems could enhance overall satisfaction.

---

## Additional Insights
### **Top 5 Departments by Response Count**
- Planning & Public Works  
- Sheriff’s Department  
- Prosecuting Attorney’s Office  
- Finance & Performance Management  
- Human Services  

*(Visualized with a Column Chart)*

### **Top 3 Departments by Completed Surveys**
- Planning & Public Works  
- Sheriff’s Department  
- Prosecuting Attorney’s Office  

*(Visualized with a Bar Chart)*

---

## Dashboard Features
- Interactive **Slicers** for:
- Status (Complete or Incomplete)
- Departments
- Response Text
- **KPIs** summarizing participation and satisfaction levels
- **Visual Highlights**:
  - Bar Chart for top responses
  - Matrix for role-based comparisons
  - Text box for actionable recommendations

---

## Key Takeaways
- Employees **understand their roles** but lack **recognition and workplace connection**.  
- **Directors** and **Managers** are highly engaged, while **Staff** show the largest satisfaction gap.  
- Building a culture of recognition, mentorship, and collaboration can significantly improve morale and retention.

---

## Recommendations
- Launch recognition programs to celebrate good work.
- Encourage cross-department collaboration and social activities.
- Conduct regular feedback sessions and team check-ins.
- Offer mentorship opportunities to connect employees at different levels.

---

## This project was completed as part of the Digitaley Drive Bootcamp Data Analytics Program, demonstrating practical application of data cleaning, transformation, and visualization skills using Power BI.




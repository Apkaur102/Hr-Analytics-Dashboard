# HR-Analytics-Dashboard (Interactive Dashboard using Tableau)

## Project Objective
Build an **HR Analytics Dashboard** to understand employee **attrition**, workforce demographics, and **job satisfaction** so HR leaders can design effective **retention** and **hiring** strategies for the next year.

---

## Dataset Used
- [`HR Data.csv`](https://github.com/Apkaur102/Hr-Analytics-Dashboard/blob/main/HR%20Data.xlsx%20-%20HR%20data.csv) (anonymized HR records)  


---



## Questions (KPIs)
- What is the **Employee Count, Attrition Count, Active Employees, and Attrition Rate**?
- What is the **Average Age** of employees?
- **Department-wise Attrition**: which departments are most/least affected?
- **No. of Employees by Age Group** (age distribution).
- **Job Satisfaction** distribution by **Job Role** (ratings 1–4).
- **Education Field-wise Attrition**.
- **Attrition by Gender** and **by Gender across Age Groups**.

**Headline KPI values (from the dashboard):**
- Employee Count: **1,470**
- Attrition Count: **237**
- Active Employees: **1,233**
- Attrition Rate: **16.12%**
- Average Age: **37**
- Attrition by Gender: **Female = 87**, **Male = 150**

---

## Dashboard
- [`Dashboard.com`](https://public.tableau.com/shared/C8QG8G3ZH?:display_count=n&:origin=viz_share_link) (View Dashboard in Tableau Public)  

<img width="1974" height="1124" alt="overview_dashboard" src="https://github.com/user-attachments/assets/bf9b92b7-088d-4a7b-ab74-d36c9e2dc509" />


---

## Process
1. **Data Audit:** Checked for missing values, duplicates, inconsistent categories.
2. **Standardization:** Cleaned data types (dates, numeric fields), normalized categorical labels.
3. **Feature Logic:**
   - `Active Employees = Employee Count – Attrition Count`
   - `Attrition Rate = Attrition Count / Employee Count`
4. **Modeling in Tableau:**
   - Built worksheets for each analysis (Dept Attrition, Age Distribution, Job Satisfaction, Education Field, Gender).
   - Assembled into a single dashboard with filters (e.g., Education).
5. **Styling:** Dark theme for readability; consistent fonts, labels, and tooltips.
6. **Validation:** Cross-checked totals and segment counts against the source.

---

## Project Insights
- **Overall Attrition:** **16.12%** with **1,233** active employees remaining from **1,470** total.
- **Gender:** More attrition among **Males (150)** than **Females (87)**.
- **Department:** Highest attrition in **Sales**, lowest in **HR** (from department-wise pie).
- **Age:** Workforce concentrates around the **30–36** age range (histogram peak).
- **Education Field:** **Life Sciences** and **Medical** backgrounds show the highest attrition counts.
- **Job Satisfaction:** Noticeable variation by role; roles with more lower ratings tend to overlap with higher attrition segments.

---

## Final Conclusion
To reduce attrition:
- Prioritize retention programs in **Sales** and roles with lower **job satisfaction**.
- Focus engagement and career-growth initiatives for employees aged **30–36**, where volumes are highest.
- Design targeted interventions for **Life Sciences**/**Medical** education profiles if they are critical roles.
- Tailor actions by **gender** where gaps appear (e.g., mentoring, flexibility, manager coaching).
- Track changes monthly and iterate policies using the same dashboard.





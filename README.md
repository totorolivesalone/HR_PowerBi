# HR Attrition Analytics Dashboard
### Data Analytics Project: Python Feature Engineering + Power BI Visualization

---

## Project Overview

This project simulates a real-world HR analytics scenario. The goal was to identify employees at risk of leaving, provide actionable insights to HR leaders and build an interactive dashboard that bridges **data analytics** and **business intelligence**.

**Key Deliverables:**
- Python logic to engineer a `High_Risk` flag using 4 custom business rules.
- Power BI dashboard showing overview and actionable insights

**Tools Used:** Python (Pandas, Colab) | Power BI (DAX, Power Query) | GitHub

### Rules

For an employee to be considered at high risk attrition , 4 rules were devised :
- underpaid= salary less than mediansalary determined per role via median
- overworked= an employee with less than two year tenure who is overworking
- stagnation= employee who has been more than three years at current role and with satisfaction level lower than 2
- job hopper= person who has worked at more than 4 company and whose tenure is less than 2
These were arbitrary rules created on logical premises and the purpose of the flags was not feature engineering (ML) but simple data analytics

#### note
Given the rules were stagnant rules created on logical grounds and not curated via feature engineering by fine tuning via Machine Learning models, they were meant for curating high risk flag and not measure against actual attrition attribute. However, i did comparison and 
the results were sheepishly bad (18% translated to actual attrition) . However, as mentioned before the objective of this project was to create high risk flag and not a flag fine-tuned on Machine Learning's predicted analysis 

### Power Bi 

created two dashboards : overview and HR Action panel (based on slicer values) 
I had to add measure values here and transformed Department data to trim down on results after I noticed slicer not working for certain departments 




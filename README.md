Charity Pledge Report - Alteryx Project

📌 Project Overview

This project was designed to help a non-profit organization analyze charitable pledges by integrating donation data with a master charity dataset. By cleansing, transforming, and summarizing the data in Alteryx, I provided insights into:

The charity category with the largest total pledge amount

The charity with the highest number of credit card donations

The top charity in New York within the 'Public' category

🏆 Business Problem

The organization received a pledge report with donation details but lacked key charity information. My task was to merge this data with a master charity dataset to:
✅ Identify which charities and categories received the most support✅ Determine which donation methods were most frequently used✅ Help leadership allocate resources more effectively

📊 Data Inputs

Fact Table: System Pledge Report (contains pledge transactions)

Dimension Table: Charity Information (contains charity details)

🔧 Alteryx Workflow

1️⃣ Data Cleansing & Preparation

✅ Fact Table (Pledge Report):

Converted data types (Select Tool)

Standardized dates (DateTime Tool)

Applied transformations (Formula Tool)

✅ Dimension Table (Charity Information):

Split columns into meaningful text fields

Applied Multi-Row Formula for data consistency

Removed duplicates & fixed text casing

2️⃣ Data Joining

Joined both datasets on the common charity identifier

Ensured data integrity & consistency

3️⃣ Data Summarization & Insights

Aggregated pledge amounts and donation counts

Used Summarize Tool to answer key business questions

Sorted and filtered results for reporting

📈 Key Insights

1️⃣ The charity category with the largest total pledge amount: Education2️⃣ The charity with the highest number of credit card donations: St. Jude's Research Hospital3️⃣ The top charity in New York for 'Public' category: United Way Worldwide

🛠 Alteryx Tools Used

Data Cleansing: Select, DateTime, Formula, Multi-Row Formula

Data Preparation: Text to Columns, Remove Duplicates, Fix Case

Data Transformation: Join, Summarize, Filter, Sort

📌 Next Steps to consider

✅ Expand analysis to include year-over-year trends✅ Automate the workflow for monthly reporting✅ Add a Power BI dashboard for visualization

📎 Project Files

🔗 GitHub Repository Link: https://github.com/kajal-1700/Charity-Pledge-Report-Alteryx/blob/main/Charity%20Pledge%20Report.yxmd 

🙌 Connect With Me

If you're interested in Alteryx, analytics, or finance projects, let's connect on LinkedIn: https://www.linkedin.com/in/kajaljaiswal1700/


 

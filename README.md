# Fake-vs-Real-Job-Analysis

**Fake vs Real Job Postings Analysis Dashboard
📝 Project Overview**

This project is my first internship data analytics project, where I analyzed fake vs real job postings to identify fraud patterns in online recruitment data.
The complete workflow covers data cleaning in Excel and data visualization in Power BI, resulting in an interactive dashboard that highlights key fraud indicators.


**1️⃣ Project Background**

Online job portals are growing rapidly, but at the same time fake job postings are also increasing. These fake jobs can lead to financial loss, data theft, and exploitation of job seekers.

This project focuses on analyzing job posting data to:

Identify fake job postings

Understand patterns behind job fraud

Create a data-driven dashboard that helps detect fraud risk

This was my first internship project, where I applied Excel data cleaning and Power BI visualization skills on a real-world dataset.



**2️⃣ Objective of the Project**

The main goals of this project were:

Calculate the percentage of fake job postings

Compare fake vs real jobs

Analyze fraud patterns based on:

Employment type

Industry

Location (On-site / Remote)

Company logo availability

Create a Fraud Risk Score

Present insights in an interactive Power BI dashboard



**3️⃣ Dataset Understanding**

The dataset contains information related to job postings, such as:

Job title

Company name

Industry

Employment type

Location

Company logo availability

Whether the job is fake or real

The data was raw and unstructured, so cleaning was required before analysis.



**4️⃣ Data Cleaning Process (Excel)**

Data cleaning was performed entirely in Microsoft Excel before importing into Power BI.

**🔹 Step-by-Step Cleaning**

Removed duplicate rows to avoid double counting

Standardized text values

Employment types (Full-time, Part-time, Internship, Contract, Temporary)

Location names (On-site, Remote)

Handled missing values

Cleaned blank industry and company logo fields

Converted categorical values

Fake jobs converted to binary format (0 = Real, 1 = Fake)

**Created clean columns:**

clean_is_fake

clean_location

clean_has_logo

Used Pivot Tables to:

Validate totals

Cross-check fake vs real counts

This step ensured accurate and reliable data for visualization.



**5️⃣ Data Modeling in Power BI**

After cleaning, the Excel file was imported into Power BI.

🔹 Data Model

Single fact table with cleaned columns

No redundancy

Optimized for performance

🔹 DAX Measures Created

Some important measures include:

Total Jobs

Fake Jobs

Real Jobs

Fake Job Percentage

Industry Fraud Rate

Fraud Risk Score

These measures helped convert raw data into meaningful KPIs.



**6️⃣ Dashboard Explanation (Visual-Wise)**
🟣 KPI Cards (Top Section)

Total Jobs (3000)
Total number of job postings analyzed.

Fake Jobs (1528)
Number of identified fake job postings.

Real Jobs (1472)
Number of legitimate job postings.

Fake Job Percentage (51%)
Shows that more than half of the jobs are fake.

Remote Jobs (1523)
Total remote job postings.

Industry Fraud Rate (0.51)
Average fraud rate across industries.

🟣 Donut Chart – Fake vs Real Jobs

Visual comparison of fake and real job postings

Clearly highlights the high proportion of fake jobs

🟣 Employment Type vs Fake Jobs

This bar chart shows:

Full-time jobs have a significant number of fake postings

Internships and temporary roles also show fraud risk

Helps job seekers identify high-risk employment types

🟣 Logo Availability vs Fake Jobs

This visual shows:

Jobs without company logos are more likely to be fake

Logo presence acts as a trust indicator

🟣 Location Analysis (On-site vs Remote)

Remote jobs have higher fraud concentration

On-site jobs are comparatively safer

This insight is important in today’s remote-first job market

🟣 Fraud Risk Score Gauge

Calculated using fake job percentage

Score displayed: 0.58

Indicates moderate to high fraud risk

This gives a quick summary metric for decision-makers.

🟣 Detailed Job Table

Displays job title, company, industry, and employment type

Allows users to inspect individual job postings

Useful for auditing and verification



**7️⃣ Filters & Interactivity**

Industry slicer: Analyze fraud in specific industries

Location slicer: Compare on-site vs remote fraud

All visuals update dynamically based on selection



**8️⃣ Key Insights & Findings**

51% of jobs are fake, indicating serious fraud risk

Remote jobs are more vulnerable to scams

Jobs without logos have higher fraud probability

Some industries show consistently higher fake job ratios

Fraud Risk Score confirms urgent need for verification



**9️⃣ Business Impact**

Helps job portals improve fraud detection

Assists job seekers in making safer decisions

Enables recruiters to improve trust & transparency

Supports data-driven decision-making



**🔟 Learning Outcomes**

Real-world Excel data cleaning experience

Creating meaningful pivot tables

Writing DAX measures

Designing professional Power BI dashboards

Understanding fraud analytics




**🔮 Future Enhancements**

Add time-based trends

Use ML models for fraud prediction

Automate data pipeline

Enhance UI with tooltips & drill-through




![Dashboard Preview](https://github.com/Prerna-Pohakar/Fake-vs-Real-Job-Analysis-/blob/main/Fake%20vs%20Real%20job%20dashboard.png)



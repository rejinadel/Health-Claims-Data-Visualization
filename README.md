# Health-Claims-Data-Visualization
A Dynamic Power BI Dashboard Built Using DAX & Business Rules

🏥 Project Overview
This project presents a dynamic and interactive Healthcare Claims Analytics Dashboard developed in Power BI.The objective was to transform raw healthcare claims data into a structured, business-ready analytical model capable of answering financial, operational, and demographic questions through interactive visualizations.

The dashboard enables stakeholders to:
1.Monitor revenue trends
2.Analyze claim distribution by provider and type
3.Understand patient demographics
4.Evaluate operational claim status
5.Apply real-time filtering using slicers

🛠 Data Engineering & Transformation
-Removed unnecessary columns
-Standardized text columns (Provider Specialty, Claim Type, Claim Status)
-Applied business logic to Employment & Marital Status
-Created structured age group classifications
-Validated Claim Amount integrity
-Handled zero/null values appropriately
-Removed duplicate records
-Ensured consistent data types across fields
-Verified date formatting and yearly grouping logic

**Data Modeling & DAX Implementation**
Core Financial Metrics
Total Claims = COUNT(Claims[ClaimID])

Total Claim Amount = SUM(Claims[ClaimAmount])

Average Claim Amount = AVERAGE(Claims[ClaimAmount])

Demographic Metrics
Total Male = 
CALCULATE(COUNT(Claims[ClaimID]), Claims[Gender] = "Male")

Total Female = 
CALCULATE(COUNT(Claims[ClaimID]), Claims[Gender] = "Female")

Provider Analysis
Total Claim Amount by Provider Specialty =
SUM(Claims[ClaimAmount])

Business Questions Answered
1️⃣ Financial Analysis

What is the total claim revenue?

What is the average claim amount?

How does revenue vary by year?

Which claim types generate the highest revenue?

Which provider specialties contribute most to total claims?

2️⃣ Patient Demographics

What is the gender distribution of claims?

How does marital or employment status influence claim behavior?

3️⃣ Provider Performance

Which specialties generate the highest total claim amount?

Which provider segments drive claim volume?

What is the distribution of claims by status (Paid, Pending, Denied)?

How do claims vary by type (Routine, Emergency, Inpatient)?

Snip of Dashboard:
<img width="1336" height="752" alt="image" src="https://github.com/user-attachments/assets/bf208cf1-b0e4-46ae-a54e-4a4c795b9551" />

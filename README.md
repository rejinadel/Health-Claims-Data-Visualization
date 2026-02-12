# Health-Claims-Data-Visualization
The raw datasets consists of 17 columns and 4501 rows.

This dataset contains synthetic healthcare claims data including patient, provider, claim, and financial details. 
It can be used for analytics, reporting, and dashboarding.

Removing the unnecessary columns like diagnostic code and Procedure code.The remaining columns are:
ClaimID - Unique identifier for each claim. Typically a UUID (e.g., 10944daf-f7d5-4e1d-8216-72ffa609fe41).
PatientID - Unique identifier for the patient submitting the claim.
ProviderID - Unique identifier for the healthcare provider. UUID format.
ClaimAmount - Amount billed or claimed for the service (numeric).
ClaimDate - Date when the claim was submitted or processed.
DiagnosisCode - Code representing the diagnosis (e.g., ICD code).
ProcedureCode - Code representing the medical procedure performed.
PatientAge - Age of the patient (numeric, integer).
PatientGender - Gender of the patient (e.g., M/F).
ProviderSpecialty - Medical specialty of the provider (e.g., Cardiology, Neurology).
ClaimStatus - Status of the claim (e.g., Pending, Paid, Denied).
PatientIncome - Annual income of the patient (numeric).
PatientMaritalStatus - Marital status of the patient (e.g., Single, Married).
PatientEmploymentStatus - Employment status of the patient (e.g., Employed, Retired, Student).
ProviderLocation - City, town, or region where the provider is located.
ClaimType - Type of claim (e.g., Routine, Emergency, Inpatient).
ClaimSubmissionMethod - How the claim was submitted (e.g., Online, Paper, Phone).

#Business questions

1️⃣ Financial / Cost Analysis Questions

What is the total claim amount for a given period (month, quarter, year)?

What is the average claim amount per patient or per provider?

Which providers or specialties generate the highest claim costs?

How does claim amount vary by claim type (Routine, Emergency, Inpatient)?

Are there outlier claims that are unusually high or low?

2️⃣ Patient Analysis Questions

How many unique patients are submitting claims?

What is the distribution of claims by patient age and gender?

How does patient income or employment status relate to claim amount or type?

Are there repeat claim patterns for certain patients?

3️⃣ Provider Analysis Questions

Which providers or locations have the most claims?

Which specialties generate the most revenue?

How many claims are pending, paid, or denied per provider?

4️⃣ Claim Type / Operational Questions

What percentage of claims are Routine, Emergency, or Inpatient?

How does submission method (Online, Paper, Phone) affect claim status or processing time?

Are there trends in claims over time (monthly, quarterly)?
5️⃣ Risk / Outlier / Compliance Questions

Are there patients or providers with unusually high claim amounts?

Are there claims submitted by minors that need review?

Identify claims that are pending for a long time.


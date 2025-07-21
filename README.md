NYC Restaurant Inspection Analysis
==================================

Overview
--------
This project analyzes restaurant inspection data from New York City to uncover trends in health code violations, inspection scores, and food safety risks. The goal is to identify patterns across boroughs, cuisine types, and time in order to provide insights into food safety and inform the public and stakeholders.

The project includes data cleaning, exploratory data analysis (EDA), visualization, and dashboard development using Python and Tableau.

Data Source
-----------
- Dataset: NYC Restaurant Inspection Results
  https://data.cityofnewyork.us/Health/Restaurant-Inspection-Results/43nn-pn8j
- Provided by: NYC Open Data
- Format: CSV

Tools Used
----------
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Tableau
- GitHub
- Excel (optional for pivoting and quick summaries)

Key Questions
-------------
- Which boroughs have the highest number of violations?
  Manhattan with over 100,000 violations.
  <img width="889" height="476" alt="image" src="https://github.com/user-attachments/assets/2a03e4fd-e1c9-44f9-8bfa-1e032cd8d7cd" />

- What are the most common types of health code violations?
- 1. Non-food contact surface or equipmade made of unacceptable material, not kept clean, nor properly sealed raised, spaced or mavable to allow accessibility for cleaning on all sides, above and underneath the unit.
  2. Establishment is not free of harborage or conditions conducive to rodents, insects, or other pests.
  3. Food contact surface not properly washed, rinsed and sanitized after each use and following any activity when contamination may have occured.
     <img width="1820" height="386" alt="image" src="https://github.com/user-attachments/assets/68f3b1f3-3046-45f6-8d32-7fa0ebb65a58" />

- Do certain cuisine types tend to receive lower inspection scores?
  Yes, Bangladeshi, African, and Filipino food scores highest (worse).
  <img width="1143" height="602" alt="image" src="https://github.com/user-attachments/assets/9b09ac86-814a-4074-8474-5ce5405ecb1b" />

- How do inspection scores change over time?
  Yes, inspection scores have generally increased over time.
  <img width="927" height="474" alt="image" src="https://github.com/user-attachments/assets/82d91591-469a-4543-b78d-f86d7338bc3b" />

Process
-------
1. Data Cleaning
   - Removed null and duplicate entries
   - Filtered for valid inspection grades and scores
   - Standardized column names and categories

2. Exploratory Data Analysis (EDA)
   - Analyzed violations by borough and cuisine type
   - Explored score distributions and critical vs. non-critical violations
   - Identified trends in grades over time

3. Visualization & Dashboard
   - Built visualizations in Tableau:
     * Violation counts by borough
     * Top cuisine types by violation rate
     * Score trends by year and inspection type
   - Created filters for cuisine, borough, and date

Results & Insights
------------------
- Boroughs with the highest violation counts included [Insert Result]
- Common violations involved [Insert Violation Types]
- Cuisine types such as [Cuisine] had lower average scores
- Scores and grades showed [Improvement/Decline] over the past 5 years

How to View the Dashboard
--------------------------
- Tableau Public: https://public.tableau.com/app/profile/tylor.justice.page
- GitHub Repository: https://github.com/TylorPage

Future Improvements
-------------------
- Integrate geospatial visualizations with map overlays
- Automate data refresh using Tableau Public or a Python script
- Apply predictive modeling to flag high-risk restaurants before inspection

Author
------
Tylor Justice-Page  
Email: tjusticepage@gmail.com
LinkedIn: https://www.linkedin.com/in/tj-page-51b9b3199  
GitHub: https://github.com/TylorPage

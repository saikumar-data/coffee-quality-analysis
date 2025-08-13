# coffee-quality-analysis
Power BI dashboard and analysis of Coffee Quality Institute (CQI) dataset

Coffee Quality Analysis – CQI Dataset
This project analyzes coffee quality data from the Coffee Quality Institute (CQI) to understand the factors influencing overall coffee quality. Using Power BI, we visualize sensory attributes, processing methods, defect occurrences, and their correlations with Total Cup Points to draw actionable insights.

Dataset Overview
Source: Coffee Quality Institute (CQI)

Key Columns:
Aroma, Flavor, Aftertaste, Acidity, Body, Balance, Uniformity, Clean Cup, Sweetness, Overall (sensory scores)
Processing Method (e.g., Washed, Natural, Honey)
Country of Origin
Defect counts (Category 1 & Category 2 defects)
Total Cup Points (sum of 6 sensory attributes)

Project Goals & KPI Questions:
Research Questions
Key Determinants of Coffee Quality:
Which sensory attributes (Aroma, Flavor, Acidity, etc.) most strongly influence Total Cup Points?
KPI: Average score of each sensory attribute.

Processing Methods & Regions Impact:
Is there a correlation between processing methods, origin countries, and coffee quality scores?
KPI: Average Total Cup Points by processing method and region.

Defects Impact:
Do higher defect counts reduce coffee quality?
KPI: Average Total Cup Points by defect category.

Interactions Between Variables:
How do multiple variables together influence Total Cup Points?
KPI: Correlation analysis of all sensory attributes with Total Cup Points.

Tech Stack :
Data Source: CSV dataset from CQI
Visualization Tool: Power BI
Techniques Used:
Power Query for cleaning and transformations
DAX for calculated columns and measures
Interactive dashboards and slicers

Data Import & Transformation Steps
1. Import Data:
Imported the CSV dataset into Power BI.

2. Power Query Transformations:
Removed unwanted columns (e.g., grading date, unused IDs, comments).
Changed data types (dates, text, numbers).
Removed null and duplicate rows.
Created calculated columns if needed (e.g., Grade Category, DAX measures).

3. Load into Power BI for visualization.

Scatter Plots:
Aroma vs Flavor (colored by Total Cup Points)
Sensory attributes correlation with Total Cup Points

Line Chart:
Trends in coffee quality over time

 Key Insights
Aroma and Flavor have the strongest positive correlation with Total Cup Points.
Washed processing method generally produces higher quality scores.
Higher defect counts significantly reduce overall coffee quality.
Certain countries consistently produce higher quality coffee due to both processing method and bean variety.

 How to Use
Download the .pbix file from this repository.
Open it in Power BI Desktop (latest version recommended).


 License
This project is for educational and analytical purposes only. Dataset credit goes to the Coffee Quality Institute.
If you upload this with your .pbix file and a thumbnail image, your repo will look professional and complete.


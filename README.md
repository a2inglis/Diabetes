Diabetes mellitus (DM) is a pervasive chronic disease with significant implications for patients. DM increases the risk of other health issues and hospital readmissions.  Hospital readmissions are expensive to the system and patient quality of life is reduced. The objective of this research is to try to predict which diabetic patients are likely to be readmitted to hospital within 30 days of discharge. The original dataset contains 101,766 patient records with 50 attributes, from diabetic patient hospital stays between 1999-2008 from 130 US healthcare facilities. The dataset was retrieved from the UC Irvine Machine Learning Repository.
The project progressed through the following steps:
1. Literature Review: Conducted a literature review of existing research using the same dataset.
2. Data Preparation: In the Step 1 python file, prepared and cleaned the data and performed an exploratory data analysis.
3. Outlier Handling: In Step 2, further explored the data and addressed outliers based on two criteria: beyond the upper interquartile range or comprising approximately 1% of the data.
4. Feature Encoding & Selection: In Step 3, scaled, encoded categorical data and compared various feature selection techniques.
5. Model Building & Evaluation: In Step 4, four models were compared - KNN, decision tree, random forest and naive bayes.  They were then evaluated with recall, precision, accuracy and F1.
Additionally, this repository contains all the data transferred among different notebooks during the various stages.

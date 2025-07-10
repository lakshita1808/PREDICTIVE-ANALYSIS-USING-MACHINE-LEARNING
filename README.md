# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

"COMPANY": CODTECH IT SOLUTIONS
"NAME": LAKSHITA SEHGAL
"INTERN ID": CT04DG2051
"DOMAIN": DATA ANALYTICS
"DURATION": 4 WEEKS 
"MENTOR": NEELA SANTOSH

# PROJECT OVERVIEW:
 The purpose of this project is to explore how artificial intelligence (AI) may impact different job roles in the coming years and to build a predictive machine learning model that can estimate the risk level for  each job. With the rapid advancement of AI, many job sectors are expected to be affected — some may evolve, while others may be replaced. This analysis helps in identifying which jobs are most vulnerable 
 and which are likely to be safe from automation.

 We used the “AI Impact on Jobs” dataset, which contains job-related features such as job titles, industries, and various indicators that reflect how easily a job can be automated. The main objective was to build  a classification model that predicts the risk level of a job being impacted by AI: Low, Medium, or High.


# TOOLS AND TECHNOLOGY USED:
 .PySpark for large-scale data processing
 .MLlib for building machine learning models
 .Matplotlib & Seaborn for data visualization

# STEPS FOLLOWED:
.Data Cleaning->
 We began by loading and cleaning the dataset using PySpark. We removed duplicates, handled missing values, and ensured all data types were correct for analysis.

.Exploratory Data Analysis (EDA)->
 We explored the data visually using plots to understand which industries and job types are most at risk. This helped in identifying important patterns and relationships.

.Feature Selection->
 We selected relevant columns that would help the model learn effectively, such as job title, industry, and automation likelihood.

.Model Training->
 We trained classification models using Decision Tree and Logistic Regression in PySpark’s MLlib. These models were chosen for their simplicity and interpretability.

.Evaluation->
 We evaluated model performance using accuracy, confusion matrix, and classification report. Visualization was also done to compare predicted vs actual risk levels.

# RESULTS AND INSIGHTS:
 The machine learning models were able to predict job risk levels with good accuracy. The insights clearly showed that routine and rule-based jobs, such as data entry, clerical roles, and basic customer
 service,  are at high risk of being automated. On the other hand, creative roles, emotional labor jobs, and human-centric professions like teachers, therapists, and artists showed low risk.

 These predictions are not just numbers — they represent real challenges and opportunities. People working in high-risk jobs can use this insight to consider upskilling or transitioning into safer fields.
 Similarly, educators and governments can use this data to design training programs that prepare workers for the future.

# CONCLUSION:
This project combines the power of data, machine learning, and real-world relevance. By predicting AI’s impact on different jobs, we can better prepare for the future of work. The analysis supports informed decision-making and promotes proactive skill development, ensuring people stay ahead in a fast-changing job market.



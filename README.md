# Project-Description

Title: Analysing factors influencing mental health among individuals: Machine Learning Approach

Mental health is a crucial aspect of our daily lives, and it’s essential to prioritize our well-being, even amidst the demands of a busy lifestyle that can negatively impact our mental state. To address this issue, a mental health dataset sourced from Kaggle, which includes responses from 147,000 participants, was analyzed. This dataset captures a range of factors affecting mental health through numerical and categorical data. To further explore this topic, four key questions were proposed to guide the analysis.

1. Association between dietary habits and mental health (i.e. depression, suicidal thoughts, Family history of Mental Illness)
2. Analyze the relationship between sleep duration and academic performance (i.e. Academic Pressure, CGPA, Study hours) 
3. Analyze how work pressure affects job satisfaction among different working professionals (i.e. Profession, Job Satisfaction, Financial Stress, Work hours)
4. Comparison of different machine learning models for predicting Depression

# Key Findings
Result 1.

=> The correlation analysis revealed a weak correlation between mental health and dietary habits, with 15% being the highest, suggesting other determinants of mental health 

=> One interesting factor showed that suicidal thoughts and depression had a moderately strong positive correlation of 35%, which is proven by other studies as well 

Result 2.

=> The CGPA range of the students was:
- highest CGPA: 10
- average CGPA: 7.66
- lowest CGPA: 5.03

=> The relationship between CGPA and study satisfaction revealed that students with higher CGPAs tend to report lower study satisfaction, indicated as more hard-working and driven to achieve good grades, whereas students with lower CGPAs might be less diligent while being satisfied with their mediocre grades

=> Desipte varying sleep durations, most students maintain CGPAs within a similar range around the average 7.66, suggesting that sleep durations do not significantly affect overall academic performance

Result 3.

=> The analysis grouped various job titles into 12 fields, revealing that the majority of workers are in the education sector, with nearly 30,000 individuals, while the aviation sector has the fewest, with around 2,500 workers

=> To evaluate the job, 3 categories were used: Job Satisfaction, Financial Stress, and Work Pressure. Each category was rated on a scale from 1 (low) to 5 (high), allowing for a comparative analysis by using the statistical method 'mode' to get the most votes in each profession
- Job satisfaction level: Architecture, Aviation, and Construction sectors reported the highest job satisfaction, scoring a 5 on the satisfaction scale. In contrast, most other fields scored a 2, indicating lower job satisfaction levels
- Work Pressure: Despite Architecture, Aviation, and Construction being among the top three industries with high work pressure, workers in these fields seem to find fulfillment in their jobs. However, this high pressure may negatively impact their mental health
- Financial Stress: The financial stress levels for workers in Architecture, Aviation, and Construction fell within the range of 2, suggesting that these positions offer sustainable income, which contributes positively to the overall quality of life, helping mitigate financial stress

Result 4.

=> Divided our predictive analysis into 2 groups
- Students
- Working Adults

=> Used 5 models to find the best model in predicting depression
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbor (K-NN)

=> Worker model: All models performed above 90% with the best model being SVM and Logistic Regression (Both metrics evaluation being the same)

=> Student model: All models performed poorer than the Worker model, with the best model being SVM (All above 80% except decision tree)

* One possible reason for the poor model performance is class imbalance, as working adults had more data compared to students

# Tools: sklearn, seaborn, matplotlib, pandas, numpy

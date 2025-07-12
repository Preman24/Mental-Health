# Project-Description

Title: Analysing factors influencing mental health among individuals: Machine Learning Approach

Mental health is a crucial aspect of our daily lives, and it’s essential to prioritize our well-being, even amidst the demands of a busy lifestyle that can negatively impact our mental state. To address this issue, a mental health dataset sourced from Kaggle, which includes responses from 147,000 participants, was analyzed. This dataset captures a range of factors affecting mental health through numerical and categorical data. To further explore this topic, four key questions were proposed to guide the analysis.

1. Association between dietary habits and mental health (i.e. depression, suicidal thoughts, Family history of Mental Illness)
2. Analyze the relationship between sleep duration and academic performance (i.e. Academic Pressure, CGPA, Study hours) 
3. Analyze how work pressure affects job satisfaction among different working professionals (i.e. Profession, Job Satisfaction, Financial Stress, Work hours)
4. Comparison of different machine learning models for predicting Depression

# Dataset Description:

| Column Names  | Description |
| :---: | :---: |
| ID                                               | Unique identifier for each participant in the study.              |
| Gender                                           | Gender of the participant (e.g., Male, Female).           |
| Age                                             | Age of the participant in years.                                 |
| Working Professional or Student                  | Indicates whether the participant is a working professional or a student. |
| Profession                                       | Current profession or field of study of the participant.         |
| Academic Pressure                                | Level of pressure experienced by the participant related to academic demands. |
| Work Pressure                                    | Level of pressure experienced by the participant in their work environment. |
| CGPA                                            | Cumulative Grade Point Average of the participant, reflecting academic performance. |
| Study Satisfaction                               | Participant's level of satisfaction with their study experience.  |
| Job Satisfaction                                 | Participant's level of satisfaction with their job or employment situation. |
| Sleep Duration                                   | Average number of hours the participant sleeps per night.        |
| Dietary Habits                                  | Description of the participant's eating patterns and food choices. |
| Degree                                          | Highest degree obtained or currently pursued by the participant.  |
| Have you ever had suicidal thoughts?            | Indicates whether the participant has ever experienced suicidal thoughts (Yes/No). |
| Work/Study Hours                                | Average number of hours spent on work or study each week.       |
| Financial Stress                                | Level of stress experienced by the participant due to financial issues. |
| Family History of Mental Illness                | Indicates if there is a family history of mental illness (Yes/No). |
| Depression                                       | Indicates whether the participant has been diagnosed with depression (Yes/No). |

# Key Findings
Result 1.


Result 4.
Divided our predictive analysis into 2 groups
- Students
- Working Adults

Used 5 models to find the best model in predicting depression
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbor (K-NN)

=> Worker model: All models performed above 90% with the best model being SVM and Logistic Regression (Both metrics evaluation being the same)

=> Student model: All models performed poorer than the Worker model, with the best model being SVM (All above 80% except decision tree)

* One possible reason for the poor model performance is class imbalance, as working adults had more data compared to students

Recommendations:






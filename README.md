# MIS311
Data Analysis and Insight 
## Student Exam Performance Analysis
### Introduction
This report provides an Exploratory Data Analysis (EDA) of the Student Exam Performance dataset. The purpose of the analysis is to examine the factors that may affect students’ academic achievement, especially final exam scores, through the use of descriptive statistics and data visualization methods.

### 1. Data Overview
**Sources of the data**
The dataset used in this analysis is the Student Exam Performance dataset provided for the MIS 311 assignment. 
**Number of rows and columns**
The dataset consists of approximately: 10,001 rows (1 header and 10000 observations) ; 23 columns (23 variables) 
Each row represents a student, and each column represents a specific feature related to academic performance and learning behavior. 

**The context or background of the data.**
The dataset contains information related to students’ demographic background, study habits, lifestyle factors, and academic performance, including key variables such as study hours per day, attendance rate, sleep hours, final exam scores, and grade category. The purpose of the dataset is to examine how different factors may influence students’ academic outcome and overall performance.

### 2. Data Cleaning 
Data cleaning was performed to ensure the dataset was accurate and consistent before analysis. The dataset was checked for missing values, duplicate records, and data type accuracy.

No missing values were found across all 10,000 observations and 23 variables.
No duplicate rows were detected, meaning each record represents a unique student.
Numerical and categorical variables were correctly formatted for analysis.

Overall, the dataset was verified to be clean and ready for statistical analysis and visualization.

### 3. Descriptive Statistics 
Descriptive statistics were used to summarize the main characteristics of the dataset and provide an overview of student performance patterns. 
 
**TABLE 1: Descriptive Statistics of final_exam_score, study_hours_per_day and attendance_rate**
<p align="center">
<img src="Descriptive Statistics.png" width="700">
The average final exam score is about 50, reflecting a moderate level of overall academic performance. On average, students study for approximately 3 hours per day, while the attendance rate stays relatively high at around 84.7 throughout the dataset.

## Insight 1: Study Hours and Final Exam Performance
 
**FIGURE 1: Scatterplot of study_hours_per_day and final_exam_score**
<p align="center">
<img src="Study Hours and Final Exam Score.png" width="700">
The scatter plot shows a positive relationship between study hours per day and final exam scores. Students who spend more time studying generally achieve better examination results. This finding indicates that study habits have a significant impact on academic performance. Regular studying may help students improve their understanding of course materials and increase their chances of obtaining better academic outcomes.

## Insight 2: Attendance Rate and Academic Performance
 
**FIGURE 2: Scatterplot of attendance_rate and final_exam_score**
<p align="center">
<img src="Descriptive Statistics.png" width="700">
The analysis shows a positive relationship between attendance rate and final exam performance. Students with higher attendance rates generally tend to obtain better examination scores than those with lower attendance levels. Regular attendance may support students in understanding lecture content more effectively, participating in classroom activities, and staying engaged in the learning process. This emphasizes the importance of classroom participation in contributing to academic success.
  
**FIGURE 3: Pivot chart of Total Grade Category Distribution **
<p align="center">
<img src="Total Grade Category Distribution.png" width="700">
The distribution of grade categories indicates that the majority of students achieved average performance levels, while a smaller number of students attained the highest grade categories. This distribution provides a general overview of academic achievement in the dataset.
### Implications of the Findings
The findings of this analysis indicate that study habits and classroom attendance are important factors in students’ academic performance. Students who spend more time studying and regularly attend classes generally tend to obtain higher final exam scores. These results suggest that educational institutions may enhance student performance by promoting consistent study routines and encouraging greater participation in classroom activities. Furthermore, offering academic support programs and encouraging effective time management strategies may assist students in achieving better learning outcomes. The analysis also illustrates how data analytics can be applied in the education sector to identify performance patterns and support data-driven decision-making.

### Conclusion
In conclusion, the exploratory data analysis identified several factors related to student academic performance. The findings show that both study hours and attendance rates are positively associated with final exam scores. These results suggest that consistent study habits and regular class attendance are important factors contributing to academic success. The analysis also demonstrates how business analytics techniques, including descriptive statistics and data visualization, can be applied to discover meaningful insights from educational data.
### References
GitHub Docs. (2024). Getting started with GitHub. Retrieved from https://docs.github.com/
GitHub. (n.d.). Start your journey. GitHub Docs. Retrieved from https://docs.github.com/
Course Dataset. (2026). Student Exam Performance dataset [Excel dataset]. MIS 311 – Introduction to Business Analytics, Eastern International University.

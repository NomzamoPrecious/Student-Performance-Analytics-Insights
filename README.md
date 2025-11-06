# Student-Performance-Analytics-Insights

Unlocking Academic Momentum: A Data-Driven Approach to Enhancing 
Student Performance Through Smart Metrics 
1. Problem Statement 
Educational institutions face challenges in identifying key factors that influence student 
performance. Without structured data analysis, it is difficult to: 
• Determine the impact of attendance, study hours, and external factors (e.g., internet 
access, peer influence) on exam scores. 
• Predict which students are at risk of underperforming. 
• Optimize resource allocation (e.g., tutoring, teacher quality) to improve outcomes. 
Student underperformance remains a pervasive challenge across educational institutions, 
especially in environments with varying levels of access to academic support, digital 
infrastructure, and socio-economic stability. While institutions have implemented diverse 
intervention strategies ranging from tutoring programs to parental engagement initiatives, 
many of these efforts fail to produce measurable improvements due to their one-size-fits-all 
approach. Students differ significantly in terms of motivation, study patterns, access to 
learning resources, and personal environments, yet these dimensions are often not 
incorporated into academic performance evaluations. As a result, educators and decision
makers struggle to make data-driven decisions that truly address the root causes of academic 
decline. 
Traditional assessment models typically rely on isolated indicators such as exam scores or 
attendance, overlooking the multi-dimensional nature of academic performance. For example, 
a student with average attendance might still perform poorly due to a lack of internet access 
or insufficient sleep. Similarly, students from low-income households may face challenges 
that inhibit their ability to study effectively at home, despite receiving high-quality 
instruction. Furthermore, factors like family income, parental involvement, peer influence, 
and access to tutoring resources are rarely analysed in conjunction, leading to an incomplete 
understanding of student needs. The absence of an integrated, metric-driven approach results 
in reactive rather than proactive support systems. 
The critical gap lies in the ability to unify academic, behavioural, and environmental data into 
actionable insights that can drive personalized interventions. This project addresses that gap 
by implementing a comprehensive student performance analysis using smart metrics derived 
from diverse data attributes. By analysing variables such as sleep hours, hours studied, 
motivation level, internet access, and prior academic history, the model aims to uncover 
hidden patterns and key predictors of success or failure. The ultimate goal is to empower 
stakeholders, teachers, parents, and policymakers with a deeper, data-backed understanding 
of student challenges, enabling them to unlock academic momentum through precision
targeted strategies. 
This project aims to leverage cleaned and transformed student performance data to 
uncover actionable insights.







3. Objectives 
The primary objective of this project is to develop an intelligent and comprehensive 
analytical model that identifies, evaluates, and explains the key drivers of academic 
performance among students. By using smart metrics and integrated data visualization 
techniques, the model will reveal how academic scores correlate with behavioural, 
environmental, and socio-economic factors. This model will enable educational institutions 
and stakeholders to take strategic actions to improve learning outcomes through data
informed decision-making. 
Specific Objectives: - - - - 
Data Preparation and Feature Engineering 
• Clean and transform raw student performance data using Excel’s advanced 
formulas to derive new categorical features such as Hours_Studied_Range, 
Attendance_Variety, Previous_Scores_Range, and Exam_Scores_Variety. 
• Ensure all data inconsistencies, null values, and formatting issues are resolved 
to maintain data integrity. 
Exploratory and Diagnostic Analysis 
• Analyse student performance in relation to multiple variables including 
attendance, sleep hours, family income, access to internet resources, 
motivation levels, and parental involvement. 
• Use funnel diagrams, bar charts, pie charts, and gauges in Power BI to 
visually compare performance segments and uncover disparities between high 
and low performers. 
Measure Development and Performance Scoring 
• Create calculated fields and Key Performance Indicators (KPIs) such as 
Funnel_Steps, Target_Exam_Score, and group-level metrics to benchmark 
performance. 
• Evaluate students against a set exam target score (85) and use gauges to 
highlight gaps and trends in average performance. 
Correlation and Pattern Recognition Using Python 
• Leverage Python libraries (Matplotlib, Seaborn, Pandas) to visualize complex 
relationships. For example, how internet access modifies the impact of 
tutoring sessions on exam scores. 
• Identify nonlinear trends and interaction effects that Excel or Power BI alone 
may not expose. - - - - 
Segmentation and Comparative Performance Analysis 
• Segment students by study hours, sleep hours, access to resources, and peer 
influence to determine which combinations most strongly associate with 
outstanding marks. 
• Compare academic performance between public and private school students 
and analyse distance from home as a factor. 
Behavioural and Socio-Economic Impact Assessment 
• Quantify the impact of external factors such as parental involvement, family 
income, and peer influence on both previous scores and final exam scores. 
• Assess how internal motivators (motivation level, study commitment) 
combine with external enablers (resources, internet) to shape outcomes. 
Data-Driven Recommendations 
• Generate actionable recommendations based on trends and outliers observed 
in the data. 
• Inform academic planning, such as focusing on improving sleep patterns, 
targeting students with low resource access, and encouraging tutoring 
participation with structured incentives. 
Support for Predictive Strategy and Policy Framing 
• Lay the groundwork for future predictive models that can estimate student 
success probabilities based on observable traits. 
• Guide institutional policy on where to allocate educational resources to 
improve efficiency and student equity.









5. Key Questions to Address 
• What are the most influential factors affecting student exam 
performance? 
This question aims to identify which variables (e.g., hours studied, attendance, sleep, internet 
access, motivation, etc.) have the greatest impact on student outcomes. By using correlations 
and visualization tools, we can distinguish between strong predictors and weaker ones, 
helping educators prioritize interventions. 
• How does internet access influence academic achievement and learning 
consistency? 
This explores the digital divide's effect on performance. Students with internet access often 
have greater exposure to learning resources, tutorials, and practice materials. This question 
helps evaluate whether lack of access is a root cause of poor outcomes and how much of an 
advantage it provides. 
• Is there a measurable academic benefit to attending tutoring sessions? 
This addresses the effectiveness of tutoring support. Do more sessions consistently lead to 
higher scores? Is the benefit uniform across all student categories, or does it depend on other 
variables like motivation or previous scores? 
• How do students' previous academic scores correlate with their final 
exam performance? 
This investigates whether past academic success reliably predicts future performance. If not, 
it may signal issues like a drop in learning momentum, poor exam preparation, or external 
stressors during the exam period. 
• To what extent does peer influence affect student motivation and 
academic behaviour? 
Peer influence can motivate or demotivate learners. This question analyses whether students 
surrounded by supportive peers perform better than those influenced negatively. It can inform 
social programs and mentorship strategies. 
• How does the variety of study hours (less, average, more) relate to 
academic achievement? 
This question breaks down how the amount of time spent studying impacts performance. Are 
students studying “more hours” actually performing better, or is quality of study more 
important than quantity? 
• Do behavioural factors like sleep duration correlate with student 
performance? 
Sleep affects memory retention, focus, and cognitive performance. This question evaluates 
whether students getting less or more than the recommended sleep hours perform worse, 
offering a potential area for wellness intervention. 
• What role does parental involvement play in shaping student 
performance trends? 
Parental involvement is a key social factor in a student’s academic life. This question 
explores how students with high, moderate, or low parental involvement differ in 
performance, revealing opportunities for family engagement strategies. 
• Are there significant differences in academic outcomes between public 
and private school students? 
This compares systemic education delivery. Does school type inherently offer performance 
advantages, or are other intersecting factors (e.g., income, teacher quality) more influential. 
• How many students are reaching the target exam score (85), and where 
are others dropping off? 
This funnel analysis question helps quantify academic drop-offs and gaps. It assesses how 
many students pass through each success filter (e.g., internet access, high-quality teachers, no 
learning disabilities) and reach “Outstanding” performance. It supports data-driven 
prioritization of interventions. 
6. Methodology - Data Cleaning and Transformation (Excel) 
• Removed duplicates and null values. 
• Created new classification columns using formulas for Hours_Range, 
Attendance_Variety, Previous_Scores_Range, and Exam_Scores_Variety. 
➢ Group 1: Study Behaviour Segmentation 
1. Hours_Range Formula: 
=IF([@[Hours_Studied]] < 15, "Less Hours", IF([@[Hours_Studied]] <= 30, "Average 
Hours", "More Hours")) 
Purpose: 
Categorizes students based on their weekly study hours into: 
• Less Hours (< 15 hours): Possibly insufficient engagement. 
• Average Hours (15–30 hours): Baseline effort. 
• More Hours (> 30 hours): High-level dedication. 
Analytical Value: 
Used to correlate study input with exam performance, helping identify whether "time spent" 
directly influences academic success. 
➢ Group 2: Attendance Classification




3. Attendance_VarietyFormula: 
=IF([@Attendance] < 50, "Low Attendance", IF([@Attendance] <= 80, "Moderate 
Attendance", "High Attendance")) 
Purpose: 
Groups students by their attendance percentage: 
• Low Attendance (< 50%): At risk. 
• Moderate Attendance (50–80%): Medium engagement. 
• High Attendance (> 80%): Consistent participation. 
Analytical Value: 
Used to analyse trends between attendance and performance, offering insight into how 
physical presence in class impacts learning outcomes. 
➢ Group 3: Historical Performance Analysis







4. Previous_Scores_Range Formula: 
=IF([@[Previous_Scores]] < 50, "Lowest Score", IF([@[Previous_Scores]] <= 80, "Moderate 
Score", "Highest Score")) 
Purpose: 
Categorizes prior academic performance: 
• Lowest Score (< 50): Historically underperforming. 
• Moderate Score (50–80): Average achievers. 
• Highest Score (> 80): Consistent top performers. 
Analytical Value: 
Allows for longitudinal analysis of performance trends and effectiveness of interventions like 
tutoring. 
➢ Group 4: Final Performance Bands









5. Exam_Scores_Variety Formula: 
=IF([@[Exam_Score]] < 55, "Poor Mark", IF([@[Exam_Score]] < 75, "Intermediate Mark", 
"Outstanding Mark")) 
Purpose: 
Stratifies final exam results into: 
• Poor Mark (< 55): Below average. 
• Intermediate Mark (55–74): Meets minimum expectations. 
• Outstanding Mark (75+): High achievers. 
Analytical Value: 
Key for performance evaluation, benchmarking, and aligning students to intervention 
programs or reward structures. 
➢        Group 5: Performance Benchmarking KPI









6. Target_Exam_Score Definition: 
Target_Exam_Score = 85 
Purpose: 
Sets a performance benchmark against which all students are evaluated. 
Analytical Value: 
Used to track how many students are meeting or exceeding a predefined academic target. 
Supports progress monitoring and success criteria. - 
Metric and KPI Calculation (Power BI – DAX) 
• Built custom measures such as Funnel_Steps and calculated the percentage of 
students reaching each funnel milestone (e.g., Internet Access, High Teacher Quality, 
No Learning Disabilities, Outstanding Marks). 
• Applied conditional formatting and target score gauges to measure how close 
groups are to the desired academic standard. 
Funnel_Steps =  
UNION( 
ROW("Stage", "Total Students", "Count", COUNTROWS('Student Performance Insights')), 
ROW("Stage", "Internet Access = Yes", "Count", CALCULATE(COUNTROWS('Student 
Performance Insights'), 'Student Performance Insights'[Internet_Access] = "Yes")), 
ROW("Stage", "High Teacher Quality", "Count", CALCULATE(COUNTROWS('Student 
Performance Insights'), 'Student Performance Insights'[Teacher_Quality] = "High")), 
ROW("Stage", "No Learning Disability", "Count", CALCULATE(COUNTROWS('Student 
Performance Insights'), 'Student Performance Insights'[Learning_Disabilities] = "No")), 
ROW("Stage", "Outstanding Mark", "Count", CALCULATE(COUNTROWS('Student Performance 
Insights'), 'Student Performance Insights'[Exam_Score_Variety] = "Outstanding Mark")) 
) - 
Data Visualization and Interactive Dashboard (Power BI) 
• Created a vision board with segmented insights by gender, school type, sleep hours, 
parental education, peer influence, and other dimensions. 
• Used slicers, bar graphs, donut charts, line graphs, and a gauge meter to simplify 
complex trends for stakeholders. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 - Advanced Data Visualization (Python) 
• Used Python (Matplotlib, Seaborn) to build a dual-trend line graph comparing 
tutorial sessions and internet access with average exam scores. 
• Identified compound relationships using grouped analysis and improved 
readability with custom plot stylings. 
Trend Analysis: Tutorial Sessions vs Exam Score with Internet Access 
import matplotlib.pyplot as plt 
import seaborn as sns 
import pandas as pd 
 
dataset.columns = dataset.columns.str.strip().str.replace(" ", "_") 
grouped = dataset.groupby(['Tutoring_Sessions', 
'Internet_Access'])['Exam_Score'].mean().reset_index() 
 
sns.set(style="whitegrid") 
 
plt.figure(figsize=(18, 6)) 
sns.lineplot(data=grouped, x='Tutoring_Sessions', y='Exam_Score', hue='Internet_Access', 
marker='o', linewidth=15, palette=['Maroon', 'Goldenrod']) 
plt.title('Trend: Exam Score by Tutorial Sessions and Internet Access', fontsize=26) 
plt.xlabel('Tutorial Sessions Attended', fontsize=25) 
plt.ylabel('Average Exam Score', fontsize=22) 
plt.xticks(fontsize=14) 
plt.yticks(fontsize=14) 
plt.legend(title='Internet Access', fontsize=25, title_fontsize=20) 
plt.tight_layout() 
plt.show() 
1. Scorecard (KPIs) 
KPI 
AVERAGE EXAM SCORE 
VALUE 
AVERAGE OF PREVIOUS SCORES 75.07 
67.24 
TARGET EXAM SCORE 
85 
% STUDENTS WITH INTERNET ACCESS ~86% 
% STUDENTS WITHOUT DISABILITIES 
~86% 
% STUDENTS WITH HIGH TEACHER QUALITY ~29%





5. Hypothesis 
H1: Students with consistent internet access and tutoring sessions perform significantly better 
in exams. 
H2: Students who sleep between 6-8 hours tend to have higher academic performance. 
H3: Motivation level, family income, and parental involvement positively influence student 
performance. 
H4: High attendance and consistent study hours correlate with outstanding exam scores. 
H5: Students with internet access and no learning disabilities achieve higher scores. 
H6: Teacher quality and peer influence significantly impact student motivation and grades.







7. Expected Outcomes 
• Identification of the top performance indicators (e.g., consistent internet access, 
high motivation, peer support). 
• Evidence-based clustering of students into performance tiers (low, average, high) with 
contextual causes. 
• Insights into which variables (e.g., parental involvement, sleep hours, resource access) 
are statistically significant predictors of academic improvement. 
• Clear visual guidance for intervention planning and support prioritization for 
underperforming groups.








8. Analysis and Insights 
1. Exam Score vs. Previous Scores 
• While the average Previous Score stands at 75.07, the Actual Exam Score dropped 
to 67.24, revealing a learning regression. 
• This suggests a knowledge retention issue or external disruption impacting 
performance between assessments.







3. Tutoring Sessions & Internet Access 
• Students with Internet Access and higher participation in Tutorial Sessions 
consistently outperformed others. 
• The Python line graph revealed a strong correlation: more tutorial sessions + internet 
access = higher exam score trajectory.






4. Impact of Peer Influence 
• A balanced distribution of peer influence types showed: 
➢ 39.3% experienced positive peer influence. 
➢ Those with negative or neutral influence had statistically lower average scores.







5. Sleep Hours Correlation 
• Optimal performance is associated with students getting 6–8 hours of sleep. 
• Both short (<5) and long (>9) sleep durations correlated with decreased exam 
performance.







6. Family Income & Parental Involvement 
• High family income and high parental involvement correlate with better academic 
performance. 
• Students with low parental involvement had lower exam scores despite high 
previous scores.






7. School Type Analysis 
• Private school students exhibited slightly higher average scores than public school 
students. 
• However, differences diminished when controlling for other factors like Internet 
Access and Study Hours.






8. Implications for Stakeholders 
For Educators 
• Adjust support interventions based on data trends (e.g., monitor students with low 
sleep or inconsistent study patterns). 
• Use dashboards to proactively support at-risk learners based on predictive indicators. 
For Students 
• Empower students with personal performance insights, especially the link between 
behaviour (study hours, sleep, etc.) and scores. 
• Encourage self-monitoring with study plans, sleep tracking, and academic journals. 
For Parents 
• Encourage active parental involvement in both school activities and home-based 
support. 
• Promote digital literacy among families to close the digital divide in student support.











10.       
Data Preparation Summary 
Tools Used: 
• Excel: Data cleaning, custom column logic (with IF functions), sorting, and 
verification. 
• Power BI: Dynamic dashboards, KPI calculations, visualizations, filters. 
• Python (Matplotlib & Seaborn): Advanced graph plotting and trendline analysis. 
Key Calculated Columns: 
• Hours_Range: Categorized hours studied into “Less,” “Average,” and “More.” 
• Attendance_Variety: Grouped attendance rates into “Low,” “Moderate,” “High.” 
• Previous_Scores_Range: Classified past performance into “Lowest,” “Moderate,” 
and “Highest.” 
• Exam_Scores_Variety: Segmented exam scores into “Poor,” “Intermediate,” 
“Outstanding.” 
Key Measures: 
• Funnel_Steps: Tracks how many students progress through favorable learning 
conditions. 
• Target_Exam_Score: Set at 85 for benchmarking academic excellence. 






10.  Limitations 
1. Sample Representativeness: The dataset may not cover every demographic or 
regional variance in student populations. 
2. Causality: Correlation does not imply causation—external variables may influence 
performance outcomes. 
3. Missing Values & Biases: Some fields such as parental involvement or peer influence 
might be subjective or self-reported, affecting accuracy. 
4. Tutorial Quality: While attendance is measured, the content quality of tutorial 
sessions is not assessed.





11. Future Enhancements 
• Introduce Machine Learning models to predict student performance based on multi
variable inputs. 
• Expand datasets to include emotional and psychological indicators (e.g., stress, 
engagement). 
• Use Natural Language Processing (NLP) to extract sentiment from written student 
feedback or learning journals. 
• Deploy mobile dashboards or portals for real-time performance tracking and 
communication between students, teachers, and parents.






13. Appendix 
A. Visualization Tools: 
• Power BI: Funnel chart, bar chart, pie chart, donut chart, gauge, slicers. 
• Python: Matplotlib & Seaborn for dual-line visualizations. 
B. Data Columns Overview: 
• Exam_Score, Previous_Scores, Hours_Studied, Internet_Access, Sleep_Hours, 
Peer_Influence, Parental_Involvement, Family_Income, School_Type, Attendance, 
Motivation_Level, etc.





14. Recommendations - - - - - 
Enhance Digital Access 
• Provide subsidized or free internet to students, especially those in 
underperforming segments. 
• Encourage hybrid learning models that benefit from online educational tools. 
Invest in Peer-Influence & Motivation Programs 
• Promote mentoring, group study initiatives, and reward systems for positive 
peer collaboration. 
Expand Tutoring Availability 
• Scale tutoring programs and ensure they are accessible regardless of 
household income. 
• Align tutoring content closely with curriculum goals and personal academic 
gaps. 
Parental Engagement Workshops 
• Train and support parents to become more involved in-home learning, 
especially in low-income groups. 
• Use SMS or mobile apps to communicate progress and needs with families. 
Encourage Healthy Sleep and Study Habits 
• Promote awareness campaigns on the benefits of adequate sleep and consistent 
study patterns. 
• Integrate these habits into life skills and wellness education. 
- 
Data Monitoring and Predictive Alerts 
• Implement early-warning dashboards that alert educators to students at risk 
based on trends in hours studied, attendance, and previous scores. 
• Begin pilot programs to test AI-driven interventions using this dataset 
structure.







15. Expected Outcomes 
• Identification of the top performance indicators (e.g., consistent internet access, high 
motivation, peer support). 
• Evidence-based clustering of students into performance tiers (low, average, high) with 
contextual causes. 
• Insights into which variables (e.g., parental involvement, sleep hours, resource access) 
are statistically significant predictors of academic improvement. 
• Clear visual guidance for intervention planning and support prioritization for 
underperforming groups.









16. Conclusion 
This Student Performance Analysis demonstrates how integrating advanced metrics and smart 
visualizations can transform raw academic data into meaningful educational intelligence. By 
combining behavioural, socio-economic, and academic factors, this solution offers a 360
degree view of student challenges and opportunities. The model does not only describe 
performance, it explains it. As such, it can serve as a foundation for educational 
transformation, one that is equitable, data-driven, and personalized. 

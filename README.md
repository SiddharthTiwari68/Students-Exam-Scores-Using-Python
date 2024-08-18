# Students-Exam-Scores-Using-Python

# Objective: 
Analyze the influence of personal and socio-economic factors on student performance in three subjects (Math, Reading, and Writing) and provide insights on how these factors interact with each other.
# Features:
Gender: Gender of the student (male/female)
EthnicGroup: Ethnic group of the student (A, B, C, D, E)
ParentEduc: Education level of the student's parents (some_highschool, high_school, associate’s degree, bachelor’s degree, master’s degree)
LunchType: Type of school lunch received (standard, free/reduced)
TestPrep: Whether the student completed a test preparation course (completed, none)
ParentMaritalStatus: Marital status of the student's parents (married, single, widowed, divorced)
PracticeSport: Frequency of sports practice (never, sometimes, regularly)
IsFirstChild: Whether the student is the first child in the family (yes, no)
NrSiblings: Number of siblings the student has (0-7)
TransportMeans: Means of transport to school (schoolbus, private)
WklyStudyHours: Weekly self-study hours (less than 5 hrs, between 5 and 10 hrs, more than 10 hrs)
MathScore: Math test score (0-100)
ReadingScore: Reading test score (0-100)
WritingScore: Writing test score (0-100)
# Data Preprocessing
Handling Missing Values:
Identify Missing Values: Check for missing values and decide on a strategy for handling them.
Imputation Strategies: Use mean/median for numerical features and mode/frequent value for categorical features.
Data Cleaning:
Consistent Data Types: Convert categorical variables to numerical formats for analysis if needed.
Outlier Handling: Identify and address outliers in numerical features such as MathScore, ReadingScore, and WritingScore.
# Exploratory Data Analysis (EDA)
 Descriptive Statistics:
# Summary Statistics: 
Calculate mean, median, mode, and standard deviation for numerical columns.
# Data Visualization
Bar Charts: Compare average scores across different categories (e.g., Gender, EthnicGroup, ParentEduc).
Box Plots: Visualize the spread of scores by LunchType, TestPrep, and ParentMaritalStatus.
Scatter Plots: Plot WklyStudyHours against scores to identify trends.
Heatmap: Display correlations between features and highlight significant relationships.
Insights and Conclusions
# Key Findings:
Identify significant factors affecting Math, Reading, and Writing scores

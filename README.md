# Jamboree Education
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/ learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.
How can you help here?
Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.
Dataset:
https: //drive.google.com/file/d/1UCnSk_NN02jlzj0bbSZ_j-gdGUDDJxy4/view?usp=sharing
 
 Column Profiling
1. Serial No. (Unique row ID)
2. GRE Scores (out of 340)
3. TOEFL Scores (out of 120)
4. University Rating (out of 5)
5. Statement of Purpose and Letter of Recommendation Strength (out of 5)
6. Undergraduate GPA (out of 10)
7. Research Experience (either 0 or 1)
8. Chance of Admit (ranging from 0 to 1)
Concept Used:
● Exploratory Data Analysis
● Linear Regression
What does good looks like?
● Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset
● Drop the unique row Identifier if you see any. This step is important as you don’t want your model to build some understanding based on row numbers.
● Use Non-graphical and graphical analysis for getting inferences about variables
● This can be done by checking the distribution of variables of graduate applicants
● Once you’ve ensured that students with varied merit apply for the university, you can
start understanding the relation between different factors responsible for graduate
admissions
● Check correlation among independent variables and how they interact with each other
● Use Linear Regression from Statsmodel library and explain the results
● Test the assumptions of linear regression:
o Multicollinearity check by VIF score
o Mean of residuals
o Linearity of variables (no pattern in residual plot) - Optional o Test for Homoscedasticity
o Normality of residuals
● Do model evaluation- MAE, RMSE, R2 score, Adjusted R2
● Provide actionable Insights & Recommendations

 Evaluation Criteria (100 points)
1. Define Problem Statement and perform Exploratory Data Analysis (10 points)
a. b.
c.
d. e.
Definition of problem (as per given problem statement with additional views)
Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), missing value detection, statistical summary.
Univariate Analysis (distribution plots of all the continuous variable(s) barplots/countplots of all the categorical variables)
Bivariate Analysis (Relationships between important variables Illustrate the insights based on EDA
i. Comments on range of attributes, outliers of various attributes
ii. Comments on the distribution of the variables and relationship between
them
iii. Comments for each univariate and bivariate plots
2. Data Preprocessing (10 Points) a. Duplicate value check
b. Missing value treatment
c. Outlier treatment
d. Feature engineering
e. Data preparation for modeling
3. Model building (10 Points)
a. Build the Linear Regression model and comment on the model statistics b. Display model coefficients with column names
4. Testing the assumptions of linear regression model (50 Points)
a. Multicollinearity check by VIF score (variables are dropped one-by-one till none
has VIF>5) (10 Points)
b. Mean of residuals is nearly zero (10 Points)
c. Linearity of variables (no pattern in residual plot) (10 Points)
d. Test for Homoscedasticity (10 Points)
e. Normality of residuals (almost bell-shaped curve in residuals distribution, points
in QQ plot are almost all on the line) (10 Points)
5. Model performance evaluation (10 Points)
a. Metrics checked - MAE, RMSE, R2, Adj R2
b. Train and test performances are checked
c. Comments on the performance measures and if there is any need to improve the
model or not
6. Actionable Insights & Recommendations (10 Points)
a. Comments on significance of predictor variables

 b. Comments on additional data sources for model improvement, model implementation in real world, potential business benefits from improving the model (These are key to differentiating a good and an excellent solution)
Questionnaire:
1. People with higher GRE Scores also have higher TOEFL Scores. (T/F)
2. A student with a higher CGPA has a good LOR. (T/F)
3. What are the top 3 correlated features with the Chance of Admit?
4. Research experience for sure increases a student’s..
a. Chance of Admit b. LOR c. University Rating
5. State the difference between R Squared and Adjusted R Squared.
6. State the difference between Ridge and Lasso.
7. Define MSE and MAE.
8. What are the basic assumptions for a Linear Regression model?
Submission Process:
Type your insights and recommendations in the text editor.
● Convert your jupyter notebook into PDF (Save as PDF using Chrome browser’s Print command), upload it in your Google Drive (set the permission to allow public access), and paste that link in the text editor.
● Optionally, you may add images/graphs in the text editor by taking screenshots or saving matplotlib graphs using plt.savefig(...).
● After submitting, you will not be allowed to edit your submission.

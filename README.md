Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

How can you help here?
Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

**Dataset:**
Dataset Link: jamboree_admission.csv

**Column Profiling:**

	1. Serial No. (Unique row ID)
	2. GRE Scores (out of 340)
	3. TOEFL Scores (out of 120)
	4. University Rating (out of 5)
	5. Statement of Purpose and Letter of Recommendation Strength (out of 5)
	6. Undergraduate GPA (out of 10)
	7. Research Experience (either 0 or 1)
	8. Chance of Admit (ranging from 0 to 1)


**Concept Used:**

 1. Exploratory Data Analysis
 2. Linear Regression

**What does good looks like?**

	1. Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset.
	2. Drop the unique row Identifier if you see any. This step is important as you don’t want your model to build some understanding based on row numbers.
	3. Use Non-graphical and graphical analysis for getting inferences about variables.
		a. This can be done by checking the distribution of variables of graduate applicants.
	4. Once you’ve ensured that students with varied merit apply for the university, you can start understanding the relationship between different factors responsible for graduate admissions.
	5. Check correlation among independent variables and how they interact with each other.
	6. Use Linear Regression from (Statsmodel library) and explain the results.
	7. Test the assumptions of linear regression:
		a. Multicollinearity check by VIF score
		b. Mean of residuals
		c. Linearity of variables (no pattern in residual plot)
		d. Test for Homoscedasticity
		e. Normality of residuals
	8. Do model evaluation- MAE, RMSE, R2 score, Adjusted R2.
	9. Provide actionable Insights & Recommendations
 10. Try out different Linear Regressions

**Evaluation Criteria (100 Points):**

1. Define Problem Statement and perform Exploratory Data Analysis (10 points)
	1. Definition of problem (as per given problem statement with additional views)
	2. Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required) , missing value detection, statistical summary.
	3. Univariate Analysis (distribution plots of all the continuous variable(s) barplots/countplots of all the categorical variables)
	4. Bivariate Analysis (Relationships between important variables such as workday and count, season and count, weather and count.
	5. Illustrate the insights based on EDA
		a. Comments on range of attributes, outliers of various attributes
		b. Comments on the distribution of the variables and relationship between them
Comments for each univariate and bivariate plots

		
**2. Data Preprocessing (10 Points)**
	1. Duplicate value check
	2. Missing value treatment
	3. Outlier treatment
	4. Feature engineering
	5. Data preparation for modeling

**3. Model building (10 Points)**
	1. Build the Linear Regression model and comment on the model statistics
	2. Display model coefficients with column names
	3. Try out Ridge and Lasso regression

**4. Testing the assumptions of the linear regression model (50 Points)**
1. Multicollinearity check by VIF score (variables are dropped one-by-one till none has VIF>5) (10 Points)
2. The mean of residuals is nearly zero (10 Points)
3. Linearity of variables (no pattern in the residual plot) (10 Points)
4. Test for Homoscedasticity (10 Points)**
5. Normality of residuals (almost bell-shaped curve in residuals distribution, points in QQ plot are almost all on the line) (10 Points)

**5. Model performance evaluation (10 Points)**
	1. Metrics checked - MAE, RMSE, R2, Adj R2
	2. Train and test performances are checked
	3. Comments on the performance measures and if there is any need to improve the model or not

**6. Actionable Insights & Recommendations (10 Points)**
	1. Comments on significance of predictor variables
	2. Comments on additional data sources for model improvement, model implementation in real world, potential business benefits from improving the model (These are key to differentiating a good and an excellent solution)

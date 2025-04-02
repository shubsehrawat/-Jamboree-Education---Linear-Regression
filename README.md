# -Jamboree-Education---Linear-Regression
Linear Regression Technique on the Jamboree Dataset

## About
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problemsolving methods ensure maximum scores with minimum effort. They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

## Column Profiling:
* Serial No. (Unique row ID)
* GRE Scores (out of 340)
* TOEFL Scores (out of 120)
* University Rating (out of 5)
* Statement of Purpose and Letter of Recommendation Strength (out of 5)
* Undergraduate GPA (out of 10)
* Research Experience (either 0 or 1)
* Chance of Admit (ranging from 0 to 1)

## Problem Statement :
Analysis to help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.


## Summary of the Regression Techniques Employed:
1. By conducting regression analysis, it's evident that CGPA emerges as the most influential feature in predicting admission chances. Additionally, GRE and TOEFL scores also hold significant importance.
2. Following the initial regression model, a thorough check for multicollinearity was performed, revealing VIF scores consistently below 5, indicative of low multicollinearity among predictors.
3. Despite the absence of high multicollinearity, it's noteworthy that the residuals do not conform perfectly to a normal distribution. Furthermore, the residual plots indicate some level of heteroscedasticity.
4. After exploring regularized models such as Ridge and Lasso regression, showed comparable results to the Linear Regression Model.
5. All the assumptions of the Linear Regression Model hold True
## Recommendation
1. Encourage students to focus on improving GRE scores, CGPA, and Letters of Recommendation (LOR), as these factors influence your chances of admission.
2. Beyond academic metrics, applicants can also add, like extracurricular achievements, personal statements, and diversity factors.
3. We can enhance our predictive model by adding other important and diverse features like work experience, internships, or extracurricular activities.

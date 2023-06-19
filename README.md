# lead_scoring
Lead_scoring is a case study which focus on the quality of lead for an edicational company X Education

Logestic Regression: The logestic regression model is a statistical model that models the probability of an event be a linear combination,it predicts the probability of a binary outcome based on input variables. It estimates the relationship between the dependent variable and independent variables by fitting a logistic function to the data.

contents: 
1.Lead_scoring_caseStudy_final.ipynb - conatins the jupiter notebook  with the complete code of the case study.
2.Summary_lead_Scoring_CaseStudy - contains the summary of the case study.
3.assignment subjective question answer - contains the answers of the sujective questions of the case study by IIITB and Upgrad.
4.lead_scoring_CaseStudy_Presentation - contains the presenation which comprises the expalinantion of the various methods used.

introduction:
problem statement of X-Eucation company:
•X Education sells online courses to industry professionals.
•X Education gets a lot of leads, its lead conversion rate is very poor.
•For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted.
•To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’.
•If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

Business objective of the company:
•X Education wants to know most promising leads.
•For that they want to build a Model which identifies the ‘Hot Leads’.
•Deployment of the Model for the future use. 

Solution methodology:
•EDA
1.Check and handle duplicate data
2.Check and handle NAN values and missing values
3.Drop columns, if it contains large amount of missing values and are not useful for the analysis
4.Imputation of the values, if necessary
5.Check and handle Outliers in data
•Feature Scaling and Dummy Variables
•Classification Techniques: Logistic Regression used for the model making and prediction

Methodology:
RFE estimator used in this model is logistic regression
ROC curve to determine optimal probability cut-off.

Conclusion and Recommendation:
•Looking at the below variables, we should be able to help X-Education company with finding out hot leads which will be very high potential customers:-
1.TotalVisits
2.The total time spend on the Website
3.Lead Origin_Lead Add Form
4.Lead Source_Direct Traffic
5.Lead Source_Google
6.Lead Source_Welingak Website
7.Lead Source_Organic Search
8.Lead Source_Referral Sites
9.Lead Source_Welingak Website
10.Do Not Email_Yes
11.Last Activity_Olark Chat Conversation
12. Last Activity_Email Bounced
•Taking the above details into consideration and using this model, the X-Education company can maximise the sales of their course and also generate an excellent revenue.


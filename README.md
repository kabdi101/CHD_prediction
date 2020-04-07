Analyzing and Predicting the Probability of Developing Chronic Heart Disease
Using Framingham Heart Study Dataset


Heart disease is the leading cause of death for men, women, and people of most racial and ethnic groups in the United States. Heart disease costs the United States about 219 billion dollars each year from 2014 to 2015. Analyzing and predicting the likelihood of developing CHD could help greatly in implementing prevention strategies to decrease the occurrence of CHD and therefore reducing the number of deaths in the US and the cost

Exploratory data analysis findings:

- Men are more likely to be diagnosed with CHD than women because men smoke more cigarettes per day
- Current smokers are more likely to be diagnosed with CHD
- Factors such as age, number of cigarettes per day, blood pressure, and glucose levels show likelihood of being diagnosed with CHD
- Factors such as cholesterol levels and body mass index show less likelihood of being diagnosed with CHD


Logistic regression finding: 

- The Logistic regression model show a prediction accuracy of 0.853, with 95% confident that the validation score lies between 0.827 and 0.878
- The AUC value is 0.75 indicating that the model's distinguish ability is acceptable
- The logistic regression model show that systolic pressure is the variable with the most influence on TenYearCHD. However, it will used as an indication of CHD problem rather than a factor. Variables such as age, glucose levels, and cigarettes per day are factors that affect the target variables TenYearCHD


Suggestions:

- Increasing the number of entries could help improve the prediction
- Including more variables such as family history with CHD, race , fasted glucose levels, level of activity, and diet would help with understanding CHD and implementing prevention protocols

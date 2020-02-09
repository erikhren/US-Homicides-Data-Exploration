# US-Homicides-1980-2014

**Project Description**
This project is descriptive in nature with the focus on exploring different ways to visualize the data. Data scientist got to know their data to formulate a vaiable problem statement which serves as a stepping stone for building more advanced machine learning models. However, many things can be learned just by building different graphs and statistical models. 

For instance, in our case we can learn that homicides rates have been sharply declining, the US perpetrators and victims age have decreased, and did you know that most homicides happen in the summer months? Moreover, this might have a slight influence on why the southern states have generally higher homicide rates. 

There is much more to learn from this notebook but the problem we focused on is whether it is possible to predict based on the victim data whether the crime will be solved or not. The main factors that drove us to explore this further were rather controversial but we were curious.
   - significantly larger unknown perpetrator values for whites and victim values for African-Americans 
   - about 90% of the unknown values were linked to unsolved cases
   - approximately 60% of the murder cases get solved (Although, the FBI considers a murder case solved only after the perpetrator is sentenced)
   
Towards the end of the project we built a simple baseline decision tree model to try to predict whether the case will be solved or not.  

**Goin Forward**<br>
To enhance the accuracy of our model we aim to improve the entire CRISP-DM cycle. This includes, testing different techniques for data imputation, normalization, standardization, discretization, data reduction, and algorithm models (random forest, XGboost etc.). 

**Data Source and Content**

The Murder Accountability Project is the most complete database of homicides in the United States currently available. This dataset includes murders from the FBI's Supplementary Homicide Report from 1976 to the present and Freedom of Information Act data on more than 22,000 homicides that were not reported to the Justice Department. This dataset includes the age, race, sex, ethnicity of victims and perpetrators, in addition to the relationship between the victim and perpetrator and weapon used.

Source: https://www.kaggle.com/murderaccountability/homicide-reports

**Acknowledgements**

The data was compiled and made available by the Murder Accountability Project, founded by Thomas Hargrove. 

**Dataset Information**

The homocide dataset consists of 24 columns and 638,454 rows each. Here are the explanations for each column:
1. The record ID (Unique identifier)
2. Year and Month (The year and month of the given report, ranging from year 1980-2014)
3. Incident (How many incidences occured for the specific features e.i. year, month, perpetrator age...)
4. Victim Age 
5. Perpetrator Age (contains ages of the perpetrators where 0 mean unknown or missing) 
6. Victim Count and Perpertrator Count (start with zero and have a maximum value of 10) 
7. Agency code (a six-digit alphanumeric code used to classify accounts by the federal or non-federal agency)
8. Agency name
9. Agency type 
10. City & State
11. Victim & Perpetrator sex
12. Victim & Perpetrator ethnicity (Unknown, Not Hispanic, Hispanic)
13. Victim & Perpetrator race (Native American/Alaska Native, White, Black, Unknown, Asian/Pacific Islander)
14. Relationship (Victim of a crime i.e. Son) 
15. Crime type (Murder or Mansloughter or Mansloughter by negligence)
16. Crime solved 
17. Weapon 
        
**Project Steps**<br>
1. Data Exploration<br>
    * Overview and understanding of the data<br>
    * Finding Errors<br>
2. Data Cleaning<br>
    * Clean the data and prepare it for viziulization<br>
    * Expect an extensive cleaning operation<br>
3. Subsetting & viziulization<br>
    * For the US  <br>
4. Decision Trees<br>
    * Encode data<br>
    * Decision tree model<br>
5. Going Forward<br>

**Python Package Glossary**

Pandas - Free software for Python that is used for data manipulation and visualization

Numpy - Is a library for Python that brings high-level mathimatical functions to support arrays and matrices

Matplotlib - Is a 2D plotting library for Python that produces high quailty plots, histograms, power spectra, bar charts, errorcharts, and scatterplots

Seaborn - Is a Python data visualization library based on Matplotlib. We utilized this to make statistical graphs more pleasing to the eye

Missingno - Missingno provides a small toolset of flexible and easy-to-use missing data visualizations and utilities that allows you to get a quick visual summary of the completeness (or lack thereof) of your dataset

sklearn - provides many unsupervised and supervised learning algorithms

IPython - is an interactive command-line terminal for Python. ... In other words, IPython is a powerful interface to the Python language

pydotplus - is an improved version of the old pydot project that provides a Python Interface to Graphviz’s Dot language

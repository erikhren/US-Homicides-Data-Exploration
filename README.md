# US-Homicides-1980-2014

**Data Source and Content**

The Murder Accountability Project is the most complete database of homicides in the United States currently available. This dataset includes murders from the FBI's Supplementary Homicide Report from 1976 to the present and Freedom of Information Act data on more than 22,000 homicides that were not reported to the Justice Department. This dataset includes the age, race, sex, ethnicity of victims and perpetrators, in addition to the relationship between the victim and perpetrator and weapon used.

Source: https://www.kaggle.com/murderaccountability/homicide-reports

**Acknowledgements**

The data was compiled and made available by the Murder Accountability Project, founded by Thomas Hargrove. 

**Dataset Information**

The homocide dataset consists of 24 columns and 638,454 rows each. Here are the explanations for each column:<br>
1. The record ID<br>
    * Sequentially numbers the report (i.e. 1,2,3...)<br>
2. Year and Month<br>
    * The year and month of the given report, ranging from year 1980-2014<br><br>
3. Incident <br>
    * How many incidences occured for the specific features (e.i. year, month, perpetrator age...)<br>
4. Victim Age<br>
    * contains ages of the victims <br>
5. Perpetrator Age<br>
   * contains ages of the perpetrators where 0 mean unknown <br>
6. Victim Count and Perpertrator Count <br>
   * start with zero and have a maximum value of 10 <br>
   * tells us about the number of victims and perpetrators involved in a particular incident <br> 
7. Agency code <br>
   * is six-digit alphanumeric code used to classify accounts by the federal or non-federal agency. <br>
   * The alpha part of the code is the parent or major agency. The numeric part of the code identifies the sub-agency.<br>
8. Agency name<br>
   * Name of the agency handling the case(s)<br>
9. Agency type <br>
   * Type of the agency handling the case(s)<br>
10. City & State <br>
11. Victim & Perpetrator sex<br>
   * Male or Female<br>
12. Victim & Perpetrator ethnicity<br>
   * Unknown, Not Hispanic, Hispanic<br>
13. Victim & Perpetrator race<br>
   * Native American/Alaska Native, White, Black, Unknown, Asian/Pacific Islander<br>
14. Relationship<br>
   * Victim of a crime (i.e. Son) <br>
15. Crime type<br>
   * Murder or Mansloughter<br>
   * Mansloughter by negligence<br>
16. Crime solved<br>
   * Whether the crime was solved or not<br>
17. Weapon<br>
   * The weapon the crime was committed with <br>
        
**Project Steps**<br>
1. Data Exploration<br>
    - Overview and understanding of the data<br>
    - Finding Errors<br>
2. Data Cleaning<br>
    - Clean the data and prepare it for viziulization<br>
    - Expect an extensive cleaning operation<br>
3. Subsetting & viziulization<br>
    - For the US  <br>
4. Decision Trees<br>
    - Encode data<br>
    - Decision tree model<br>
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

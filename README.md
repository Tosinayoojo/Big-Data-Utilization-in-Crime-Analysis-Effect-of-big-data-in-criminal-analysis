# Big Data Utilization in Crime Analysis: Effect of big data in criminal analysis
1. This report aims to discuss the effects of big data solutions in criminal analysis using historical data provided by the UK government of crimes commited in different financial years.
2. The report covers the usage of different big data technologies such as pandas, spark, sparksql,hive, mapreduce, and machine learning models for outlier detection, correlation analysis, and prediction.

## Executive Summary
This report critically examines provided datasets which include criminal analysis across various financial years. The primary objective of the documentation is to explain the relationship within the datasets and also point out the relationship between big data and crime analysis. It aims to draft research questions after carefully reviewing the given dataset, perform some calculations on the dataset, and provide solutions to research questions. 
In addition to addressing the research questions, the report focuses on the challenges associated with the use of big data solutions and the solutions provided in crime analysis. Upon highlighting the challenges, it offers strategic solutions adopted to mitigate against the known challenges. The approach used in the report ensures a thorough examination of the subject field, infusing both theoretical insights with practical knowledge.

## Dataset Overview
The dataset consists of multiple worksheets compiled into a single criminal workbook, spanning 13 financial years from 2012 to 2023. Each financial year contains approximately 27,000 rows and 8 columns with the following fields: Financial Year, Financial Quarter, Force Name, Offence Description, Offence Group, Offence Subgroup, Offence Code, and Number of Offences.

For this project, I focused on the workbooks from the financial years 2014-15, 2015-16, 2021-22, and 2022-23. The selected worksheets were merged into a single comprehensive worksheet to streamline data access, cleaning, and preprocessing activities. This consolidation facilitates efficient management and analysis of the data, ensuring a more effective workflow for subsequent data processing and insights generation..

## Research Questions
The following research questions below have been carefully drafted after an extensive review of the datasets provided. The aim is to address the positive and negative effects of big data analytics in crime analysis.
1.	What are the most common types of offenses recorded in the database? What are the top five offenses in the dataset and what relevance does that cover in the criminal analysis?
Anser: The figure above provides a solution to the research question 1.
The most common types of offenses are:
•	Violence against the person
•	Theft offenses
•	Sexual offenses
•	Robbery
•	Public order offense

The top five offenses are:
•	Theft Offence
•	Violence against the person
•	Fraud Offenses
•	Criminal damage offenses
•	Public order offenses
Using this in crime analysis can help while performing predictive analysis to find the prevalent type of offense. It can also help government officials plan how to allocate resources and better tackle criminal organizations within an area


3.	What force made the most arrests across all the financial years and in what financial year did they make the most arrest?
Answer: The metropolitan police force made the most arrests in all the financial years where most of the arrest was made in the year 2022/23

5.	Are there any inconsistencies or anomalies in the data that need to be addressed to improve the data integrity? What technologies were adopted to ensure data reliability and robustness to provide meaningful contributions?
Answer: The inconsistencies or anomalies identified in the dataset were addressed using different solution methods across the notebook. Duplicates were handled using pandas, Null values were handled, and columns were dropped using spark. The report then proceeds to show how to handle outliers and perform map-reduce functionalities using the Functools function.

7.	What analytical approach proves most effective in predictive modelling for anticipating the frequency and nature of offenses, and how can this method be optimally applied to enhance proactive law enforcement strategies?
Answer: Given the predictive analysis being done is for several offenses, the regression model is adopted to predict the number of offenses and also determine the best model to use with the least number of errors involved.

## Big Data Technologies Used
Some of the technologies adopted to answer the research questions include:
•	the use of python, 
•	Pandas, 
•	Spark, 
•	Spark SQL,
•	Hive
•	Correlations,
•	Map Reduce
•	Machine Learning for predictive analytics, 
•	Tableau for Visualizations.

## Conclusion
Big data utilization has become a major component of the crime analysis process. Different sectors have been adopting big data technologies which has led to an increase in efficiency and effectiveness and the crime sector is no different. Big data technology has been adopted in crime analysis, from crime patterns and predictions and automating the fraud detection process.
This report adopts a CRISP_DM methodology to answer the research questions and also a systematic review methodology to examine the challenges and solutions associated with the introduction of big data technologies.
The document examines the datasets, highlights the issues associated with working with the datasets, and provides solutions adopted to handle the issues. The report emphasizes the importance of big data technologies in crime analysis bringing us to a conclusion that there are more benefits to the introduction of big data solution.


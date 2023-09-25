# Data Analyst

#### Technical Skills: Python, SQL, Sqlalchemy, Apache Spark, Tableau, Microstrategy

## Work Experience
**Account Planner @ Fanatics, Inc. (_2022 - 2023_)**
- Engineered responsive plans for multimillion-dollar portfolios including Fortune 35 companies, Target & Costco, with a keen eye for customization and future optimization.
- Automated forecasting for league and account performance, and future unit purchases using Python, while conducting comprehensive financial data analysis, leveraging MicroStrategy for data querying and SQL for data 
  management, enhancing overall efficiency and accuracy.

**Sales Analyst @ Fanatics, Inc. (_2019 - 2022_)**
- Administered and grew multimillion-dollar portfolios for key accounts by +3% YoY, leveraging data-driven, cost-effective strategies. 
- Streamlined customer relations management through effective data analysis of customer interactions, utilizing MicroStrategy.

**Retail Sales Merchandiser @ Advantage Solutions (_2018 - 2019_)**
- Oversaw and optimized retail sales by analyzing client product performance, ensuring sales volume increase for leading brands across various categories. 
- Demonstrated keen attention to detail and effective time management skills, managing multiple tasks simultaneously and adapting to changing demands and priorities.


## Education							       		
- M.S., Business Analytics & Information Systems | University of South Florida (_2023 - Current_)	 			        		
- B.S., Consumer Economics | University of Georgia (_2009-2013_)
   - Member of the National Society of Collegiate Scholars


## Certifications							       		
- Data Science	| Rutgers University (_2022 - 2023_)
  - Improved Python and SQL programming skills
  - Gained experience in real-world processes using ETL, Big Data, and Machine Learning



## Projects
### [Home Sales](https://github.com/bauzaj/Home_Sales)
This project is dedicated to the analysis of home sales data utilizing the powerful data processing capabilities of Spark. The notebook begins with the setup of the Spark environment, ensuring all necessary packages and dependencies, including findspark, are appropriately installed and configured. The core data is sourced from an AWS S3 bucket, demonstrating familiarity with cloud-based storage solutions. The data is loaded into a Spark DataFrame, which serves as the foundation for the subsequent analyses. The analyses includes EDA and advanced analyses that may encompass time series, regression, or clustering. The project culminates with insights derived from the data, providing actionable recommendations or observations about home sales trends.

![BarChart](/assets/img/homesales.png)  

![Code](/assets/img/pyspark.png)



### [Credit Risk](https://github.com/bauzaj/credit-risk-classification)
This project focuses on the classification of credit risks by analyzing lending data and utilizing machine learning techniques, specifically logistic regression. The script commences with the import of essential Python libraries such as numpy, pandas, and relevant functionalities from sklearn. Lending data is loaded from a CSV file into a Pandas DataFrame, which is then separated into features and a target variable, 'loan_status', indicating whether a loan is "Healthy" or "High Risk". The dataset is subsequently partitioned into training and testing subsets. Before modeling, features are standardized to ensure they share a common scale.

A logistic regression model is initially trained using the original, non-resampled data. The model's performance is evaluated on both the training and testing datasets. To address potential class imbalances, the script introduces oversampling techniques via the RandomOverSampler from the imblearn library. A new logistic regression model is then trained using this resampled data, and its efficacy is gauged using metrics such as the balanced accuracy score, confusion matrix, and a comprehensive classification report. Results suggest that the model trained with oversampled data adeptly differentiates between "Healthy" and "High Risk" loans, albeit with slightly diminished performance for the "High Risk" category.

![Image](/assets/img/risk.png)

![Code](/assets/img/regress.png)


### [Food and Health](https://github.com/bauzaj/Eat-Health-Module)
The "Eat Healthy" project is a comprehensive data analysis and visualization effort that delves into health metrics based on the ATUS Eating & Health (EH) Module. The EH Module was implemented from 2006 to 2008 and then resumed from 2014 to 2016. It offers detailed insights into patterns related to eating, meal preparation, and health. While data for 2015 is currently under processing and is expected to be released soon, the data collection plan extends until December 2016. Technologies used: 1) Pandas for data cleaning & manipulation. 2)Sqlalchemy to load data into PostgresSQL. 3) Flask API for fetching data. 4) Plotly for interactive browser visualizations.


![Flask_Visual](/assets/img/bmi2.png)  

![Flask](/assets/img/flaskapi.png)


### [Crowdfunding](https://github.com/bauzaj/Crowdfunding_Analysis)
This project is aimed at extracting, transforming, and loading data from various sources into a relational database using Python, Pandas, and SQLalchemy. The project involves processing data from four different sources, including crowdfunding.xlsx, contacts.xlsx, and two CSV files created from the xlsx files. The data is processed in stages, with each stage involving a different set of tasks. The extracted data is cleaned, transformed, and merged, then loaded into the PostgreSQL database. The result is a well-organized relational database that is easy to query for analytical purposes.



![Categories](/assets/img/crwd.png)

![Cat_Code](/assets/img/crwdqry.png)

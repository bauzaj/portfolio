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
- M.S., Business Analytics and Information Systems**<br>
University of South Florida, 2023 - Current 			        		
-B.S., Consumer Economics**<br>
University of Georgia, 2009 - 2013  
- Member of the National Society of Collegiate Scholars


## Certifications							       		
- Data Science	| Rutgers University (_2022 - 2023_)
  - Improved Python and SQL programming skills
  - Gained experience in real-world processes using ETL, Big Data, and Machine Learning



## Projects
### [Home Sales](https://github.com/bauzaj/Home_Sales)
This project was designed to demonstrate advanced competency in leveraging Spark for in-depth analysis of home sales data. The process initiated with the meticulous configuration of the Spark environment, ensuring seamless integration of essential packages, notably findspark. Core data was sourced directly from an AWS S3 bucket, underscoring expertise in engaging with cloud storage solutions. Once ingested, the data was structured into a Spark DataFrame, establishing the foundation for robust analytical procedures. The analytical scope spanned Exploratory Data Analysis (EDA) and extended to specialized techniques such as time series, regression, and clustering analyses. The endeavor culminated in extracting insightful conclusions from the dataset, presenting actionable intelligence and discerning commentary on the dynamics of home sales trends.

![BarChart](/assets/img/homesales.png)  

![Code](/assets/img/pyspark.png)



### [Credit Risk](https://github.com/bauzaj/credit-risk-classification)
This initiative was architected to harness advanced machine learning methodologies, notably logistic regression, for the precise classification of credit risks derived from comprehensive lending data. The analytical framework was primed with the integration of pivotal Python libraries, including numpy, pandas, and select modules from sklearn. The lending dataset, sourced from a CSV file, was structured into a Pandas DataFrame and meticulously segmented into defining features and the pivotal target variable, 'loan_status', demarcating loans as either "Healthy" or "High Risk". To ensure rigorous model training, the dataset underwent stratification into distinct training and testing cohorts. Prior to modeling, a normalization procedure was executed on features to align them to a uniform scale.

The preliminary phase of modeling employed a logistic regression trained on the original dataset. The model's efficacy was rigorously assessed against both training and testing subsets. Recognizing the challenges posed by class imbalances, the analytical script incorporated oversampling strategies using the RandomOverSampler from the imblearn suite. A refined logistic regression model, trained on this augmented dataset, was subsequently evaluated through metrics like the balanced accuracy score, confusion matrix, and a detailed classification assessment. The empirical findings underscored the model's proficiency in distinguishing between "Healthy" and "High Risk" loan categories, with a nuanced observation of marginally reduced performance in identifying the "High Risk" segment.

![Image](/assets/img/risk.png)

![Code](/assets/img/regress.png)


### [Food and Health](https://github.com/bauzaj/Eat-Health-Module)
The "Eat Healthy Dashboard" serves as a vivid demonstration of proficiency in both backend and frontend development. Drawing from a PostgreSQL database, the backend, developed using Flask and sqlalchemy, provides meticulously crafted API endpoints, offering insights into health metrics such as average BMI, general health, and exercise frequency. This data-driven approach ensures that users receive accurate and meaningful insights.

On the frontend, the dashboard exhibits a keen sense of design aesthetics and user experience. Utilizing sophisticated visualization libraries like Plotly and D3.js, it presents data in an interactive and dynamic manner. The design, rooted in CSS, ensures clarity and interactivity, allowing users to uncover patterns and make informed decisions about health and dietary choices. This blend of a robust backend with an intuitive frontend underscores the project's holistic approach to web development.


![Flask_Visual](/assets/img/bmi2.png)  

![Flask](/assets/img/flaskapi.png)


### [Crowdfunding](https://github.com/bauzaj/Crowdfunding_Analysis)
This project exemplifies a systematic approach to data integration, harnessing the capabilities of Python, Pandas, and SQLalchemy to streamline the extraction, transformation, and loading (ETL) of data into a relational database. With data sourced from multiple files, including crowdfunding.xlsx and contacts.xlsx, as well as derivative CSVs, the project orchestrates meticulous processing workflows tailored for each dataset. The data undergoes rigorous cleaning and transformation before converging into the PostgreSQL environment. The culmination is a structured relational database, primed for efficient querying and insightful analytics.



![Categories](/assets/img/crwd.png)

![Cat_Code](/assets/img/crwdqry.png)

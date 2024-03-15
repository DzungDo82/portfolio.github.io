# Dzung Do - Data Portfolio

## About me

Hi, I'm Dzung Do! As a strong data analytics and science professional, I possess profound skills in Python, SQL, Power BI, Tableau, Excel, and AWS. Utilizing advanced tools, I inform strategic decisions and foster innovation by deriving actionable insights from analytical methods and predictive models. Committed to teamwork, excellence, and exceeding expectations, I bring a dedicated and collaborative approach to any project, ensuring the seamless integration of data-driven solutions.

Welcome to my portfolio website:
https://dzungdo82.github.io/portfolio.github.io/

Or feel free to explore my Key Portfolio Projects on my GitHub.

- [Machine Learning, Deep Learning and Big Data projects - using SQL, Python, Spark, and AWS](#machine-learning-deep-learning-and-big-data-projects-using-sql-python-spark-and-aws)
	+ [Customer Churn Prediction in Telecom](#customer-churn-prediction-in-telecom)
	+ [Click-Through Rate (CTR) project](#click-through-rate-ctr-project)
	+ [Profit Forecasting of the online store](#profit-forecasting-of-the-online-store)
	+ [E-Commerce sales (Customer-Centric Business Intelligence)](#e-commerce-sales-customer-centric-business-intelligence)
	+ [Twitter Sentiment Analysis](#twitter-sentiment-analysis)

- [Visualization and Analysis projects - using Excel, Power BI, and Tabbleau](#visualization-and-analysis-projects-using-excel-power-bi-and-tabbleau)
	+ [Sales Data of Online Sport Store](#sales-data-of-online-sport-store)
	+ [Sales Data of Online Supermarket](#sales-data-of-online-supermarket)
	+ [Employee Performance Metrics](#employee-performance-metrics)
	+ [Uber Density in New York](#uber-density-in-new-york)

- [SQL projects](#sql-projects)
	+ [Airbnb listings Analysis](#airbnb-listings-analysis)
	+ [Movie Rental Stores Analysis](#movie-rental-stores-analysis)
	+ [Retail Loyalty Program Analysis](#retail-loyalty-program-analysis)

- [Education](#education)
  
- [Contacts](#contacts)

## 1. Machine Learning, Deep Learning and Big Data projects - using SQL, Python, Spark, and AWS
In this section, I will outline the processes for implementing machine learning, deep learning, and Big Data projects based on my experience with each project.

### 1.1 Customer Churn Prediction in Telecom
**- Link:** [`Telecom_Churn`](https://github.com/DzungDo82/TeleChurn)    
**- Description:** Developed and implemented predictive analytics models for customer churn, with a focus on identifying and prioritizing potential defectors for targeted customer retention efforts.  
**- Skills:** Loading the data, Exploratory Data Analysis (EDA): data visualization - correlation heatmap, correlating categorical features, and correlating numerical features, Feature engineering, Model training - Spliting (train and test dataset), evaluating important levels of features for each model, grid search, scaling, baseline model comparison,  pipeline, sampling, and combining sacler, sampler and model.<br>
**- Technology:** Python - Pandas, Numpy, Seaborn, Matplotlib, scikit-learn preprocessing, metrics, and models (Imbalanced-learn, F1 score, accuracy score, confusion matrix, Logistic Regression, Decision Tree, KNeighbors, XGBoost, Random Forest, etc.)<br>
**- Results:** Selected 75% of relevant features for model training and achieved a 96% predictive accuracy with the Random Forest Classifier.

### 1.2 Click-Through Rate (CTR) project
**- Link:** [`Click-Through Rate`](https://github.com/DzungDo82/Click-Through-Rate) <br>
**- Description:** Measured the click-through rate by comparing the number of clicks on an ad within the payment app to the number of impressions it received.<br>
**- Skills:** Designed table schemas, assembled a modeling dataset of over 2 million rows, connected two tools, loaded data, conducted feature engineering, binning, visualization, data cleaning, and model training.<br>
**- Technology:** SQL, Python - SQL Alchemy, Pandas, Numpy, Seaborn, Matplotlib, scikit-learn preprocessing, metrics, and models (Imbalanced-learn, F1 score, accuracy score, confusion matrix, Logistic Regression, Decision Tree, KNeighbors, XGBoost, Random Forest, etc.)<br>
**- Results:** Skilled in handling imbalanced datasets (92% vs. 8%) and discovered the optimal combination of Standard Scaler + SMOTE + Random Forest Classifier, achieving a predictive accuracy score of 73%.

### 1.3 Profit Forecasting of the online store
**- Link:** [`Profit Forecasting`](https://github.com/DzungDo82/Profit_Forecasting) <br>
**- Description:** Aimed to employ time series forecasting techniques to predict sales and profit, leveraging the patterns and characteristics extracted from the time series analysis of the superstore's historical data.<br>
**- Skills:** Studied forecasting methods and subsequently analyzed the concepts, pros, and cons of time series models.<br>
**- Technology:** Python - applied ARIMA (AutoRegressive Integrated Moving Average) and SARIMA (Seasonal AutoRegressive Integrated Moving Average) models to predict the profit for the next year.<br>
**- Results:** Studied a new concept - forecasting methods, and subsequently analyzed the concepts, pros vs. cons of time series, successfully applying new models from start to finish the project within 2 weeks.

### 1.4 E-Commerce sales (Customer-Centric Business Intelligence)
**- Link:** [`Customer metrics - RFM`](https://github.com/DzungDo82/Ecommerce_RFM) <br>
**- Description:** Leveraged the E-Commerce dataset, conducted customer segmentation to optimize marketing strategies and uncover insights into sales trends, customer behavior, and product popularity for the business specializing in unique products.<br>
**- Skills:** Applied the RFM (recency, frequency, and monetary factors) model, identifying three to five crucial client groups, and then advanced to predict customer loyalty levels using Deep Learning methods.<br>
**- Technology:** Utilized KMeans Clustering to RFM results for Silhouette score and used scikit-learn and TensorFlow for deep learning.<br>
**- Results:** Successfully aligned business objectives with quantifiable metrics, resulting in more effective and targeted marketing strategies when implementing the RFM model, which evaluates customer behavior, and 100% achieved predicted loyal customer levels – high vs. low with a new dataset.

### 1.5 Twitter Sentiment Analysis
**- Link:** [`Twitter Sentiment Analysis`](https://github.com/DzungDo82/Twitter_BigData) <br>
**- Description:** Selected the topic 'Black Friday' and analyzed user sentiment (positive, negative, neutral) along with exploring the relationship between followers and tweets for the top 10 users.<br>
**- Skills:** Trained sentiment classification, read tweets from S3, generated predictions, and integrated them into the Quicksight dashboard for analysis.<br>
**- Technology:** EC2, S3, Athena, and Quicksight on AWS, and Spark on Databricks<br>
**- Results:** Managed the big data project and integraged multiple tools.

## 2. Visualization and Analysis projects - using Excel, Power BI, and Tabbleau
In this section, you can take a tour to explore some of my visualization projects.

### 2.1 Sales Data of Online Sport Store
**- Link:** [`Sales Data of Online Sport Store`](https://github.com/DzungDo82/Visual_sport_store) <br>
**- Description:** The online sport store required a solution for monitoring key performance indicators (sales, revenue, profit, returns), evaluating regional performance, analyzing trends and forecasts at the product level, and identifying high-value customers.<br>
**- Skills:** Created table relationships in a snowflake schema, established hierarchies based on geography, category, and date, and implemented DAX measures.<br>
**- Results:** The project highlighted the importance of tracking and analyzing sales data over time to identify trends and patterns, emphasizing the value of timely and comprehensive data visualization in understanding business performance, and facilitating informed decision-making.

### 2.1 Sales Data of Online Supermarket
**- Link:** [`Sales Data of Online Supermarket`](https://github.com/DzungDo82/Visual_online_market) <br>
**- Description:** The online market, a multinational business, managed a diverse portfolio of grocery stores across the United States, Canada, and Mexico, with a focus on expansion and operational diversity.<br>
**- Skills:** Managed the implementation of a visualization task that identified three key factors: the type of data (time-series, financial, categorical, hierarchical, etc.), the preferred mode of communication (comparison, composition, distribution, or relationship), and the intended audience (manager, executive, or client), in order to generate an appropriate and effective data report.<br>
**- Results:** Overall, surpassed transaction and profit targets by 5.69% and 5.6% respectively, underscoring the market's strong financial viability. Despite challenges in Canada, maintained consistent performance in the US and Mexico, highlighting adaptability and resilience in diverse market environments.

### 2.3 Employee Performance Metrics
**- Link:** [`Employee Performance Metrics`](https://github.com/DzungDo82/Visual_employee_metric) <br>
**- Description:** The company addressed declining performance indexes to identify root causes without adversely affecting employee morale, leveraging insights for strategic interventions.<br>
**- Skills:** Analyzed job satisfaction levels and their correlation with attrition rates, highlighting group disparities and enabling targeted interventions.<br>
**- Results:** The implementation of predictive analytics enabled the accurate forecasting of attrition rates based on crucial employee features.

### 2.4 Uber Density in New York
**- Link:** [`Uber Density in New York`](https://github.com/DzungDo82/Visual_Uber_NY) <br>
**- Description:** The dataset comprises monthly Uber pick-up records from April to July 2014, supplemented by additional data providing corresponding weather information for the same period.<br>
**- Results:** Identified high-density Uber pick-up locations during workday rush hours, optimizing service distribution and enhancing operational efficiency. Additionally, discovered a significant correlation between temperature fluctuations and Uber trip numbers, enabling strategic scheduling and resource allocation to meet fluctuating demand effectively.

## 3. SQL projects
In this section, the business concerns are addressed with SQL queries ranging from basic to advanced.

### 3.1 Airbnb listings Analysis
**- Link:** [`Airbnb listings Analysis`](https://github.com/DzungDo82/SQL_Airbnb) <br>
**- Description:** Determined the total number of unique listings in the calendar table, providing an overview of listing diversity.<br>
**- Results:** Proficiently utilized pivot tables and subqueries in SQL to identify the city with the highest number of listings and analyzed calendar table listings to discern price discrepancies between weekends and weekdays, providing valuable insights into pricing strategies.

### 3.2 Movie Rental Stores Analysis
**- Link:** [`Movie Rental Stores Analysis`](https://github.com/DzungDo82/SQL_Movie) <br>
**- Description:** The database was designed to represent a DVD rental store in early 2005.<br>
**- Results:** Analyzed sales data for rental volumes and monthly rental volumes, evaluated inventory levels by creating reports with film names and categories; assessed revenue from payments by month and each store, identifying unpopular movies for potential sale.

### 3.3 Retail Loyalty Program Analysis
**- Link:** [`Retail Loyalty Program Analysis`](https://github.com/DzungDo82/SQL_Loyalty) <br>
**- Description:** Utilized SQL to create and analyze a database, answering business questions on sales performance, store rankings, and customer loyalty.<br>
**- Results:** Analyzed transactions with negative sales/units, assessed transaction table span, and evaluated monthly and yearly sales growth, alongside store performance, loyalty program effectiveness, and top-performing stores and product categories based on provincial performance.

## Education
- **Applied Data Science and Big Data Diploma** – Toronto Institute of Data Science and Technology<br>
- **Bachelor of Architecture** – Van Lang University in Vietnam

## Contacts
- LinkedIn: www.linkedin.com/in/dzungdo29
- E-mail: kate.do.pham@gmail.com

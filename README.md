# Data Science Portfolio
This is a collection of projects I've completed over the years highlighting skills across the data science spectrum including data wrangling, hypothesis testing, database management, visualization, machine learning and deep learning. 


## [Harris SAVES Covid-19 Research Project](https://harrissaves.org/)
* Research project led by UTHealth School of Public Health in partnership with Baylor College of Medicine and Harris County Public Health.
* Through this research project, we provide free testing for everyone in Harris County and collect data to better understand the spread of Covid-19 in this geography.
* My responsibilities include data architecture, collection, cleaning, analytics, and visualization.
* [Public dashboard linked here](https://sph.uth.edu/projects/harris-saves/dashboard)

![harris dashboard](/images/Dashboard-main.png)


## [Using Machine Learning to Predict Customer Churn](https://github.com/bdbacik/Predicting-Customer-Churn)
* Built classification model to predict churn of credit card customers for a bank.
* Optimized Linear Regression, Random Forest, and XGBoost with grid search cross validation.
* Introduced novel modeling approach with random undersampling, tomek link elimination, and xgboost bagging to to achieve better positive class Recall on noisy, * label imbalanced data.
* Conducted ROI analyis by considering customer lifetime value (LTV), cost of false positives/negatives, and cost of intervention to retain customers.
* Presented recommendation for final model and summarized learnings for similar problems.

![correlation heatmap](/images/corr_heatmap.png)

## [Pubmed Crawler for Covid-19 Research Publications](https://github.com/bdbacik/Pubmed-Crawler)
* Pubmed crawler module that collects publication details from PubMed for a given keyword (i.e., COVID-19 Vaccine) and time period.
* Database module that creates a SQLite database, populates tables, and queries tables for data needed for visualization.
* Visualization module that produces a dashboard summarizing key statistics related to COVID-19 vaccine publications.
* Automation module to automatically run script and update visualization weekly using AWS and cron.

![pubmed dashboard](https://pubmedcrawler.s3.us-east-2.amazonaws.com/pubmed_dashboard2.png)

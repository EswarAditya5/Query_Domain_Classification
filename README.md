# Query_Domain_Classification

**Data Collection:** Analytics Vidya: https://datahack.analyticsvidhya.com/contest/query-domain-classification/

Build a system to categorize the query on the basis of the domain using Natural Language Processing.

## Problem Statement:

DSForum is a community-based portal where users can post queries related to data science topics such as machine learning, statistical analysis, data visualization, etc. The company optimizes the response time of the query by answering the query to the earliest. Nevertheless, the community can answer the queries through discussion forums. The queries might be related to different domains like Techniques, Tools, Careers, etc. 

Currently, the users manually tag the queries while posting the query into any of these categories: Techniques, Tools, Career, Hackathons, Resources, Misc, or Other. The query is then forwarded to the concerned team. This process is more error-prone and impacts the query response time. 

Can we design and develop a model that can accurately classify queries based on their domain? This will help the team to improve the response time of the platform by accurately identifying the domain of a query and redirecting it to the appropriate team and resolving the queries to the earliest. 

# Data Dictionary:

You are provided with 3 files - train.csv, test.csv, and sample_submission.csv

Train and Test Set

The train and test set contains the queries from different timespans. The train set includes the target variable ‘domain’ whereas in the test set, you need to predict the target variable ‘domain’. The target variable category contains multiple classes like  Techniques, Tools, Career, Hackathons, Resources, Misc, and Other.


|Variable|Description|
|:--:|:--:|
|ID| Unique identifier of the query|
| Title | Title of the query|
| Domain |Domain of the query (Target Variable)|


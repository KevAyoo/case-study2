# case-study
Customer &amp; Account Data Analysis
This repository contains Python scripts used to explore, clean, merge, and analyze customer, account, and lead datasets from an Excel file. The project performs exploratory data analysis (EDA), feature engineering, and segmentation preparation for downstream analytics or modeling.

Project Overview
The goal of this project is to:
Load multiple sheets from an Excel file
Inspect and profile the datasets
Explore lead sources and account statuses
Merge Leads and Accounts to estimate conversion rates
Engineer customer-level features
Prepare data for clustering, segmentation, and profiling
Analyze regional and cluster distributions
Data Loading & Inspection
The code loads all sheets from the provided Excel workbook:

3. Exploratory Data Analysis
Lead Sources
Identifies and plots the top 20 lead sources or channels
Account Status
Checks for common status columns and visualizes account distribution by status

4. Lead–Account Conversion
The project attempts to join Leads and Accounts on customer_id (or closest alternative) to compute:
Total leads
Leads successfully mapped to accounts
Conversion rate

6. Feature Engineering
Customer-level features engineered include:
Number of accounts
Total balance
Average balance
First account date
Days since first account
Missing values filled appropriately
These features are merged into a unified customer dataset (cust_features).

6. Clustering & Profiling
If clustering is applied externally, the project includes:
Cluster-level numeric summaries (count, mean, median)
Top lead sources per cluster
Regional cluster distribution (highlighting Kenya)

9. Results
The analysis produces:
Dataset summaries
Lead source & account status visualizations
Conversion rate metrics
Full engineered customer dataset
Cluster profiles
Regional cluster comparison

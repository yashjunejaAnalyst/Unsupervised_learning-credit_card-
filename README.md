# Unsupervised_learning-credit_card-
Python Project ( Unsupervised Learning - Credit Card Customer Segmentation )

**Project Title:**

Customer Segmentation for Credit Card Users Using Unsupervised Machine Learning

**Objective:**

To segment AllLife Bank’s credit card customers using unsupervised learning techniques, in order to:

1.) Understand customer behavior patterns.

2.) Personalize marketing and service delivery.

3.) Improve digital engagement and reduce operational costs.

**Approach:**

**1. Data Understanding and Preprocessing**
   
•	Dataset included-

o	Average Credit Limit

o	Total Credit Cards

o	Total Bank Visits

o	Total Online Visits

o	Total Calls Made

•	Preprocessing Steps-

o	No missing or duplicate values.

o	Outlier detection conducted; kept due to value retention.

o	Data was scaled using standard scaling for clustering.

**2. Exploratory Data Analysis (EDA)**
   
•	Customers mostly have low to moderate credit limits.

•	Majority prefer few in-branch visits and show low digital engagement.

•	Strong correlations found:

o	Positive: Credit limit ↔️ Online visits

o	Negative: Calls made ↔️ Credit limit / online usage

**3. K-Means Clustering**
   
•	Used Elbow Method and Silhouette Score (0.723) to select optimal clusters.

•	Identified 6 customer segments with unique behavioral traits.

**4. Hierarchical Clustering**
   
•	Performed using dendrograms and cophenetic correlation.

•	Also formed 6 clusters, slightly varying in characteristics from K-Means.

**Outcome:**

Model Comparison-

•	Silhouette Score for both K-Means and Hierarchical = 0.723

•	K-Means is more scalable for larger datasets.

•	Hierarchical Clustering provides better interpretability and relational insights.



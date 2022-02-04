<center><h2><b>Data Science applied to online shopping behaviour</b></h2></center>

This notebook carries out an in-depth analysis of online shopping behavior with a view to identifying leading features that can be leveraged by ML models to predict a customer's propensity to buy

# **Tasks & Methodology Summary**
-----


1. **Task 1** - Explore a variety of classification models to build a highly predictive classifier that predicts whether or not a customer will purchase. Models were trained on data entries corresponding to the months of June-Dec, and tested on data entries corresponding to Feb-March.

    1. Find and explain important features. 
    1. Report and interpret the most meaningful classifications metrics (F1 score was used as they key metric to optimize against)
    1. Show and explain the hyper-parameter fitting process.


2.  **Task 2:** Generate user-behavior clusters based on the purchasing behavior data for the complete dataset.

    1. How many clusters are there? What are the significant differences between the various clusters in terms of the size of the clusters and purchase ratio.
    2. Return plots and cluster images generated for the data.
    3. Perform a detailed analysis for each cluster corresponding to the variations in features and identify some behaviors corresponding to each particular cluster (e.g,. which cluster represent new shoppers vs. brand conscious shoppers etc.).

3. **Task 3:** Consider training data (with the 'Revenue' attribute) for records from June-Sept only. For all records from Oct-Dec, assume that the 'Revenue' attribute is missing. Build a semi-supervised self-labeling model to estimate 'Revenue' for the missing records in Oct-Dec and then fit a classifier. Report classification performance on Feb-March data set with and without the self-labeled data. 

    1. Consider the records from Oct-Dec only, and generate the classification performance on test data
    2. Compare the above results to using the self-labeled data and training data together to see whther the classification performance on test data improves... 

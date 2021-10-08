# JP-Morgan-Loan-foreclosure

Problem statement-
Predicting foreclosure cases for each of the data points in test dataset and to suggest the effective measure the firm
can take to overcome a foreclosure case and enhance its customer retention rate that will yield to more profitability.

Dataset information- There were 4 seperate files provided
• Customer demographics
• Customer transactions (i.e. repayments made by the client)
• List of foreclosed customers
• Test dataset

Data Merging-
• The customer transactions datasetis merged with list of foreclosed customer dataseton AGREEMENTID and
similarly with test dataset.
• Bothdatasets are then merged with Customer demographics dataset on CUSTOMERID.
• The resulted train dataset and test dataset consists of 19730 and 13163 instances respectively with 50 attributes.
• The two datasets were concat and resulted to 32893 and 50 attributes.
 

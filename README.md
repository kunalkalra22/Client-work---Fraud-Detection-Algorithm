# Client-work---Fraud-Detection-Algorithm

This alrgoritm detects the customers exhibiting unnatural behaviour, and classifies them as fraud based on applying statistical techniques on their transactional KPIs. Rolling
windows of 1-, 7-, 15-, and 30-days are selected to classify fraud at a customer and store-level for a national cineplex chain in India. The data for the rolling windows is 
right-skewed on the KPIs of interest, which is first transformed before applying statistical analysis, and once the thresholds for fraud are determined on the transformed data,
the actual thresholds are arrived at using a reverse transformation.

The code has been writen in Qlikview.

Build a recommendation engine

Online Challenge: Build A Recommendation Engine (Powered by IBM Cloud)
There is a growing expectation from customers in the digital world to have a more personalized experience and business owners wanting to become more data driven so they can stay one step ahead of the competition and focus on what matters most: building their business.
 
IBM invites the Developers and Data Scientists to compete for this challenge of developing an optimized, high performing recommendation system for a retail organization who would like to provide a personalized shopping experience to stay ahead of the competition.
 
Business stakeholders don't care much on how fancy the algorithm is. They care more about how it can move the needle on their key business challenges.
 
Here is the opportunity to prove that Data Science is all about solving the real business problem not just models or algorithm alone. Are you ready to take up this challenge? Click on the register button to join this contest.



Problem Statement


Organization “Silara Retail”  is inviting the Developers and Data Scientists to build a high performing recommendation engine for their online retail portal.
They are making their last one year customer transaction (anonymized) data available. For the customers in test data, the participants need to recommend the next items that they are most likely to buy.
You are expected to build a high performing recommendation engine using any framework of your choice. You are encouraged to use IBM Watson Studio Apache spark based Jupyter notebook.
The model created should be readily consumable by the organization and hence you are expected to expose the model as API endpoint using any toolkit of their choice. It will be good to consider using Watson Machine Learning (WML) available through IBM Cloud.
 

Data Dictionary
train.csv: Contains transactional data for for a particular set of customers 
Variable	Description
CustomerID	Unique ID for customer
InvoiceNo	Invoice number of transaction
Quantity	Quantity of item bought
InvoiceDate	Invoice Date
UnitPrice	Unit Price for item
Country	Country Code
StockCode	Item ID
 
 
test.csv: Contains first 50% transactions for a different set of customers for whom recommendations are to be made. 
Variable	Description
CustomerID	Unique ID for customer
InvoiceNo	Invoice number of transaction
Quantity	Quantity of item bought
InvoiceDate	Invoice Date
UnitPrice	Unit Price for item
Country	Country Code
StockCode	Item ID
 
sample_submission.csv: Contains the exact format for submission. Submission file should be of format: [628 rows x 2 columns]
Variable	Description
CustomerID	Unique ID for customer
Items	List of recommended items
 
Public and Private Split
The customer IDs in test data is further randomly divided into Public (50%) and Private (50%) data.
Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.

IBM Cloud Registration
If you would like to explore the IBM Cloud service, please sign up for IBM cloud using the link below:
 
Link https://ibm.biz/BdYkpq
 
Build a Recommendation Model using Watson Studio and Watson ML (Reference Model) :
 
Code reference: https://github.com/IBMDevConnect/Recommendation_service



Link to Solution Submission

Participants are required to register on the below link to explore the link to solution submission

https://datahack.analyticsvidhya.com/contest/build-a-recommendation-engine-powered-by-ibm-cloud/



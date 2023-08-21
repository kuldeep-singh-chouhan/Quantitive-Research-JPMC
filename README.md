# JPMorgan Chase & Co. | Forage Virtual Experience Program
This program is about completing tasks that replicate the work of Quantitive Research team does every day. Key skills involves, data analysis, programming, and financial mathematics.
### 1. Investigate and analyze price data
 Analyze the Natural Gas Price data to estimate the purchase price of gas at any date in the past and extrapolate it for one year into the future
### 2. Price a commodity storage contract
Create a prototype pricing model that will be the basis for fully automated quoting to clients.
Write a function that is able to use the data created previously to price the contract. The client may want to choose multiple dates to inject and withdraw a set amount of gas, so your approach should generalize the explanation from before. Consider all the cash flows involved in the product.

The input parameters that should be taken into account for pricing are:

1. Injection dates. 
1. Withdrawal dates.
1. The prices at which the commodity can be purchased/sold on those dates.
1. The rate at which the gas can be injected/withdrawn.
1. The maximum volume that can be stored.
1. Storage costs.

Write a function that takes these inputs and gives back the value of the contract.
### 3. Credit risk analysis
The data on the loan borrowers provide details of the borrower, including their income, total loans outstanding, and a few other metrics. There is also a column indicating if the borrower has previously defaulted on a loan. Use this data to build a model that, given details for any loan described above, will predict that the borrower will default or not.
### 4. Bucket FICO scores
Make the model work for future data sets, so create a general approach to generating the buckets. Given a set number of buckets corresponding to the number of input labels for the model, find out the boundaries that best summarize the data. Create a rating map that maps the FICO score of the borrowers to a rating where a lower rating signifies a better credit score.

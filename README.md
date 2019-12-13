# What are the factors that significantly impact the monthly premiums?

## Predictive Analysis of Monthly Payments of Auto Insurance

![picture](https://i2.wp.com/www.einsurance.com/wp-content/uploads/how-to-speed-up-your-car-insurance-claims.jpg?resize=1500%2C1001&ssl=1)

Auto insurance is a contract between a driver and the insurance company that protects the driver against the financial loss of an accident, theft or any unforeseen incident. In the US, all drivers must have a liability  insurance that meets the legal requirements, which vary with the states’ laws.

Policyholders pay monthly premiums. Various factors affect the insurance premiums of a customer. The list of factors is not limited to but includes the state, vehicle type, accident history, deductibles, age, gender, demographic information, credit score, and many different factors; for example, a lower the deductible amount results in a higher the premium amount. Insurance companies do risk assessments to determine the insurance premium of a client. For example, a higher risk entails higher premiums. From the client's perspective, they look for the best coverage and meet the liability requirements with a minimum budget. This capstone project investigates the significance of factors that affect the insurance premiums of the clients; it provides a systemic analytical investigation of the data that can provide decision support for insurance companies to find the optimized affordable premiums.

The data was obtained from the Emcien data repository data in a CSV file format.This data set used to analyze the parent reviews for each childcare centers. For more information about the data and the cleaning process, please see the links below:

  1. [Proposal](https://github.com/daphneworld/capstone2/blob/master/Daphne's%20Capstone%20Project-2%20Proposal.pdf)
  
  2. [Data Wrangling Process](https://github.com/daphneworld/capstone2/blob/master/Data%20Wrangling%20Process%20of%20Capstone%20Project%202.pdf)
  
  3. [Data Wrangling Code](https://github.com/daphneworld/capstone2/blob/master/Data%20Wrangling%20of%20Capstone%20Project%202.ipynb)
  
During exploratory data analysis, we ask the following questions:
- What are the factors that significantly impact the monthly premiums?
- How claim reasons correlate with other factors? 

The exploratory data analysis process contain the analysis of different features and their relations.  For more information about the exploratory data analysis process, please see the links below:

  1. [Data Story](https://github.com/daphneworld/capstone2/blob/master/AUTO%20INSURANCE%20MONTHLY%20PREMIUM%20PREDICTON%20DATA%20REPORT.pdf)
 
  2. [Exploratory Data Analysis Code](https://github.com/daphneworld/capstone1/blob/master/Exploratory%20Data%20Analysis%20New%20York%20City%20Childcare%20Centers.ipynb)
 
## Machine Learning
  
  Statsmodels is used for feature selection. Target value is Monthly Auto Premiums. Numerical features are claim amount,total claim amount and income. Categorical features are State, Response, Coverage, Education, EmploymentStatus, Gender, LocationCode, MaritalStatus, PolicyType, Policy, ClaimReason,SalesChannel, VehicleClass, VehicleSize. 

 Model Name | Mean Absolute Error
  ----------------------------|---------------------
  Multiple Linear Regression|4.98
  Quadratic Linear Regression|4.97
  Ridge  Regression|4.98
  Lasso Regression|4.95
  Elastic Net Regression|4.95

Among the regression models, Lasso regresion and Elastic Net Regression achieved the best results. The model evaluated with different metrics such as mean absolute error,mean squared error and root mean squared error. For more information about the exploratory data analysis process, please see the link below:

   - [Machine Learning Analysis](https://github.com/daphneworld/capstone2/blob/master/Regression%20Analysis%20for%20Prediction%20Monthly%20Premiums%20of%20Auto%20Insurance%20Data.ipynb)
   - [Presentation slides](https://github.com/daphneworld/capstone2/blob/master/Prediction%20of%20Monthly%20Premiums%20of%20Auto%20Insurance.pptx.zip)
   

## Key Findings
  - The claim amount, which is the amount that was claimed by a policyholder, is higher than the total claim amount, which  is the amount that was approved by the insurance company. According to data, %80 of the claim amount is less than 1000 and %80 percent of the total claim amount is less than 600. 
  
  - 314  customers do not have any claims.
  
  - 6817 customers have an income and 2317 customers do not have an income.

  - Total claim amount is higher between $20,000.00-$40,000.00 annual income, and total claim amount is between $200.00-$600.00. The higher total claim amounts mostly overlap with the lower-income range. 

  - 1308  students have honor status. They must be high school students and 198  of these students  have no income.
  
  - %70 of the students pay less than 100 $ monthly premium.

  - The majority of customers buy low monthly premium policies, which have high deductibles.

  - There is a correlation between the total claim amount and monthly premiums.
  
  - The total claim amount is %10 of the total premium in every state..

  - There is no significant relationship between the monthly premiums of a policyholder and the number and the type of policies. 

  - The type of coverage affects the monthly premiums. Basic coverages have lower premiums, whereas the premium coverages have higher premiums.

  - The education level of a policyholder does not significantly impact the monthly premiums, the P.hD. holders have slightly lower monthly premiums than the high school and lower grades holders.

  - Gender, employment status, marital status,vehicle size,sales channel  do not have a significant impact on monthly premiums.

  - Urban and rural communities policyholders have lower monthly premiums than suburban ones.

  - The lowest monthly premium belongs to two-door and four-door car types. Luxury cars have the highest monthly premiums.

  - Collision is the primary claim reason in each state. The next most frequent claim reason is hail. This is normal because Nebraska, Missouri, and Kansas are in the top 5 states in the U.S. for hail loss (2019).

  - Employed policyholders constitute the highest number of policyholders who have the claim reason for hail. The reason can be that these policyholders drive their cars more frequently than the others.


 
 

 






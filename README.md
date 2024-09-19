# Insurance policies cross-selling
 
In this project, logistic regression is used to build a predictive model that can predict whether past-year policyholders might also be interested in purchasing insurance for their vehicle.

The dataset consists of the following properties:

- **id**: unique id of the buyer.
- **Gender**: gender of the buyer.
- **Age**: age of the buyer.
- **Driving_License**: 1 if the user has a driver's license, 0 otherwise.
- **Region_Code**: buyer's unique region code.
- **Previously_Insured**: 1 if the user already has a vehicle insured, 0 otherwise.
- **Vehicle_Age**: age of the vehicle.
- **Vehicle_Damage**: 1 if the user has damaged the vehicle in the past, 0 otherwise.
- **Annual_Premium**: the amount the user has to pay as premium during the year.
- **Policy_Sales_Channel**: anonymized code of the channel used for the proposal (e.g., by email, by phone, in person, etc...)
- **Vintage**: number of days since the user has been a customer of the company.
- **Response**: 1 if the buyer responded positively to the sales proposal, 0 otherwise.

  

The goal of the model is to predict the value of **Response**.
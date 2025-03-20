# AI-ML-UsedCarPricing

# An Examination of Factors in Used Car Pricing
### What drives the price of a car?

![](images/ckurt.jpeg)

**OVERVIEW**

In this application, the client is a used car dealership looking to maximize sales. Using a dataset on used cars and machine learning, factors that make a car more or less expensive are identified.  As a result of this analysis, clear recommendations to the client, a used car dealership, is provided as to what consumers value in a used car.

The dealership needs a clear set of recommendations on the key features that drive used car pricing, enabling them to fine-tune their purchasing decisions and maintain inventory aligned with consumer preference. Using a dataset on used cars, statistical and machine learning models are used to determine which features contribute most to a car’s resale value.
## Executive Summary
Machine learning techniques were used to determine which features contribute most to a car’s resale value. 
The dealership group's market positioning and business constraints were considered in the evaluation: 
* The dealer is not interested in keeping cars of extremely high value  (over $100,000) on the lot 
* The dealer prefers  to sell cars under 1,000,000 miles to avoid time consuming questions during the sales cycle
* The dealer is not equipped to sell non-mass market cars such as those that are very old (25 years) or very rare

Various computer models were evaluated based on their ability to accurately  predict the price of the car. Data up to the year 2020 was used to evaluate the models. The selected model provided the following insight into what drives the price of a car. 

**Top Factors That Drove High Prices**
* Fuel: Diesel
* Type: Truck
* Cylinders: 8 Cylinders
* Drive: 4wd
* Manufacturer: Toyota
* Type: Pickup
* Transmission: Manual
* Title: Status: Clean
* Manufacturer: Ram
* Recent Model Year
* Manufacturer: GMC
* State: CA
* Manufacturer: Honda
* Type: Convertible
* State: NC
* Type: Coupe
* Cylinders: 6 Cylinders
* Manufacturer: Lexus
* Condition: Like New
* Cylinders: 10 Cylinders

**Top Factors that Drive Low Prices**
* Fuel: Gas
* Cylinders: 4 Cylinders
* Type: Sedan
* Drive: Fwd
* Type: SUV
* Manufacturer: Nissan
* Transmission: Automatic
* Type: Hatchback
* Manufacturer: Dodge
* Manufacturer: Subaru
* Title: Status: Rebuilt


The complete list of sorted factors in priority order is available for download here: 
<a href="factors_that_drive_price_sorted.csv">factors_that_drive_price_sorted.csv</a>

**Action Items and Next Steps**
1. The dealer should review the sorted factors list and purchase cars with these attributes. 
2. As the recommendations are only as good as the data used, dealer group to continuously  provide updated sales data for re-evaluation. 
## Methodology: CRISP-DM Framework
For this application, an industry standard model called CRISP-DM is used.  This process provides a framework for working through a data problem.  


<center>
    <img src = images/crisp.png width = 50%/>
</center>

<center>
    <img src = images/CRISP-DM-Methodology.png width = 80%/>
</center>


## Outline of Project

* Jupyter Notebook:  <a href="UsedCarPricing.ipynb">UsedCarPricing.ipynb</a>
* Download Data:  <a href="data/vehicles.csv">vehicles.csv</a>
* Final Report:  <a href="11.1 What Drives the Price of a Car.docx">11.1 What Drives the Price of a Car.docx</a>


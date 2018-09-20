# Data Analytics manager for a medium sized health care software provider.
Create a system using Apache Hadoop with the following requirements:
* Incorporate data from 45 million rows in a MySQL corporate database containing patient records, histories, visits, and prescriptions.
* Incorporate unstructured data captured from patient monitoring equipment present at hundreds of patient care facilities

## What is the health trend of patients being treated at customer locations, given the measurement of vitals measured with our monitoring equipment for these 3 indicators (blood sugar, pulse, temperature) ?



* Assess the requirements of the business in order to determine which systems would be best to implement to achieve our goal of assessing health trends
* Create a data warehouse that holds all the data stored from different silos and then develop a data mart which would pull out and store only the necessary information from the data warehouse, that we would use to assess the patients (in this case vitals).
* Create an index to generate and differentiate all the patients with a patient ID number and then select the tables needed for analysis from the database. 
* Write a query in SQL to find the patients who have been treated at the different locations, and whose vitals were measured based on the three indicators. Write a query that joins the different tables or create a temporary table to find the measurements of vitals. T
* The data is processed in batches on MapReduce to query the data since we have a large data set of 45 million records. Hadoop will then simplify the unstructured data and read with hive. 
* After finding the necessary data, which are the different patients and the data based on their vitals, I will export it into a visualization tool and allow the data to show a trend of vital levels in every patient or which vital is measured the most in patients. Knowing this information will allow me to recommend the best data driven decisions moving forward. 
* I could also use R to predict patients vital levels overtime by analyzing current and historical data of vitals. 

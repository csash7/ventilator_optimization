# ventilator_optimization
Final project of the class EE 608 A

Ventilator Optimization to maximize Life years.
It gets the latest COVID data from "https://covid19api.io/api/v1/ReportsByCountries/US" API.
Some of the data such as number of patients based on age group, mortality rate and ventilators data can be found in 
https://www.worldometers.info/coronavirus/coronavirus-age-sex-demographics/

Input is the number of ventilators available.
The ventilator optimization is based on the age group and to maximize the life years of the patients.

For the optimization, we used penalty method with initial parameters,
c = 2
beta_factor = 2

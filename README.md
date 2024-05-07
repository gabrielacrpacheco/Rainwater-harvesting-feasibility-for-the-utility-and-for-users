# Rainwater-harvesting-feasibility-for-the-utility-and-for-users
This code evaluates the implementation of rainwater harvesting systems in the urban context, considering different categories of users, for both users and the utility.
This code was developed during my PhD and the program considers the following steps:

Input data:
  - file with rainfall (csv format);
  - file with demand, number and characteristics of households, tank volume for each type of household, tank prices, tariff structure, cost per volume for the utility, sizing and economic parameters (csv format).
Continuous simulation of the daily mass balance for the different categories of households;
Calculation of consumption (per month, per type of household and per year of the life span);
  - Calculation of consumption of rainwater for each different household in the city and for all of them;
  - Calculation of consumption if rainwater harvesting were not implemented for each different household in the city and for all of them;
Economic Evaluation (with and without rainwater harvesting)
  - Determination of the amount paid per type of household and for all of them (utility revenue);
  - Determination of the utility expenses for producing the consumed water volume per type of household and for all of them (utility expense);

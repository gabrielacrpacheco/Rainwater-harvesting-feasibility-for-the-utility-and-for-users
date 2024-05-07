# Rainwater-harvesting-feasibility-for-the-utility-and-for-users
This code was developed during my PhD at UnB.
The program evaluates the implementation of rainwater harvesting systems in the urban context, considering different categories of users who have varying catchment areas, consumption levels, and rainwater reservoir volumes. Using a rainfall dataset, water and sewage tariffs and the cost of these services for the utility, technical and economic performance indicators are calculated for both users and the utility.

INPUT DATA:
  - file with rainfall (csv format);
  - file with demand, number and characteristics of households, tank volume for each type of household, tank prices, tariff structure, cost per volume for the utility, sizing and economic parameters (csv format).
STAGES:
1) Continuous simulation of the daily mass balance for the different categories of households;
2) Calculation of consumption (per month, per type of household and per year of the life span);
  - Calculation of consumption of rainwater for each different household in the city and for all of them;
  - Calculation of consumption if rainwater harvesting were not implemented for each different household in the city and for all of them;
  - Determination of consumption indicators;
3) Economic Evaluation (with and without rainwater harvesting);
  - Determination of the amount paid per type of household and for all of them (utility revenue);
  - Determination of the utility expenses for producing the consumed water volume per type of household and for all of them (utility expense);
  - Determination of economic indicators;

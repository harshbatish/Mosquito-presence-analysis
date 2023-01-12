# Mosquito-presence-analysis

---

This project aims to detect the presence of mosquites and West Nile Virus which should depend on various factors present in the dataset.

Number of samples taken into consideration while making this project is around __200 thousand__, which is whole as raw data. There are 13 features/ columns in the dataset.


---

### Data dictionary:

1. __Year__
2. __Week__
3. __Address_Block__: This is th full address where mosquitoes were found (includes the block)
4. __Block__: This column shows the block number of the address.
5. __Trap__: This represents what type of trap is it.
6. __Trap_type__: Name of the trap
7. __Date:__
8. __Mosquito Number:__ Number of mosquitoes
9. __Mosquito ID:__ Code name based on species
10. __WNV Present:__ _TARGET COLUMN positive or negative
11. __Species:__ Type of species
12. __Lat:__ Geographical coordinates of the mosquito presence
13. __Lon:__ Geographical coordinates of the mosquito presence
14. __Month:__

---

### Data Files:

1. __mosquito_data.csv__: Main data file (raw)
2. __mosquito_data_part_2.csv__: Proccessed/ clean data 

---

For this project, I made 4 different jupyter notebooks which are described as follows:

### Structure of Project:

1. __EDAfile.ipynb__ : This file shows all the cleaning of the data and pre-processing. Data wrangling, basic EDA and advanced EDA is done.

2. __statsanalysis.ipynb__ : statistical significance/ linear and logistic regression.

---

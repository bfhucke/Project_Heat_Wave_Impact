# Project_Heat_Wave_Impact
all Notebooks used for the thesis project on modelling heat wave effects

This file comprises all used Jupyter Notebooks during the work. Because of the large amounts of data that had to be loaded for the different tasks, multiple Notebooks had to created. They are split up by topic. A short description of the contents is shown below:


0_Locations_rv_geocode: the basis, reverse geocoding of all available coordinates in the raw weather data

1_MRT_Calculation: Calculation of the Mean Radiant Temperature (MRT), stored in a folder because it comprises multiple Notebooks. The reason is that the MRT had to be calculated separately for different years due to the large amounts of data that needed to be retrieved to compute it.

2_Merge_Weather_MRT: The merging of MRT with other weather variables. Similarly, to the MRT calculation, this folder contains multiple notebooks due to large data amounts that needed to be filtered and merged with MRT

3_Threshold_Computation: Computation of apparent temperature threshold that is crucial to determine heat waves

4_1_Mortality_Demographic: Loading of raw mortality and demographic statistics and transformation in order to merge with weather data

4_2_Health_Expend_Disease: Loading of raw health expenditure and disease prevalence statistics and transformation in order to merge with weather data

5_Final_Merge: Merging of all obtained data from the previous notebooks, datasets to be used in the descriptive and modelling parts are set up in this notebook

6_Descriptive: Notebook to create the descriptive statistics and plots used in the thesis chapter on Descriptive Results

7_Modelling: Notebook where all models described in the Thesis are fitted, comprises the modelling process and all results

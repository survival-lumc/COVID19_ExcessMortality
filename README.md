# COVID19_ExcessMortality
This is an accompanying github repository for the paper "Dynamics of infection, vaccination and excess mortality during the COVID-19 pandemic among older individuals - a nationwide analysis", by Eva Koster, Marije Sluiskes, Hein Putter, Frits Rosendaal, Astrid van Hylckama Vlieg, Mark de Boer and Liesbeth de Wreede. It contains all code that was used for the analyses of this paper to facilitate researchers who want to apply our models to similar data.

The data for the current paper are non-public microdata from Statistics Netherlands. Under certain conditions, these microdata are accessible for statistical and scientific research. For further information: microdata@cbs.nl.

The code is split into 6 files. Files 1-5 were used within the remote CBS environment.

1. create datasets per year: This syntax creates the basic datasets for each year in 2015-2021, which contain demographic and survival data.
2. dataset 2020-2021: This syntax creates the dataset for the study period 2020-2021, and adds vaccination and infection data.
3. ratetables: This syntax generates all rate tables that were used for the background hazards in the relative survival analyses.
4. analyses - calculations: In this syntax, all calculations on the study period (2020-2021) are performed.
5. export results from CBS: This syntax makes a file to export the results from the CBS environment.
6. outside CBS - show results: This file contains all the code to show the results.

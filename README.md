# HES TimeSeries Module

Cette repository possede le materiel pour le module pour les serie temporelles.

Les données sont mis à disposition depuis https://transparency.entsoe.eu/ 
- Pour la consommation: Total Load - Day Ahead / Actual Actual Total Load [6.1.A] Day-ahead Total Load Forecast [6.1.B] 
- Pour la generation: Actual Generation per Production Type Aggregated Generation per Type [16.1.B&C]


Structure:
- data
    - curated_data
    - load
    - generation 

- data_exploration
    - 00_Production_cleaning.ipynb --> notebook pour la generation
    - 01_Timeseries_exploration.ipynb --> notebook pour l'exploration des timeseries 

- forecastdemo
   - Script utilisant scikit learn pour effectuer une prevision 

- Presentation 
    - Presentation du module 06/12/2024 



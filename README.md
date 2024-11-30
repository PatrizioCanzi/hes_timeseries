# Module HES - Séries Temporelles
Ce dépôt contient le matériel pour le module sur les séries temporelles.

Les données sont mises à disposition via ENTSO-E Transparency Platform :

- Consommation : Total Load - Day Ahead / Actual , Actual Total Load [6.1.A] , Day-ahead Total Load Forecast [6.1.B]

- Production : Actual Generation per Production Type , Aggregated Generation per Type [16.1.B&C]


Structure:
- data : curated_data , load , generation 

- data_exploration : 00_Production_cleaning.ipynb --> notebook pour la generation ,  01_Timeseries_exploration.ipynb --> notebook pour l'exploration des timeseries 

- forecastdemo : Script utilisant scikit learn pour effectuer une prevision 

- presentation : Presentation utilisée



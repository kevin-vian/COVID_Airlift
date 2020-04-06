# COVID_Airlift

This repository was inspired by Paul Yarin's Medium post on exploring the feasibility of airlifting COVID-19 patients to relieve overcrowded hospitals in the United States.
https://medium.com/@yarin/urgent-need-for-data-science-modeling-of-airborne-national-medical-evacuation-network-to-address-c2acd2dd1aaa

## To install and run the simulation locally:
```
source COVID_Airlift/medevac/bin/activate
pip install -r requirements.txt
jupyter notebook
```
## Notes:
- Open COVID-19_Medevac_Exploration_V6.ipynb in the browser launched by Jupyter 
- The cells of the notebook should be run linearly (top to bottom)
- Please refer to comments in the notebook for explanations of inputs, outputs, and modeling assumptions

## To Do List
- [ ] Modify trainer to make mortality rate a learned variable (currently given)
- [ ] Incorporate historical hopsital addmitance data to refine "hospitalized" predictions

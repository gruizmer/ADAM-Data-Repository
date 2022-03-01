# ADAM-Data-Repository
This repo contains all the data needed to run the case studies for the ADAM paper.

## Biogas production
The directory `biogas` contains all data for the biogas production case studies. Specifically, `biogas/biogas_x` contains the data files for the scenario where `x` is the corresponding REC value. 

## Plastic waste recycling
The directory `plastic_waste` contains all data for the plastic waste recycling case studies. Different scenarios share the same supply, technology site, and technology candidate data, as specified by the `csv` files under `plastic_waste`. Each scenario has a different demand data file, which is contained in `plastic_waste/Elec_price` and `plastic_waste/PET_price`.

## How to run the case studies
In order to run the case studies, one can create a new model in ADAM and upload appropriate CSV file at each step (e.g. upload `biogas/biogas_0/supplydata197.csv` in step 2 where supply data are specified). 

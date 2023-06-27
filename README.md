# Code Sample
This is sample code for an application for a teaching position. This is an extract of the code from the first year term paper. The code includes an example of uploading and saving different objects in R, it also includes different types of plots, regression analysis and its outputs. There are three data files in the folder: 
- 'vdem.xlsx' dataset for the first descriptive plot;  
- 'table_maps.xlsx' dataset for the second descriptive plot;  
- 'data_analysis.xlsx' dataset for the analysis.  

## Variables used in the analysis
### Dependent variables:  
Regional government elected (v2elsrgel) -- V-Dem data
  - 0: Generally, offices at the regional level are not elected
  - 1: Generally, the regional assembly is elected but not the executive
  - 2: Generally, the regional executive and assembly are elected
    
Local government elected (v2ellocelc) -- V-Dem data
  - 0: Generally, offices at the local level are not elected
  - 1: Generally, the local assembly is elected but not the executive
  - 2: Generally, the local executive and assembly are elected

### Independent variables: 

State capacity (Capacity) -- Hanson's data (-3 to +3)

Coups d’etat attempts (coup) -- Colpus data
  - 0: No coup attempt occurred  
  - 1: Unsuccessful coup attempt occurred  
  - 2: Successful coup attempt occurred

Mass uprisings (campaign) -- NAVCO data
  - 0: 'no' 
  - 1: 'yes'

### Control variables: 

GDP per capita (e_gdppc)  
Infant mortality rate (e_peinfmor)  
Population (e_pop)  
Petroleum, coal, and natural gas production per capita (e_total_fuel_income_pc)  
Leader change (leader_change)  
Ethnic fractionalization (EFindex)  
Lagged DVs (previous level of decentralization):
  - v2elsrgel_change
  - v2ellocelc_change

The code is written in R Markdown and is contained in two files: .Rmd and HTML.

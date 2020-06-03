# Datasets

- human/SARS-CoV-2/latent-period
- human/demographics/scotland

- pathogen/SARS-CoV-2/surface-survival


Regarding `human/demographics/scotland/demographics.h5`, the format is as follows:

- The h5 file contains the following groups: "dz", "grid10km", "grid1km", "hb", "iz", "la", "mmw", "spc", and "ur".   

- Each group contains the following subgroups: "10year", "1year", "5year", and "total".

- Each subgroup contains the following data objects: "areaNames" (area names), "colNames" (age groups),  "dataset" (the data), and "rowNames" (area IDs).

  - Groups "grid10km" and "grid1km" are the exception to this, where areaNames is replaced by gridXY (a matrix of x,y coordinates). As before, these coordinates denote the row and column of each grid location, starting in the lower left-hand corner. 

- For simplicity, there are no longer any attached attributes.




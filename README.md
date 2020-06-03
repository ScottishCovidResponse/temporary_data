# Datasets

- human/SARS-CoV-2/latent-period
- human/demographics/scotland

- pathogen/SARS-CoV-2/surface-survival


**Regarding `human/demographics/scotland/demographics.h5`, the format is as follows:**

- The h5 file contains the following groups: `dz` (data zone), `grid10km` (10km grid), `grid1km` (1km grid), `hb` (Health board code), `iz` (2011 intermediate zone code), `la` (Local authority code), `mmw` (Multi-member ward code), `spc` (Scottish parliamentary constituency code), and `ur` (2016 Scottish Government 6-fold urban rural classification).   

- Each group contains the following subgroups: `10year`, `1year`, `5year`, and `total`.

- Each subgroup contains the following data objects: `array` (the data), `Dimension_1_title` (the title of the first dimension),  `Dimension_1_names` (the names of the first dimension), `Dimension_2_title` (the title of the second dimension), and `Dimension_2_names` (the names of the second dimension).

  - Groups `grid10km` and `grid1km` are the exception to this, which includes `Dimension_1_values` (a 2xN matrix of x,y coordinates) and `Dimension_1_units` (the units of the array). As before, these coordinates denote the row and column of each grid location, starting in the lower left-hand corner. 

- For simplicity, there are no longer any attached attributes.


**Please note the following:**

- 

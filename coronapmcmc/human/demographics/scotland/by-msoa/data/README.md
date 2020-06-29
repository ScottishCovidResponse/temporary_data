# Area data

Information about the areas over which disease spread is modelled

Originally from

https://github.com/ScottishCovidResponse/CoronaPMCMC/blob/f22e46332328aa42e2ed13081cc151aac672938b/Data_ScotlandMSOA/areadata.txt

The columns are:

- “area” gives the area code 
- “x, y” geographical position (e.g. long, lat or any other units),
- “region” gives the region code to which the area belongs (corresponding to “regiondata.txt”). 
  columns for covariates. This example gives population density, but anything else which could affect disease transmission could be also included, e.g. deprivation index or weather data 
- columns for populations in different age groups. This should be available from census data. This example shows just three age groups, but if we can get the age classifications as small as possible then the code can combine them in whichever way is appropriate.
- columns for other demographic categories (giving percentages). This shows sex, but others could be used if they are available (e.g. ethnicity).

The example above shows MSOA areas in Scotland, but we also need MSOA areas for the entire UK and the same for the finer scale output areas (OAs).


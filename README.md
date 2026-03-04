# Matrix-Variate-Cluster-Weighted-Bilinear-Factor-Analyzers

The file MatFacReg_1.0.0.0.tar.gz contains the R package for running Matrix-Variate-Cluster-Weighted-Bilinear-Factor-Analyzers. A help description for each argument supports each function.

The file GHG_data.RData contains data for N=174 countries observed over the six years 2015–2020.
The response array, Y, includes measurements of carbon dioxide (CO₂), methane (CH₄), and nitrous oxide (N₂O) emissions for each country in each year.
Hence, Y is a 3 x 6 x 174 array, where the dimensions correspond to variables, years, and countries, respectively.

The covariate array, X, comprises five country-level indicators: GDP per capita (in USD), fertilizer consumption (kilograms per hectare of arable land), value added in agriculture, forestry, and fishing (in USD), energy intensity of primary energy (measured in MJ per PPP GDP), and population.
These variables are also recorded for each country and year, so that X is a 5 x 6 x 174 array, again organized as variables by years by countries.

The objects YL and XL contain the logarithmic transformations of Y and X, respectively. 
The empirical analyses presented in the paper are conducted using these log-transformed arrays.

The data were downloaded from the FAOSTAT database (https://www.fao.org/faostat/en/#data/GT) and from the World Bank’s World Development Indicators (https://databank.worldbank.org/source/world-development-indicators).


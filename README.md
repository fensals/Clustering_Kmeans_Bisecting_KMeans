# Clustering_Kmeans_Bisecting_KMeans

### Background

Social and economic factors, such as income, infant mortality, GDP and other Human Development Indices(HDI) can significantly affect how well and how long people live.
These factors are what show the improvements or decline brought about by the impact of governments on the lives of their citizens.

This project seeks to use the Kmeans and Bisecting Kmeans clustering algorithms to create groups of countries with similar socio economic performances


###  Objective

To cluster countries into groups based on similarity in their socio economic perfromance.

### Data Dictionary

The data has the following attributes:
- country: Name of the country
- child_mort: Death of children under 5 years of age per 1000 live births
- exports - Exports in % age of the GDP per capita
- health - The total spend on health given as % of GDP
- imports - The value of imports given as % of GDP per capita
- income - The net income per person
- inflation - Inflation rate %
- life_expec - Average life expectancy in years
- total_fer - The fertility rate - Average children per woman in the country
- gdpp - GDP per capita

## Conclusion

- 3 clusters of countries were created.These clusters are made up of countries with traits of developed, developing and underdeveloped countries respectively.

- The Clusters created by the Bisecting KMeans algorithm are more evenly distributed than those created by the KMeans algorithm

- Bisecting KMeans algorithm is more robust to outliers.

- The Bisecting KMeans model is a better clustering model for this data.

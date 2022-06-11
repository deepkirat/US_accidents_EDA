
# US Accidents EDA

Exploratory data analysis is an approach of analyzing 
data sets to summarize their main characteristics, 
often using statistical graphics and other data 
visualization methods.

This is a countrywide car accident dataset, which covers 49 states of the USA. The accident data are collected from February 2016 to Dec 2021, using multiple APIs that provide streaming traffic incident (or event) data. These APIs broadcast traffic data captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 2.8 million accident records in this dataset.

NOTE- It only contains 49 States, New york not 
being a part of it


## Data Preparation and Cleaning

- Load the file using Pandas
- Look at some information about the data & the columns
- Fix any missing or incorrect values
## Exploratory Analysis and Visualization

Columns analysed :

- City
- Start Time
- Temperature
- Weather Condition


## Summary and Conclusion

- 496 cities (less than 4%) have more than 1000 yearly accidents.
- There were 1110 cities with only 1 accident over the period of February 2016 to Dec 2021
- Most accidents happen in the time frame of from 1 pm to 5 pm with the highest number of accidents happening around 5 pm
- Looking at the graphs of monday and sunday we can see that most accidents occur the times when people generally commute to work whereas on sunday it's spread all over forming a bell curve
- Most accidents happen on the coastal regions with bigger cities
- The most number of accidents were on a fair weather condition which is intresting
## Acknowledgements

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.


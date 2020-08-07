# Introduction 
From World Health Organization - On 31 December 2019, WHO was alerted to several cases of pneumonia in Wuhan City, Hubei Province of China. The virus did not match any other known virus. This raised concern because when a virus is new, we do not know how it affects people. So daily level information on the affected people can give some interesting insights when it is made available to the broader data science community. Johns Hopkins University has made an excellent dashboard using the affected cases data. Data is extracted from the google sheets associated In this project, the total confirmed cases of Covid 19 around the world will visualize to find out how various country/provinces affected by the pandemic. This information can help to news reporter, health authorities and even people who their day to day life affected by this virus.
# Methodology 
After importing data, data latitude and longitude for each country added through getting API key from the service provider (Open Cage Geocode). Then, an statistical analysis performed through (describe()) to get a general idea about number of cases values and their distribution. Pyplot graphs and Folium used to visualize data.

# Results and Discussion
 The total number of cases in different countries around the word on February and August compared. In noticed that the cases were locally high in the country of origin “China”: in February and it rapidly spread out around the word on the August. USA has the maximum total number of cases in the world. The folium map lets user to click on each region and see the number of cases. It seems that there is not any relationship that countries closer to China has high number of the cases. 
 
![]( https://github.com/MinaMehrata/Capstone-Final-Assigment/blob/master/Image/pic1.png)

![]( https://github.com/MinaMehrata/Capstone-Final-Assigment/blob/master/Image/pic2.png)


![]( https://github.com/MinaMehrata/Capstone-Final-Assigment/blob/master/Image/pic3.PNG )

# Conclusion
China governments perfectly managed number of cases their country. Countries like USA, Brazil and India have the highest number of the cases in compare to other countries in August 2020. It is recommended to add population of each country data to data frame to analyze the number of cases/populations to get the better idea about the managing Covid 19 in different countries.




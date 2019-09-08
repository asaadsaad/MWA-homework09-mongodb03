# MWA - Homework 09 - Mongodb 03
## Exercise
This [JSON](http://mumstudents.org/cs572/lecture09/zips.zip) file contains a list of all the zip codes in the US. Import it into your MongoDB (`mongoimport`).  
Use the **Aggregation Framework** to write 4 pipelines:
* Find all the zip codes in Washington state.
* Find all the zip codes with a population less than 5000.
* Find all cities that have more than one zip code, sort the results by state and city name.
* Display the least populated city in each state

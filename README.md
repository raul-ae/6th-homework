Weather App

For this assignment the I make calls to Open Weather Map API, for this reaso i created an account to get my apikey: 663e2813643990a2ac771699fb50ba44

calls to the API are saved in a function named "runAjax" wich includes everything neccesary to perform the call: 
*name for the search
*call URL
*a function to execute

to perform the weather search:
the page requires an input section to introduce the city to search.
once introduced and the search button pressed, the city name is saved in a variable name citySearch.
at the same time the value is saved in local storage using an incremental key.
and also displayed in the history search side.

2 functions are anabled to pload the results of the search to the DOM:
*uploadSearch
*uploadForecast

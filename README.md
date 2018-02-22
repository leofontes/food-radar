# Food Truck Radar App

Simple React Native app developed to help everyone learn the basic concepts of RN and the specific details that will be required in future endeavors (maps, navigation, etc)
 
## API
In order to easily obtain data from the food trucks, the app will consume the [Street Food App API](https://streetfoodapp.com/api).
  
All resources have a base URL of http://data.streetfoodapp.com/1.1/
  * GET regions
  * GET schedule/:city
  * GET vendors/:vendor
  * GET locations/:city/:vendor

Documentation on expected responses can be found on the link above.

 ## Features
 The basic features of the app will be as follows:
  * Present a list of all the regions available
  * Present a list of all the food trucks
  * Filtering by region (city) or name of the food truck
  * Map that displays markers with the last position of the trucks
  * The markers show basic information about the truck and a button to view more info in detail
  * Toggle food trucks as favorites, saving this information locally on Realm (suggestion)
  * The detail screen presents complete information about the trucks
  * Allow sharing the information of the truck on Facebook, Twitter and Instagram
  
 

# INTERACTIVE-FRONTEND PROJECT

This application project is for to find hotels and limited to in any city in Turkey, Ireland, France, UK for now 
to be cost effective for me as Google Maps changed the policy.



By updating the code in line 9, countries, cities and also different places types( ex. post office, dentist, embassy, etc) can be 
added. 

```
'tu': {
          center: {lat: 38.585146, lng: 30.675218},
          zoom: 6
        },
        
``` 
and in line 65;
```
function search() {
        var search = {
          bounds: map.getBounds(),
          types: ['lodging']
        };  
```        


## UX

In the dropdown search, the user can search any country and then by choosing a city it shows the hotels with the green markers.

The Web app is divided into three sections;

Upper half is for search section where the second bottom shows the conutry choosen. After the search query is made below the map of city chosen, it shows the hotels.


# Features Left to Implement:

The weather app will be implemented according to the city chosen later on with 3 days forecast.

# Technologies Used

Bootstrap 3.3.7 (https://getbootstrap.com/docs/3.3/) is used for the design and Google Maps API (https://developers.google.com/maps/documentation/javascript/tutorial)is used to show the hotels.
# Bugs:

During implementation, I got JS notification  that some of the commands will be depreciated in 2019.

Also, I had issues with Ad Block when using Firefox where markers did not show up.


# Deployment
 
This applicaton is written om Cloud9 and then GitHub was chosen as a hosting platfrom. 


# Content
The photo used in this site was obtained from from (https://www.pexels.com/) [FREE and no license]

# Acknowledgements

I received inspiration for this project from **Dublin Code of Institute** (https://codeinstitute.net/) and I specially thank to my mentor **Ivan Michlovic** for his guidance during this project. 
Also, I thank to my beloved family for their understanding for the time while I worked on this project who supports me 
to achieve my goals.

# charger_challenge

WHAT IT IS?
Opcharge is a web app that strategically suggests locations for electric vehicle charging stations in the Windsor area.
Our algorithm optimizes charger stations availability in these areas by keeping track of the locations of current charging stations, 
taking account of the spaces between each station, and how long an electric vehicle can go without being recharged. 
We also limited our charging stations to the Windsor area by restricting any points that go outside the coordinate points from the West and East of Windsor. 
After writing our algorithm using python and using the coordinate points we were able to plot the optimized charging stations in the Windsor area. 
Which will be shown in the web app demo. {link}

HOW IT WORKS?
Basic functionality
-User can input number of stations
-Program outputs most optimal gps locations for each charger in the areas required
-Chargers are not placed on highways
Additional functionality
-Chargers are placed in key strategic locations thanks to machine learning
-Using clusters and centroids
-Street location of the coordinates displayed
-Does not place chargers in residential area
-Takes population density into account
-Chargers are not placed on small roads or roads with high traffic
-Medium traffic
-Shows chargers on the map



WHAT CHALLENGES DID WE FACE?
We ran through a lot of difficulties and challenges while building this web app most of which we were able to overcome with help from each other and the internet:

The first challenge we ran into was downloading all the longitude and latitude points of the windsor area. 
This process took very long as there were over a million data points. Choosing the right and best technology to plot this data was also very difficult and after 
research and trial and error we found that the Jupyter notebook was the best. 

After polishing our back end and algorithm it was challenging for us to link the front end and back end aspects of our project since we were using python to build the backend. 




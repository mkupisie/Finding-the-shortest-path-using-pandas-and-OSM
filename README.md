## Finding the shortest cycling path between starting point and endpoint

**The code enables the user to find the shortest path between the entered starting point and endpoint.**
To read and retrieve routable networks for cycling in _OpenStreetmap_ street network, OSMnx's _graph_from_place()_ function is used.
User must select first the area by providing area name, city and country. Place name must exist in the OpenStreetMap database 
(test can be run at _openstreetmap.org_ or _nominatim.openstreetmap.org_). 

After the entered area is found and returned, user can enter start point and end point. Based on the entered points program is finding the shortest path that is presented on interactive map with its length.

MapMyEvents_python.
Python 3 (3.6.4) script that maps events along a route (or for a single location).

Author:Vasily Kerov.

MapMyEvents_web is a web implemented (in Flask) 

The flow of the Python script:

1. Get trip origin and destination, trip dates, and the keyword from the web page.
2. Submit the origin and the destination to Google Map Directions API and get directions.
3. Parse directions to optimize the route for the next API call to Eventbrite for events.
4. Submit locations from the cleaned directions to Eventbrite and get events.
5. Save them to JSON.
6. Map events using Google Maps JavaScript API. (upon clicking on the markers an info window pops up with the details of the event).

Web-implemented (in Flask) version of the script is available at mapmyevents.pythonanywhere.com and in the repository: https://github.com/bazilione/MapMyEvents_web.git.

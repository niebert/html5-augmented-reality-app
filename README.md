html5-augmented-reality-app
===========================

Simple Augmented Reality App implemented using HTML5 and Cordova with Foursquare data overlay (and US cities overlay)

Uses Foursquare API to search for locations and plots the location on Google Maps.
Uses Cordova API to access device compass, accelerometer and geolocation.

The app must be compiled using Intel XDK or use Phonegap build.

App was developed by krisrak during 2 day XDK hackathon at Intel.
Developed using Intel XDK tool - http://html5dev-software.intel.com

### OpenLayers in XDK 
The Google Maps can be replaced by [OpenLayer](http://openlayers.org/en/latest/examples/geolocation.html). 

### Local Database
With [Mixare4JSON](https://niehaus.github.io/Mixare4JSON) users can build there own JSON database, that can be displayed in the augemented reality environment.

### Geometry 
With the geolocation the app know the latitude and longitude of the mobile device. With the compass the App knows in which direction the camera is heading. The accelerometer determines the angles in which the camera is heading (looking slighty up or down). The accelerometer sho

## Files
### index_UScities.html
The original XDK app shows 12 US Cities in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation. 


### index_UScities_xdkAR.html
Shows 12 US Cities in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation. Uses intel.xdk JS bridge API to enable camera in background and overlays data in augmented reality mode. 

### index_foursquare.html
Shows foursquare places data in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation.

* requires you to sign up for foursquare developer account and add client id and client secret to the source code_

### index_foursquare_xdkAR.html
Shows foursquare places data in list view, map view and augmented reality mode. Uses Cordova APIs for accelerometer, compass and geolocation. Uses intel.xdk JS bridge API to enable camera in background and overlays data in augmented reality mode. 

* requires you to sign up for foursquare developer account and add client id and client secret to the source code_

 __index.html = index_UScities.html__

## Screenshots


### foursquare listView 
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_listView.png)  


### foursquare mapView
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_mapView.png)
 
   
### foursquare XDK AR mode
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/foursquare_xdkARmode.png)  

### US Cities AR mode
![alt tag](https://raw.github.com/krisrak/html5-augmented-reality-app/master/screenshots/UScities_ARmode.png)

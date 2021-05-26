# HikingTrails-release

<img src="/hticon.png" width="130" height="200">

**1. About:**

**General:**

This is the public release repository of HikingTrails where you can download the latest version of HikingTrails (the sourcecode of HikingTrails resides in a private github repository):

https://github.com/r-meijerink/HikingTrails-release/releases/tag/v1.0

HikingTrails is a windows desktop application to create/manage hiking trails and corresponding pictures. The mission of HikingTrails is to offer hikers and landscape/nature photographers a free (off-cloud) hiking application to do the following:
- Easily manage, build, edit and view hiking trails on a Bing Map. You can draw routes in free draw mode or use the routing API (shortest distance/time between two points). Two routing API's are supported: open route service API (https://openrouteservice.org/) and the Bing Maps routes API. To use the routing functionality you need to get a Bing Maps API key or an open route service API key (how to do this is described in the help menu).
- To easily add point of interests with pictures to routes (you can import geotagged pictures) and build a clear collection of geotagged hiking pictures this way that is easily navigable and viewable.
- To share your routes with other users of HikingTrails and being able to import existing hiking trails (KML/GPX file).

The main functionalities are as followed:

- Create/edit/view routes on a Bing Map (Bing Maps WPF control).
- Create routes in free draw mode or use the routing API (shortest distance/time between two points). Two routing API's are supported: open route service API (https://openrouteservice.org/) and the Bing Maps routes API. Used routing profiles: Bing Maps API -> 'walking' , open route service API -> 'foot-hiking'.
- Add points of interests to your route and include a description, tags, a rating and a picture to each point of interest.
- For each route you can (among other things) enter a note, a category, and a date.
- Save your routes as an XML file on your desktop computer/laptop.
- Export a route/routes to KML and open them in Google Earth. Or you can also use the KML file in an offline navigation app like for example maps.me: (https://support.maps.me/hc/en-us/articles/207895029-How-to-import-bookmarks-). This way you can follow the route on your smartphone while walking.
- Export route/routes to XML (HikingTrails route file) and share them with other users.
- Import routes from a KML or GPX file.
- Import routes from a HikingTrails route file (XML file).
- Import geo-tagged pictures as POI points from a folder or import a geo-tagged picture file as POI point (this way you can easily couple your photo's to a location along the hiking trail).
- View statistics of your routes.
- View all your walked routes on a calendar.
- Quickly browse through the images of all the point of interests of all routes with the use of a treeview.
Each route has an app data folder that stores all the POI images of a route (the selected images are copied to this folder and can then be geotagged).
- Geotag your hiking pictures.


HikingTrails is loosely based on this webapplication:

http://www.wandermap.net/nl/#/z15/53.5667,13.2666998/terrain

It is an offline variant of it meant for the Windows desktop environment.

**Main Use-cases:**

The general main use-cases HikingTrails is offering are as following:

1- Being able to easily build, edit and view your walking routes on a Bing Map (on a local Windows PC and not in the cloud).

2- Being able to easily add point of interests with pictures to routes and build a clear collection of all your hiking pictures this way that is easily navigable and viewable.
This application aims to make the best possible connection between your local windows hiking images and your hiking routes.

3- Being able to easily share your routes with other users of HikingTrails including the pictures. 

Other important use-cases are:

1- Being able to export your Hiking trails to KML so you can open them in other GIS applications. 

2- Being able to import existing Hiking trails (in KML or GPX format).

3- Being able to see statitistics of your walked routes.

4- Being able to see all your routes on a clear calendar.

**Screenshots:**

![](/screenshot1.png)
![](/screenshot0.png)
![](/screenshot2.png)
![](/screenshot4.png)

![](/screenshot3.png)
![](/screenshot5.png)
![](/screenshot6.png)
![](/Screenshot10.png)



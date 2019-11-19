# ATLAN-Challenge
AIM- Identify commercial centers using Points of Interest (POI) data

Objective- 

1.Get Points of Interest from open data sources like open street maps (OSM).
2. Understand how spatial location data works
    Understand spatial vector data types and how to manipulate it using your language of choice.
    Understand necessary GIS concepts like projections, spatial clustering, etc.
3.Figure out a way of clustering these points into commercial centers/markets. You can use standard size polygons also to cluster the points.
4.Find and label the most significant clusters, statistically and intuitively. 
5.Visualize the resultant commercial centres/markets. 

Data source:POI (OSM) data- https://www.openstreetmap.org/#map=11/28.6518/77.2219


Step 1 : I extract the geojson data of Delhi city from overpass-turbo API then i read geojson data in jupyter notebook using geopandas library.
Step 2: There are many columns which has only None values so i removed that column then i left with "ID,Amenity,Geometry".
Step 3: i extracted the latitude and longitude from Geometry.
Step4:I applied Kmeans Clustering and DBScan Clustering Algorithm to find the no. of cluster .In Kmeans Algorithm,i make a elbow plot to find the no. of cluster. 






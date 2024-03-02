# Agglomerative_Clustering_In_Python
This project deals with how to create Agglomerative Hierarchical Clustering in Python Using Indian Pollution Dataset of 2010

## About the project:
In this project, I consider a 2010 indian pollution data. In that the features that measures pollution are 'S02', 'PM10' and 'NO2'. I get them and group them by state name. To do Agglomerative clustering, I scaled them and apply a z-transfornation on them to make their mean 0 and std 1.

I use the dendrogram and linkage modules that comes under scipy's cluster.hierarchy library. I use this as creating a dendrogram is easy using scipy.

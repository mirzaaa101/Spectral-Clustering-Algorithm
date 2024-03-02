# Spectral-Clustering-Algorithm

# Task
  1) Take a csv file with 14,590 rows and columns "Location Latitude", "Location Longitude", "value".
  2) Remove all rows that contain null value(s).
  3) Create a pairwise matrix with the distance between every ["Location Latitude", "Location Longitude"] and all the ["Location Latitude", "Location Longitude"] on the dataset. Use Vicenty distance as the distance function.
  4) Remove all rows that contain null value(s).
  5) Apply a K-Means clustering algorithm to the pairwise matrix with the nulls removed.
  6) Optimise K number using Elbow and or Silhouete method.
  7) Add a cluster identifier label to every row in the dataset.

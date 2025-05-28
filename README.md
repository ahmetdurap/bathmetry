# bathmetry
Bathymetric dataset of six region of Australia 
README for Bathymetric Dataset
Dataset Description
This dataset contains georeferenced bathymetric measurements along a coastal transect. The dataset consists
of four columns representing spatial coordinates, depth, and cumulative distance.
Column Description Unit Type Notes
x Longitude decimal degrees float WGS84 reference system
y Latitude decimal degrees float WGS84 reference system
z Depth meters integer Negative values indicate depth below sea level
distance Cumulative Distance kilometers float Computed using geodesic distance from starting point
Table 1: Column descriptions for the dataset.
Sample Data
x y z distance
133.5786047 -39.6342174 -5568 0
133.5854423 -39.62871112 -5582 0.855009935
133.5922798 -39.62320483 -5590 1.710019871
133.5991174 -39.61769855 -5587 2.565029806
Usage
This dataset is suitable for:
• Bathymetric surface interpolation and visualization
• Geospatial machine learning applications
• Temporal-spatial analysis in marine studies
Notes
• Ensure geodesic distance is interpreted in kilometers for accurate modeling.
• Depths are referenced to mean sea level.
1

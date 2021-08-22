Welcome to AgriTech---USGS-LIDAR's documentation!
=================================================

This project creates a package to access Entwine Point Tile(EPT) LiDAR data from AWS and return the data in the format of a geopandas dataframe for ease of analysis.

**AgriTech---USGS-LIDAR** is a project for analysing how  how water flows through a maize farm field.
Water is very important for crop growth and health.  We can better predict maize harvest if we better understand how water flows through a field, and which parts are likely to be flooded or too dry. One important ingredient to understanding water flow in a field is by measuring the elevation of the field at many points. The USGS recently released high resolution elevation data as a lidar point cloud called USGS 3DEP in a public dataset on Amazon. This dataset is essential to build models of water flow and predict plant health and maize harvest. 

**TO BE DONE**: produce an easy to use, reliable and well designed python module that domain experts and data scientists can use to fetch, visualise, and transform publicly available satellite and LIDAR data. In particular, your code should interface with USGS 3DEP and fetch data using their API. 

**DATA**: LIDAR high definition elevation data - `USGS 3DEP <https://www.usgs.gov/core-science-systems/ngp/3dep>`_ - The `USGS recently released high resolution elevation data as a lidar point cloud <https://www.usgs.gov/news/usgs-3dep-lidar-point-cloud-now-available-amazon-public-dataset>`_ in a `public dataset on Amazon <https://registry.opendata.aws/usgs-lidar/>`_. This dataset is complicated to understand and use, and it would be useful to have an easy way to access and use it in order to build models of water flow and predict plant health and maize harvest. 

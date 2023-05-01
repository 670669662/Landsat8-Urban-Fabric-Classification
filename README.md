# Landsat8-Urban-Fabric-Classification
This project aims to process and analyze land cover data to understand land use patterns within urban environments better. Using the training dataset the Google Earth Engine Community provided, we segment land cover into categories, including buildings, vegetation, and water. We then apply this methodology to several African cities lacking detailed land cover information, utilizing global Landsat 8 data and the Random Forest algorithm for prediction. This project will help urban planners, researchers, and policymakers better understand land cover characteristics in these communities, providing valuable data for future urban development and environmental conservation efforts.

## Method Overview (5 Steps):

1. **Import necessary libraries and load the training dataset** provided by the Google Earth Engine Community.
2. **Segment the land cover data** into categories: buildings, vegetation, and water.
3. **Apply the segmentation methodology** to several African cities with Landsat 8 data.
4. **Use the Random Forest algorithm** to predict land cover types for the target cities.
5. **Calculate the area and percentage** of different land cover types for each region.
6. **Analyze and visualize the results** to better understand land cover characteristics in these communities.

## Required Libraries
To install the necessary libraries, run the following commands:

```bash
pip install geopandas
pip install rasterio
pip install numpy
pip install pandas
```
## Segement Results
![IMAGE COLLECTIN](https://user-images.githubusercontent.com/70087271/235382142-e3900edd-dad5-486c-8f94-3654d242dc51.jpg)
![ML IMAGE COLLECTIN](https://user-images.githubusercontent.com/70087271/235382159-c081593c-0836-45b6-a1d5-97bec3902b3a.jpg)

| NDVI_mean   | NDBI_mean   | Building_area | Building_percentage | Forest_area | Forest_percentage | Water_area | Water_percentage|
|-------------|-------------|---------------|---------------------|-------------|-------------------|------------|-----------------|
| 0.258893094 | -0.012632252| 1.27E+07      | 79.98489642         | 3408868.235 | 21.46430796       | 0          | 0               |



## Acknowledgements

I would like to express our gratitude to our teammates Kelly Shining Hong, Candice Siyun Ji, and Wei Xiao. The technical implementation of this code is part of the Conflict Urbanism 2023 project. For the complete final project, please visit [https://centerforspatialresearch.github.io/conflict_urbanism_sp2023/2023/04/28/Those-Who-Live-and-Travel-in-the-Dark.html](https://centerforspatialresearch.github.io/conflict_urbanism_sp2023/2023/04/28/Those-Who-Live-and-Travel-in-the-Dark.html).






# Project to display two datsets on side by side maps

## Section 1. This code will allow you to display two datasets on their own map side by side.

In order for your datasets to correctly display on the maps they must have a geometry column. 
If you only have X and Y co-ordinates you can use the code included in the jupiter file to create the geometry column.

Please enter the name of your datasets as you want them to appear on the maps in the code: name_1 = , and name_2 = .

Please add your dataset file path in the code as: dataset_1 = , and dataset_2 = .

The final step will save a local copy of the maps and open them in a pop-up window.

## Section 2. This code will compare the datasets using specific columns.

This will compare how many records are in both datasets. 


Dataset_1 has 9043 records, dataset_2_uniq has 2433 records
There are 398 geomentry records in dataset_1 that are also in dataset_2_uniq
There are 385 geometry records in dataset_2_uniq that are also in dataset_1
There are 5652 unique uprns in dataset_1 and 1433 unique uprns in dataset_2_uniq
There are 956 uprn records in dataset_1 that are also in dataset_2_uniq, this is 10.6 percent of dataset_1
There are 956 uprn records in dataset_2_uniq that are also in dataset_1 , this is 39.3 percent of dataset_2_uniq

Dataset_1 recipe: Land use: Site: filter: description = Post Office
Dataset_2 filtered on classification code and not historic

## 

This was made by [Sue Phillips](mailto:sue.phillips@ons.gov.uk) as part of her apprenticeship rotation through the ONS Geospatial team in DALI.
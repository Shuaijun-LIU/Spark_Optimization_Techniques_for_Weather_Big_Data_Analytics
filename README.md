# Exploring Apache Spark Performance Optimization Techniques Deep Learning-Driven Meteorological Big Data Analytics
### <u>*Author:</u> [Shuaijun Liu: — Click here to go to my Personal Web Page](https://shuaijun-liu.github.io/)


- **code**
  - `1.Dataset_Visualization_and_Acquisition.ipynb`
  - `2.Processing_and_Model_NoSpark.ipynb`
  - `3.Processing_and_Model_Spark.ipynb`

- **data**
  - `2014_2024`
  - `stations_infor`
  - `country-list.txt`
  - `isd-format-document.pdf`
  - `isd-lite-format.pdf`
  - `readme.txt`

In the 'data' section, you can see the small dataset of hourly weather data and station information data for the last 10 years in Japan that we used to train the model, which are distributed and stored in json and csv formats in the '2014_2024' and 'station_ infor' folders. Other supporting files can also be found in 'data', such as additional information for visualizing the dataset, and a 'readme' file exists for the dataset for detailed description.

In the 'code' section, we have divided the data processing, modeling and prediction into three parts, including:1. Initial data visualization and acquisition. 2. modeling and prediction without applying spark and its optimization techniques. 3. modeling and prediction after using spark and its optimization techniques. In which the third part is the focus of exploration in this term paper, we used optimization techniques such as data caching to analyze over 10gb of meteorological big data and modeled it with good results.


-------------------------------------------------------------------------------------------------
(To Others: All code is original to the paper and should not be reproduced without permission!)

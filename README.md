# surfs_up

## Overview of the analysis
In order to show an investor a surf shop is sustainable to open up in Oahu, Hawaii, analysis on a weather dataset provided in SQLite database was run using the query tool SQLAlchemy. This analysis focused on the temperature data for the months of June and Decemeber in Oahu. The results were summarized and compared.

## Results
- The mean temperature, maximum temperature, minimum temperature in June are all higher than the mean temperature, maximum temperature, minimum temperature in December.

![June](https://user-images.githubusercontent.com/84931545/130381041-a7b89209-9267-4d65-93d6-7b15d3da91a4.PNG)

![December](https://user-images.githubusercontent.com/84931545/130381048-0c520699-868a-431c-a546-fbcc2edc481b.PNG)

- Base on the number of counts, there are more data points collected in June than in December.
- The standard deviation for the temperatures is 3.75 in December which is higher than the standard deviation for the temperatures in June which is 3.26.

## Summary
The differences in mean, max, min temperature between the two months are not dramatic and the standard deviations are similar as well between the two months. At each quartile, there is around a 3-4 degree Fahrenheit difference between June and December with June having the higher temperature. This is not a surprise since June is a summer month in Hawaii. 

Additional queries could be executed to find out the precipitation statistics in June and/or in December. Filtering out the specific year could also be done if one desires to observe the difference between years. Queries could look like the following.


Query for precipitation of Decemeber.

![Precipitation 12](https://user-images.githubusercontent.com/84931545/130380588-188b5ac9-9b45-4940-a615-4847dccb374a.PNG)


Query for Precipitation of June of 2017.

![Precipitation201706](https://user-images.githubusercontent.com/84931545/130380595-ecca666e-a3ac-49e1-bd11-e94b18b3732d.PNG)


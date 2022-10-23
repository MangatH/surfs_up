# surfs_up

## Overview of the analysis
The analysis is primarily devoted to weather analytics, which is required to open a Surf and Shake shop. W. Avy, an investor in this business plan, who is famous for his love of surfing, asked to run some analytics on a weather data set he has from the very island which is the location to open shop, the beautiful Awahoo.

### Purpose of the analysis
* W. Avy likes the analysis, but he wants more information about temperature trends before opening the surf shop. 
* Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

### Resources
Using Python, Pandas functions and methods, and SQLAlchemy, filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December.

## Results
* The first key difference is in the value counts for the months of June and December. The value count for June is 1700 whereas for the month of December is 1517.

* Another key difference is drawn while looking at the summary statistics for the month of June and December. The mean temperature for June is 74.9°F which is higher as compared to December i.e. 71°F.

* Furthermore, a difference can also be drawn between the minimum and maximum temperature for these two months. The maximum and minimium temperature for June is 85°F and 64°F, on the other hand for December it is 83°F and 56°F respectively.

* The following images shows these differences at a glance.

<img width="274" alt="Screen Shot 2022-10-23 at 6 58 11 PM" src="https://user-images.githubusercontent.com/111387025/197395032-de1b89e3-fb80-4d03-bdc6-718e5779ee93.png">
<img width="319" alt="Screen Shot 2022-10-23 at 6 58 55 PM" src="https://user-images.githubusercontent.com/111387025/197395037-a8b3b660-59c1-4e3a-91ad-03ebd5b71eca.png">

## Summary and additional queries
* The results indicate that the opening of the surf shop might turn out to be a good idea. 

* The mean temperature, as seen through the summary statistics for the months of June and December, seems to be idle for such type of business.

* However, in order to have a better insight it would be best to look at the precipitation data as well.
Precipitation is one of the major factors affecting such kind of businesses. Therefore, an additional query can be made to look at the precipitation, by slightly changing the query as shown:

<img width="1403" alt="Screen Shot 2022-10-23 at 7 07 23 PM" src="https://user-images.githubusercontent.com/111387025/197395486-aa08edf7-4bb0-4506-a3be-43a4d250ec4e.png">

* Further, looking at the summary statistics for both these columns- 'temperature' and 'precipitation' to have a better insight.

<img width="540" alt="Screen Shot 2022-10-23 at 7 09 29 PM" src="https://user-images.githubusercontent.com/111387025/197395567-37025bce-35bb-4f1c-81d9-877a783acb74.png">

* The similar kind of exercise can be done for the month of December.

* Additionally, a histogram can also be drawn using the 'plot' function, which would help to take a clear look on the results just by a glance. For exmaple, the histogram for the month of December would look like:

<img width="826" alt="Screen Shot 2022-10-23 at 7 14 00 PM" src="https://user-images.githubusercontent.com/111387025/197395757-6dd006fb-e5c2-4a44-9dae-c6c220221180.png">

* Another histogram can be made for the month of June.

* It would also assist in understanding the key differences in the temperature data of these two months simultaneously, just by looking at the histograms.


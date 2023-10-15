# XternDataScienceWSA
2024 Xtern Data Science Work Sample Assessment

## Task
Utilize an open-source map API such as Google Map API, OpenStreetMap, or AWS Map API to collect useful data on local food trucks. Clean and organize your data then present it as a table or data frame. Such a table or data frame of local food trucks should contain basic information such as name, address, rating, website, open hour, and cuisine type. See Example_Data.csv for an example list.

Review the data and draw any conclusions you can find from the data set you gathered. Present a two-day weekend foodie plan with time, location name, address, cuisine, travel time, travel distance, transportation type, and visualization of the travel route. The travel route is best visualized by building on your own. There are tons of Geographic information system packages in both Python and R! See Example_Plan.csv for an example plan.

## Methods
To accomplish the above task I used the Google Map API to obtain results from the search "food truck Indianapolis". With these results, I selected 4 food trucks for Saturday and 4 more for Sunday. The selections were made so that someone could visit one in the morning for breakfast/brunch, one in the early afternoon, one for dinner, and one late night (trucks open until midnight or later). 

My original plan to create the maps also used the Google Map API capabilities, however, I struggled to get my system set up to be able to present the maps that were produced. In a second effort to visualize the route generated in the schedules, I used a combination of the OpenStreetMap API to get the latitude and longitude of each address for the location and then used folium to map the route from location to location.

## Results
The full notebook of code is located in a Jupyter Notebook file located in the attached folder. 
The final schedules can be found under the names ex_#_day.csv with the maps in day#_map.html

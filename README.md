# Overview of Analysis 

For this project, our analysis digs deeper into the temperature trends; specifically, temperature data for months of June and December in Oahu. We will determine the summary stats for June and December by using Python, Pandas functions and methods and SQLAlchemy. Our dataset pertaining to weather conditions has been stored in an SQLite database. SQLAlchemy is used to connect as well as generate queries to pull the information we need to further deepen our analysis. 

## Results 

From our results, we've created DataFrames where temperatures in June and December are added onto a list. The summary of the statistics generated for the DataFrame is shown down below in Figures 1 and 2:

**Figure1: June Temperatures**

![Screen Shot 2022-08-20 at 8 28 58 PM](https://user-images.githubusercontent.com/106577074/185774112-ae8e74c3-6f80-40a3-ae68-91f44ea279f8.png)

**Figure 1.1**

![Screen Shot 2022-08-20 at 8 32 54 PM](https://user-images.githubusercontent.com/106577074/185774240-eb03cbf8-533a-45c7-b8dc-a7c632f2f94b.png)

**Figure2: December Temperatures**

![Screen Shot 2022-08-20 at 8 29 04 PM](https://user-images.githubusercontent.com/106577074/185774131-bcedf846-d809-4a41-88e5-b7b34e384a87.png)

**Figure 2.1**

![Screen Shot 2022-08-20 at 8 33 12 PM](https://user-images.githubusercontent.com/106577074/185774246-0fdf387a-023b-46eb-9f18-42caba45eb51.png)


From our DataFrames and their corresponding graphs, we can conclude:

- June and December showcase similar minimum, maximum and average temps 
- The average temperature for both months is between 72-75 degrees F
- Seems the temperature stays pretty consistent year round based on our dataset

## Summary 

Based on our visualizations of the data for June and December above, it seems the average temperature for June is 75 and December is 71. Therefore, the temperatures for summer and winter stays in the 70s. 

In order to better backup our overall analysis, additional queries were created for months February and October. The reason I chose these months were becuase seasonality wise, they differ from winter and summer as we've moved onto early Spring-ish to fall. The results of our analysis is down below:

**Figure 3: February Temperatures**

![Screen Shot 2022-08-20 at 8 45 59 PM](https://user-images.githubusercontent.com/106577074/185774603-f95b2b59-403a-49ed-96a2-2f29ee96df4f.png)

**Figure 4: October Temperatures**

![Screen Shot 2022-08-20 at 8 48 32 PM](https://user-images.githubusercontent.com/106577074/185774614-a60c8eb0-0389-4ede-9a43-06fc5faa44c8.png)

We can see here that average temperature in these two months stays within the 70-75 degrees. Therefore, we can confidently let our investor know that opening a Surf n' Shake shop in Oahu, Hawaii will deliver beautiful weather year round without much precipitation. 

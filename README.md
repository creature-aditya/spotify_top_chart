# spotify_top_chart
Spotify top chart is a PySpark based project in which spotify dataset with 25 attributes is taken in analysis directly from AWS S3 location. The data is checked for null values, duplicates and other anomalies. After cleaning the data, major insights attributions are marked by which we are about to operate on dataset.

As of now, we are taking 3 entities:
    1. Top artists worldwide.
    2. Top artists in each country.
    3. Top dancable songs worldwide.
    We can't make top karaoke song worldwide as we can't sing in multiple languages :)

2 of these ouput are created using TempView and written PySpark SQL query meanwhile remaining 1 has PySpark dataframe used to write directly to the output CSV file.

All 3 output CSV files are stored in same S3 bucket with same location as input dataset.
![image](https://github.com/creature-aditya/spotify_top_chart/assets/83203134/6345d3ae-8c9c-43e5-91ee-b171db643f2f)


You can find the dataset csv file using this link

https://drive.google.com/file/d/1z10InMEN9lC5ItxHvRwUPylSXNcuGhs_/view?usp=sharing

Sample of dataset:
![image](https://github.com/creature-aditya/spotify_top_chart/assets/83203134/772674bc-e5e3-4d02-afc8-69f91421c40e)


Happy Coding!

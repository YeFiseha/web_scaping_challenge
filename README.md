# web_scaping_challenge
# Web-scraping and data analysis project

# Assignment 1: Scrape titles and preview text from Mars news articles.
Results:
Automated browsing (with Splinter) is used to visit the Mars news site, and the HTML code is extracted (with Beautiful Soup). 
The titles and preview text of the news articles are scraped and extracted. 
The scraped information is stored in the following Python data structures:
1. each title-and-preview pair is stored in a Python dictionary and, each dictionary is given two keys: title and preview,
2. all the dictionaries are stored in a Python list,
3. list is printed in the notebook.

# Assignment 2: Scrape and analyze Mars weather data.
Results:
A Beautiful Soup object is used to scrape the data in the HTML table.
The scraped data is assembled into a Pandas DataFrame.
The data types associated with each column are examined.
The dataset is analyzed by using Pandas functions – and the findings are:
1. Number of months on Mars
2. Number of Martian (and not Earth) days worth of data in the dataset
3. coldest and the warmest months on Mars:
3.1 average minimum daily temperature for all the months on Mars
3.2 results are plotted on a bar chart
4. months with the lowest and highest atmospheric pressure on Mars:
4.1 average daily atmospheric pressure of all the months
4.2 results are plotted on a bar chart
5. number of terrestrial (Earth) days in a Martian year
5.1 number of days elapsed on Earth in the time that Mars circles the Sun once
5.2 A visual estimate by plotting daily minimum temperature 
6. 	DataFrame is exported to a CSV file

# References
Part_1_mars_news.ipy file is for the first part of the assignment: scraping titles and preview of text from Mars news articles.
Part_2_mars_weathers.ipy file is for the second part of the assignment: scraping and analyzing Mars weather data.
mars_weather_data.csv is the DataFrame exported to a csv file.




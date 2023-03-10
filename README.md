# webscraping-challenge

PART 1

First, I visited the Mars news website and created a Beautiful Soup object to extract the elements from the website.

I stored the results in an empty dictionary and looped through all the elements to find the title and preview of the articles. 

The list was exported and the browser was quit.

PART 2

To scrape and analyze the Mars weather data, I visited the temperature Mars facts website and created a Beautiful Soup object out of the data table. 

All rows were extracted and a DataFrame was created with the id, terrestrial_date, sol, ls, month, min_temp, and pressure information. 

The data types of the columns were adjusted for analysis.

By analyzing the data I was able to answer how many months exist on Mars, how many Martian days are in the dataset, the average low temperature by month and a visual representation of the coldest and warmest months, the average pressure by month and a visual of the highest and lowest months, and how many Earth days exist in a Martian year using a visual estimate. 

The DataFrame was exported to marsweather.csv
# webscraping-challenge
In this challenge, we were tasked to implement our learnings of web scraping.\
This challenge was split into two parts; scrape titles and texts from a webpage containing news of Mars, and scrape and analyse data from a webpage containing a data table of Mars temperature data.

## Part 1 - Scrape Titles and Preview Text from Mars News
In this part, we are provided with the url (see below for link) of a news page containing information of Mars, in which we are tasked with the below list:
* extract all text elements within the body of the page
* list the list of titles and preview text located within the page\

The code for this can be found in the 'Starter_Code' directory within this repository, and in the file 'part_1_mars_news.ipynb\
url = https://static.bc-edx.com/data/web/mars_news/index.html

## Part 2 - Scrape and Analyse Mars Weather Data
This part contains a url (see below for link) of a webpage containing a table with the following data related to Mars weather:
* id of the transmission from the Curiosity rover
* the date on Earth (or terrestrial date)
* number of elapsed sols (Martian days) since the Curiousity rover landed on Mars
* the solar longitude (sl)
* the Martian month
* minimum temperature recorded in the sol
* atmospheric pressure at the Curiousity's location\

The code located within the 'Starter_Code' directory under the file 'part_2_mars_weather', scrapes the table and stores it in a pandas Dataframe saved as a csv named 'data.csv', converting it to the correct data type for the following analysis:
* count of months on Mars
* count of number of Martian days worth of data
* average minimum temperature by Martian month, represented in a bar plot
* average atmospheric pressure by Martian month, represented in a bar plot
* a plot of the minimum temperature for each day of data recorded\

From this analysis, we can conclude that, on average, the coldest month is the third month, with the eigth month the warmest. Additionally, we see that the atmospheric pressure is, on average, lowest in the sixth month and greatest in the ninth. Lastly, based on the data available we can conclude that a year on Mars appears to be 675 days, which is close to the actual length of a year of 687 days.\

url = https://static.bc-edx.com/data/web/mars_facts/temperature.html

## Running
For this code to run successfully, python is required to be installed along with libraries such as; pandas, jupyter, splinter, Beautiful Soup, and matplotlib. One method to install these programs is to download Anaconda - link below. To run this code, open the file within Jupyter, ensure that the input files are directed correctly and run!\
Anaconda install: https://docs.anaconda.com/free/anaconda/install/

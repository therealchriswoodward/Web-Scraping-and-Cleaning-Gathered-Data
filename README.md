# Web Scraping and Cleaning Gathered Data
Web scraping for book data, and cleaning the gatherings up in a dataframe

***
If you would like to jump straight to my notebook:

[My Notebook](#https://github.com/therealchriswoodward/Web-Scraping-and-Cleaning-Gathered-Data/blob/main/Selenium%20Practice.ipynb)
***

In this project, I used several libraries to build a web scraping program for gathering book data (Title, Price, Rating)

The purpose of the project was to scrape the data, get it into a Pandas data frame, and clean the data into a state where normal data wrangling and mining can occur. I wanted to show my skills in web scraping because it can be challenging to get scraped data into a state where it can be analyzed; you often have phrases and other complex strings that must be cleaned as well as the fact that you often need the actual name of the attribute rather than just a text field, which I handled in this project.

***

Features:

* A delay is programmed to not make requests to quickly
* Scraping occurs over more than one page
* Titles, Prices, and Ratings are gathered
* Length of arrays are counted
* Puntuation is removed from the prices
* Prices are converted from Pounds to USD
* Prices are rounded once converted to USD
* Ratings are cleaned via column splitting
* Text in Rating is converted to numerical format
* A histogram of the prices is plotted
* A boxplot of the prices is plotted

***

# Website:

[Books to Scrape | http://books.toscrape.com/catalogue/page-1.html](http://books.toscrape.com/catalogue/page-1.html)

For any other analysts who wish to practice or students who wish to learn, Books to Scrape is a great resource.
***

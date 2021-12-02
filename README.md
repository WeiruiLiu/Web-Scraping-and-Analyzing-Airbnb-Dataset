# Web Scraping and Analyzing Airbnb Data in DMV areas
Individual Project - Rayna Liu

## Background and Introduction
Founded in 2008, Airbnb has become a giant in the short-stay homestay industry in just nine years. It provides a platform for hosts to post information about short-term rentals or rooms, allowing travelers to search and book unique properties worldwide based on their needs.

For customers, they want to know whether they are getting a reasonable price. Will they overpay? Whether there is a difference in amenities and prices between the same property type and room structure in the same area. For hosts, which property types and room structure are more prevalent in the area, and which amenities will be offered more competitive advantages? For this, I will use [Airbnb](https://www.airbnb.com/), to help customers, and hosts better understand lodging data in the DMV area.

This will be done in two steps: 

### Dataset
I. Web Scraping **(Project 2 Web Scraping.ipynb)**: Use BeautifulSoup to gather lodging descripitions and data.
* Define a function to scrape information from Airbnb web page with specific places to stay and save each web page information into an individual csv file.
* Scrape lodgings' information on the DMV area (District of Columbia, Maryland, Virginia). Airbnb will show 300 lodgings' information (15 pages) for each DMV area.
* It will take about 2 minutes to complete web scraping. In total 45 csv files (900 lodgings' information) and save in **Web Scraping Dataset from Airbnb Website - Nov 9, 2020** folder.

### Analysis and Visualization
II. Cleaning and Analyzing **(Project 2 Cleaning and Analyzing.ipynb)**: Analyze and compare the lodging data in different DMV areas.
* The csv file that come from 900 lodging’s information runs of **(Project 2 Web Scraping.ipynb)** on Nov 9, 2020.
* Table of Contents:
  * Common Location
  * Title Name Preference
  * Property Type in DMV area
  * Correlation Coefficients Between Variables 
  * Analysis of Room Structure in DMV area
  * Analysis of Amenities and Facilities of Lodging in DMV area
  * Popular Lodging with Best Price in DMV area
  * Interactive

## How it Works
  1. Watch video presentation click Youtube link [Here](https://youtu.be/zbClqCMHpQo).
  2. Read **PPT Presentation.pptx**.
  3. Check Python Code and Visualiztion in [Web Scraping](https://weiruiliu.github.io/Web-Scraping-and-Analyzing-Airbnb-Dataset/Project%202%20Web%20Scraping.html) and [Cleaning and Analyzing](https://weiruiliu.github.io/Web-Scraping-and-Analyzing-Airbnb-Dataset/Project%202%20Cleaning%20and%20Analyzing.html) on Github pages.

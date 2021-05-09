# Web Scraping and Analyzing Aairbnb Data in DMV areas

Founded in 2008, Airbnb has become a giant in the short-stay homestay industry in just nine years. It provides a platform for hosts to post information about short-term rentals or rooms, allowing travelers to search and book unique properties worldwide based on their needs.

For customers, they want to know whether they are getting a reasonable price. Will they overpay? Whether there is a difference in amenities and prices between the same property type and room structure in the same area. For hosts, which property types and room structure are more prevalent in the area, and which amenities will be offered more competitive advantages? For this, I will use [Airbnb](https://www.airbnb.com/), to help customers, and hosts better understand lodging data in the DMV area.

This will be done in two steps: 

> I. Web Scraping (Project 2 Web Scraping.ipynb): Use BeautifulSoup to gather lodging descripitions and data.
> > - Define a function to scrape information from Airbnb web page with specific places to stay and save each web page information into an individual csv file.
> > - I will scrape lodgings' information on the DMV area (District of Columbia, Maryland, Virginia). Airbnb will show 300 lodgings' information (15 pages) for each area I retrieve.
> > - It will take about 2 minutes to complete.

> II. Cleaning and Analyzing (Project 2 Cleaning and Analyzing.ipynb): Analyze and compare the lodging data in different DMV areas.
> > - The CSV file that I'm going to analyze come from 900 lodging’s information runs of the Project2: Web Scraping notebook on Nov 9, 2020.
> > > Table of Contents:
> > > - a. Common Location
> > > - b. Title Name Preference
> > > - c. Property Type in DMV area
> > >  - 

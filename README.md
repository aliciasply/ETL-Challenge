## ETL Web-Scraping on Used Rolex watch prices from 3 Websites

![RolexWatch](images/cover.png)

### Introduction:

* I am always curious about Rolex watches, therefore I decided to browse the different models of the watch and see what are the price difference with the collection of data from three reputable watch sites. 
* I chose RealReal.com, Crownandcaliber.com, and Watchbox.com to gather data by web-scraping technique. 


### Project Description:

1. Extracting data from scraping all three websites.
* I scraped realreal.com and find the product id, watch brand, watch model, watch price and the link directly link to the website.
2. Transforming the data
* Converted the data into a dataframe, followed by cleaning up the data by changing its data type and removed any unncessary symbols from the dataframe.
3.  Loading the data into the database 
* First, I built a path to connect to the SQL server, followed by using the conn = engine.connect() function to connect to the database.
* After connecting the data to the SQL server via Python, I read the data directly from the database. 
* To learn about the summary of watch prices with different models, I used dataframe.describe() to view the whole summary. 
* I created a graph to show the average price of each watches based on its model. 

### Average Used Rolex watch prices by RealReal.com
![RealRealWatch](images/realreal.png)

### Average Used Rolex watch prices by Crownandcaliber.com
![RealRealWatch](images/crownandcaliber.png)

### Average Used Rolex watch prices by Watchbox.com
![RealRealWatch](images/watchbox.png)

### Average Used Rolex watch prices across 3 websites 
![RealRealWatch](images/combine_graph.png)

### Copyright

Alicia Ly.

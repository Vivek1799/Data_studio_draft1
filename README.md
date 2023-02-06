Introduction

This Project is about looking at how inflation has hit grocery stores and affected the prices of basic food staples - Eggs, Bread and Milk. We look at the grocery stores near Columbia University as the neighborhood has many international students living who have no option but to shop here. 

Data Collection

1) I started by scraping all four major grocery stores around campus - Westside Market, Morton Williams, C-town and Food-town on the Instacart website for their price listings for Eggs, Bread and Milk. 

2) I had to use Playwright to scrape the Instacart website as it uses dynamic javascript to display the information. I automated the data collection process by writing the script. BeautifulSoup doesn’t help in scraping this website. 

3) I scraped for all the products on the first page, when I searched for the product. I searched for ‘Regular Eggs’ for Eggs, ‘White Bread’ for Bread and ‘Whole Milk’ for milk. ( for milk, I got organic whole milk as these were the most popular options around the Columbia neighborhood.) Tools used for this were pandas.

4) After scraping, I got all this data into a dataframe and filtered the data, to make it uniform. 

5) For eggs, I used the 12 count /dozen as the unit of measurement, 64 fl oz for milk and 16-20oz for bread. I filtered out the products with different counts. 


Tools used

Playwright, Panda, Datawrapper, HTML, CSS and Bootstrap.

Findings 

The prices of these items in the neighborhood around Columbia University campus are more expensive than average prices of New York and the U.S. 

Limitations

I could only scrape four stores for this project. I couldn’t scrape for small local stores as they don’t have their prices listed online. I used Instacart for scraping and prices listed online can vary by the actual store prices. 




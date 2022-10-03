# scraping-amazon-bestseller-books
### Scraping Bestseller books from amazon

Check out the Jupyter notebook here : https://jovian.ai/1242sanjay/web-scrapping-project-2


Web Scraping is the process of extracting data from web in a automated way. Here we scrape IMDb for getting movies data.

[Amazon](https://www.amazon.in/) is one of the largest online marketplaces in the United States, if not the world. Users can buy items from Amazon or a third-party seller on Amazon, or sell their own items. Orders are then delivered using common worldwide courier services. The company also sells its own line of technology items.

The page https://www.amazon.in/gp/bestsellers/books/ provides the list of best seller books on amazon and we are going to scrape these bestseller books details like position, name, writer, price, rating and total reviews. Here we'll use python `requests` and `beautifulsoup4` libraries to scrape this data.

We'll follow the below given steps:
1. Download the webpage using `requests`
2. Parse the HTML source code using `BeautifulSoup`
3. Extract position, name, writer, price, rating and total reviews from the page
4. Store the extracted information into Python lists and dictionary
5. Save the extracted information into a CSV file

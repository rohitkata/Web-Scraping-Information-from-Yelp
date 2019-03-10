# Web-Scraping-Information-from-Yelp

## Rationale

Scraping restaurant names, links, reviews and other details for 300 restaurants in an area from Yelp. This is done to building a relevant data set on which several analysis can be performed.

## Methodology

After identifying which pages to scrape, identify the logic of the URL as the URL structure of the pages I wanted to scrape changes. As a result I obtained the URL links of all the pages I wanted to scrape. Then I set about understanding the HTML structure of a single page. To parse the HTML document and extract the relevant data, I used BeautifulSoup. I obtained a data set that contained name of the restaurant,  reviews, overall ratings, price range of the restaurant, health score and also a few categorical variables such as Takes reservation, delivery etc.

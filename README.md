# Scraping different categories of products on Kushal's using Python

Check out this project on jupyter notebook : https://jovian.ai/ashwinishetti15/web-scrapping-kushal-project

### About Kushal's
* [Kushals.com](https://www.kushals.com/) is an exciting new way to buy Fashion and Silver Jewellery and Accessories Online.
* [Kushals.com](https://www.kushals.com/) provides a intuitive interface and detailed description to help you search and order the perfect jewellery to match your needs for all occasions.
* In [Kushals.com](https://www.kushals.com/) here we are scraping categories and URL for the categories. Then we are scraping each categories top products details like Product Name, Product price, URL of the product.

### Introduction about Web Scraping:
Web scraping is the process of extracting data from websites. Some data that is available on the web is presented in a format that makes it easier to collect and use it.
We are scraping https://www.kushals.com/

### Tools that are used for the project
* Python
* Requests
* Beautiful Soup
* Pandas

### Project Outline
1. Choosing the website for scraping and check whether it is scrapable or not.
2. Download the webpage (Kushal's website) using requests library.
3. Installing and importing required libraries.
4. Extracting Category Name and URLs from the website using BeautilfulSoup.
5. Accessing each category by the URL.
6. Parsing top 16 products into 3 fields: Product Title, Price, URL.
7. Storing the scraped data into dictionary.
8. Saving the data into CSV files using pandas which are stored in a single folder.

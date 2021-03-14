#### Sharing Part of my project work done while taking Specialist Diploma In Applied Artificial Intelligence

# ScrapingUsingScrapy
Using python Scrapy module to design a web scraping program to get the content from the following website 

https://webscraper.io/test-sites/e-commerce/allinone/computers/tablets


This is a website for testing web scraping, this given URL link to a computer eCommerce store selling different models of tablets.

The task is to collect information on all the tablets list on the webpage.

The information to be collected are product, description, price, and review for each of the tablets. You are supposed to program your code using the focus spider class( scrapy.Spider ) in python. The result of the scraped data must store in a JSON format file as listed below:
```
{"price": ["$603.99"], "description": ["Wi-Fi, 64GB, Silver"], "product": "Apple iPad Air", "review": "7 reviews"}
{"price": ["$172.99"], "description": ["Silver, 7" IPS, Quad-Core 1.2Ghz, 16GB, 3G, Android 4.2"], "product": "IdeaTab S5000", "review": "8 reviews"}
{"price": ["$148.99"], "description": ["Blue, 7" IPS, Quad-Core 1.3GHz, 8GB, 3G, Android 4.2"], "product": "IdeaTab A3500-H", "review": "9 reviews"}
{"price": ["$233.99"], "description": ["LTE (SM-T235), Quad-Core 1.2GHz, 8GB, Black"], "product": "Galaxy Tab 4", "review": "1 reviews"}
{"price": ["$399.99"], "description": ["10.1", 3G, Android 4.0, Garnet Red"], "product": "Galaxy Note", "review": "12 reviews"}
```
#### Create a python function to search for Android or Apple Tablet information.
Function name: searchbybrand( string)

Argument: string -> android or apple

Return result: list of all matched item( with product, description, price, reviews)

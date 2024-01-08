Scraping using BeautifulSoup

These files help in scraping product details from lenscart website. First file one only scrap limited amount of products because of infinite scrolling functionality of website.

You are required to find api gateway link to access data in page format
you can get the link by enabling logXMLhttpRequests in google chrome console and slowly scroll the website
But why do we need this?
It's beacause lenscart uses infinte scrolling functionality,
So data is generated through AJAX(api gateway) and you can't access it by simply looping through url page count value

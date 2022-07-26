# Webscrapping-with-BeautifulSoup
At this module we will learn on how do simple web scrapping using beautiful soup. Web scrapping is one of a method that we can use to colleting the data from internet. At this particular module, we will try to scrap and clean IMDB Top Rated 1000 Movies from ( https://www.imdb.com/search/title/?groups=top_1000&sort=user_rating,desc&count=100&start=1&ref_=adv_prv), it's one of the offical site to check top 1000 top IMDB rated movies. To do this we will only use a couple default library from python and BeautifulSoup.

## Dependencies
<pr>Actually to follow this module you only need to install beautifulsoup4 with pip install beautifulsoup4 and you are good to go. But here some libraries that needed to be installed first that I use at this module : <pr/>
- beautifulSoup4
- pandas
- requests
- As prerequisties a bit knowledge on html is required.
  
 ## What is BeautifulSoup

Beautiful Soup is a Python library for pulling data out of HTML and XML files. Beautiful Soup 3 only works on Python 2.x, but Beautiful Soup 4 also works on Python 3.x. Beautiful Soup 4 is faster, has more features, and works with third-party parsers
like lxml and html5lib.

Since beautifulsoup used to pull the data out of a HTML, so first we need to pull out the html first. How we do it? We will use default library `request`. 

So all this code is doing is sending a GET request to spesific address we give. This is the same type of request your browser sent to view this page, but the only difference is that Requests can't actually render the HTML, so instead you will just get the raw HTML and the other response information.

## Conclusion

In conclusion when you don't have a direct access to a data from a website you can always do the scrapping method.

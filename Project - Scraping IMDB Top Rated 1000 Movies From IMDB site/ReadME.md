In this project we would scrap all the top 1000 IMDB rated movies resides across multiple pages for the site (https://www.imdb.com/search/title/?groups=top_1000&sort=user_rating,desc&count=100&start=1&ref_=adv_prv).


## Dependencies
<pr>Actually to follow this module you only need to install beautifulsoup4 with pip install beautifulsoup4 and you are good to go. But here some libraries that needed to be installed first that I use at this module : <pr/>
- beautifulSoup4
- pandas
- requests
  
 ## What is BeautifulSoup

Beautiful Soup is a Python library for pulling data out of HTML and XML files. Beautiful Soup 3 only works on Python 2.x, but Beautiful Soup 4 also works on Python 3.x. Beautiful Soup 4 is faster, has more features, and works with third-party parsers
like lxml and html5lib.

Since beautifulsoup used to pull the data out of a HTML, so first we need to pull out the html first. How we do it? We will use default library `request`. 

So all this code is doing is sending a GET request to spesific address we give. This is the same type of request your browser sent to view this page, but the only difference is that Requests can't actually render the HTML, so instead you will just get the raw HTML and the other response information.

# Web-Scraping-Challange
Developed a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page.
- First, Completed initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.
- Second, scraped the NASA Mars News Site (https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest) and collect the latest News Title and Paragraph Text.
- Third, used splinter to navigate JPL Mars Space Images (https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars), ensured the image url to full size i.e .jpg format. 
- Next, scraped Mars weather twitter account (https://twitter.com/marswxreport?lang=en) for latest Mars weather tweet.
- Then, collected Mars facts from https://space-facts.com/mars/ using pandas and then converted into HTML string. 
- Finally, from USGS Astrogeology site (https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) to obtain high resolution images for each of Mar's hemispheres.

Used MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.

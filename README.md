# Mission_to_Mars

## Overview 
The purpose of this assignment is to scrape the data from several websites to create a webpage, which highlights data on the planet Mars. 

## Data Sources

* **https://redplanetscience.com
* **https://spaceimages-mars.com
* **https://galaxyfacts-mars.com
* **https://marshemisphere.com

* **Tools:** Pandas, Splinter, BeautifulSoup, Jupyter Notebook
* **Applications:** MongoDB, Flask
* **Languages:** Python, HTML, CSS

## Summary
In this project, there is an automated web browser that visits the NASA news website and the Mars Hemispheres website to scrape data for the Mission to Mars in index.html. It is stored in a NoSQL database in scraping.py, and then render the data in a web application created with Flask in app.py. 
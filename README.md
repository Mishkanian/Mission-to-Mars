# Mission to Mars Web App

## Project Overview
The purpose of this project is to build a Web App that will scrape several websites for the most recent Mars data. The extracted data is stored in a NoSQL database and then an HTML page is created to display the findings. 

## Software

- Python 3.7
- splinter 0.14.0
- webdriver-manager 3.3.0
- Flask 1.1.2
- Flask-PyMongo 2.3.0
- BeasutifulSoup (bs4) 0.0.1
- html5lib 1.1
- lxml 4.6.3

## Scraping Mars Data

Mars hemisphere images are scraped from [Astropedia](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars).

As seen in the screenshot below, the extracted data is successfully stored in MongoDB.  

![mongo_mars](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mongo_mars.png)

## Updating the Web App

Adding Bootstrap 3 compoents, such as the code below, allowed the four Mars hemisphere images to be displayed side-by-side on Desktop browsers, instead of a line.
```html
 <div class="col-md-3">
```
![web_hemi](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mars_hemi.png)

### Optimization for Mobile Devices

The Web App is also fully optimized for mobile devices:

![mobile_screen]()

![mobile_hemi]()

**Author: Michael Mishkanian**  

For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/michaelmishkanian/).

![mars_image](https://astropedia.astrogeology.usgs.gov/download/Mars/Viking/cerberus_enhanced.tif/full.jpg)

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

The final HTML page can be viewed by clicking [here]()

Selecting the "Scrape New Data" button will obtain the latest news, images, and facts about Mars. News titles and summaries are extracted from [NASA Mars Exploration Program News](https://data-class-mars.s3.amazonaws.com/Mars/index.html). The featured images are extracted from the [Jet Propulsion Laboratory's Space Images](https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html). Mars hemisphere images are extracted from [Astropedia](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars). Finally, the Mars facts are gathered from [Galaxy Facts](https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html).

After running [app.py](https://github.com/Mishkanian/Mission-to-Mars/blob/main/app.py), the extracted data is successfully stored in MongoDB as seen in the screenshot below.  

![mongo_mars](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mongo_mars.png)

## Updating the Web App

Adding Bootstrap 3 compoents, such as the code below, allowed the four Mars hemisphere images to be displayed side-by-side on Desktop browsers, instead of a line.
```html
 <div class="col-md-3">
```
![web_hemi](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mars_hemi.png)

### Optimization for Mobile Devices

The Web App is also fully optimized for mobile devices, including the layout of the [hemisphere images](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mobile_mars_hemi.png).

![mobile_screen](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mobile_mars.png)


**Author: Michael Mishkanian**  

For all questions and inquiries, please contact me on [LinkedIn](https://www.linkedin.com/in/michaelmishkanian/).

![mars_image](https://github.com/Mishkanian/Mission-to-Mars/blob/main/Resources/mars.jpeg)

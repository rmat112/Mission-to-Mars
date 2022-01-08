# Mission-to-Mars
## Overview
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images. This challenge includes the following:
- Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
- Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles
- Deliverable 3: Add Bootstrap 3 Components
#### Data Files: 
- [Mission_to_Mars_Challenge.ipynb](https://github.com/rmat112/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb)
- [Mission_to_Mars_Challenge.py](https://github.com/rmat112/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.py)
- [app.py](https://github.com/rmat112/Mission-to-Mars/blob/main/app.py)
- [scraping.py](https://github.com/rmat112/Mission-to-Mars/blob/main/scraping.py)
- [index.html](https://github.com/rmat112/Mission-to-Mars/blob/main/templates/index.html)
#### Tools:
- Jupyter Notebook
- VisualStudio Code 1.63.2
- MongoDB v5.0.4
- Flask 1.1.2
- Python 3.9.7
- Pandas
- Beautiful Soup
- Splinter

## 1. Scrape Full Resolution Mars Hemisphere Images and Titles
- Browser was used to visit the [Mars Hemispheres](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) website to view the hemisphere images.<br/>
- Code was written that retrieves the full-resolution image and title for each hemisphere image.<br/>
- The full-resolution images of the hemispheres were added to the dictionary.<br/>
- The titles for the hemisphere images were added to the dictionary.<br/>
- The list contains the dictionary of the full-resolution image URL string and title for each hemisphere image.<br/>
![Del1_1.png](https://github.com/rmat112/Mission-to-Mars/blob/main/Del1_1.png)


## 2. Update the Web App with Mars Hemisphere Images and Titles
- Exporting the jupyter ontebook created in (1.) above and saving it as .py file.<br/>
- Updating the scraping.py file to contain code that retrieves the full-resolution image URL and title for each hemisphere image.<br/>
- The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image.<br/>
- The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image<br/>
- After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images<br/>
##### Full-resolution images and the titles of the four hemisphere)
![D2_2.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D2_2.png)
![D2_3.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D2_3.png)


## 3. Add Bootstrap 3 Components
- The webpage is mobile-responsive<br/>
![D3_1.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D3_1.png)
- Two additional Bootstrap 3 components are used to style the webpage<br/>
  - Styling the "Scrape New Data" button.
  ![D3_2_1.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D3_2_1.png)
  - Customizing the facts table.
  ![D3_2_2.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D3_2_2.png)
  - Adding the hemisphere images as thumbnails (all in one row)
  ![D3_2_3.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D3_2_3.png)
  ![D3_2_3img.png](https://github.com/rmat112/Mission-to-Mars/blob/main/D3_2_3img.png)

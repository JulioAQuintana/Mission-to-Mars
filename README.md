# Mission to Mars

The purpose of this project is to develop a Flask web application using Python and Mongo DB and using scraping HTML tools for wiew desing

## Background
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

## Resources

**_list resources used_**

* **Data Source:** https://marshemispheres.com/
* **Software:** Jupyter Notebook 6.3.0, Flask 1.1.2, Splinter 1.26.4, MongoDB 4.4.6, Mongo DB

## Results

####  Deliverable 1
### **_Scrape High-Resolution Mars Hemisphere Images and Titles._**
I used BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images. through code in Mission_to_Mars_Challenge.ipynb I got the information for image and titles from hemispheres webpage:

   ![] (https://github.com/JulioAQuintana/Mission-to-Mars/blob/main/Resources/Hemispheresdata.png)


####  Deliverable 2
   * **_pdate the Web App with Mars’s Hemisphere Images and Titles._**
 I used Python to update your Mongo database, and modify your index.html file in this way the webpage contains all the information you collected in this module as well as the full-resolution image and title for each hemisphere image

   ![](https://github.com/JulioAQuintana/Mission-to-Mars/blob/main/Resources/Hemispheresimage.png)

####  Deliverable 3
   * **_Add Bootstrap 3 Components_**
For this part of the Challenge, I updated  the web app to make it mobile-responsive, and add two additional Bootstrap 3 components to make it stand out.

Please review the Mission_to_Mars_Challenge.ipynb and Mission_to_Mars_Challenge.py code to see details about this challenge. 

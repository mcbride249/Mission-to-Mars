**Mission-to-Mars**

**Project Overview**

Assist a junior data scientist named Robin, in achieving her dream of achieving a position at Nasa, by web scrape data specific data using Chrome Developer Tools (DevTools). A script was to be written that would gather all the information she searches for into one convenient location, and once gathered be able to be shared with others, with the intent of gaining interest and attention from Nasa. Specifically, this project is looking to gather information from the Mission to Mars from across the web and display the data in a central location, without having to spend time gathering the data manually.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Goals:**

1. Use Splinter to automate a browser.
2. Scrape the most recent Mars data.
3. Scrape the Mars data's featured image.
4. Scrpae Mars facts.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Summary**

1. The following code initialized Splinter to begin.

![Goal 1](https://user-images.githubusercontent.com/92111396/148693636-219403cf-6daa-421a-9ad1-1f716ab55005.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Goal%201.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. The following code was used to scrape the Mars data.

![Goal 2](https://user-images.githubusercontent.com/92111396/148693668-d5fdc969-568e-45b7-9d6b-eb3abf131148.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Goal%202.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3.The following code was used to scrape the Mars data's featured image.

![Goal 3](https://user-images.githubusercontent.com/92111396/148693726-b899ab60-86ff-4ea0-a8d5-e311ff104864.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Goal%203.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4.The follwoing code was used to scrape the Mars facts.

![Goal 4](https://user-images.githubusercontent.com/92111396/148693763-c58eb336-c317-4f4a-b758-0da0abbcc7d4.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Goal%204.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Resources**

-Data Source: Mission_To_Mars_Chall;enge.ipynb, app.py, scraping.py, index.html 

-Software: Python 3.7.10, Visual Studio Code, 1.38.1, MongoDBCompass

-Reference: getbootstrap.com, w3schools.com

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Module 10 - Challenge** 

All code for this challenge can be found in the Mission_To Mars_Challenge folder.

https://github.com/mcbride249/Mission-to-Mars/tree/main/Mission_To_Mars_Challenge

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Purpose**

The purpose of this challenge was to use BeautifulSoup and Splinter to scrape full resolution images of Mars's hemispheres and the titles of those images, store the scrapped data on a Mongo database, use the web application to display the data, and alter the design of the web app to accommodate these images and ensure that they are mobile device friendly. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 1**

The following code was used to retriuve the full resolution images and titles for each of Mars's hemispheres.

![Deliverable 1-1](https://user-images.githubusercontent.com/92111396/148694118-60cb1cb1-fa9c-4832-a128-506060e52987.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%201/Deliverable%201-1.PNG


The below block of codes dfisplayes the full resolution URLs and the image titles, confirming (once entered into a broweser) that the code in Step 3 was successful.

![Deliverable 1-2](https://user-images.githubusercontent.com/92111396/148694158-131c0925-ef38-483a-bf27-2f5bcef09ef4.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%201/Deliverable%201-2.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 2**

To complete Deliverable 2, a new scraping dictionary labelled "hemispheres" was created within the data dictionary in the scrape all function with the scraping.py file.   

![Deliverable 2-1](https://user-images.githubusercontent.com/92111396/148694488-ed486867-3243-40ee-8e4b-c4237adaeba7.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%202/Deliverable%202-1.PNG


The following block of code was then added to scrape the data from multiple webpages and add it to our own.

![Deliverable 2-2](https://user-images.githubusercontent.com/92111396/148694636-e50f1317-4195-43dd-9ad7-c8d36cf8ad9e.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%202/Deliverable%202-2.PNG


The final webpage produced via scraping, that cointained the data scraped from multiple web sources can be seen below.

![Deliverable 2-3](https://user-images.githubusercontent.com/92111396/148694752-2e86c2a3-1876-4c3a-8525-b578eb14bc0b.PNG)

https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%202/Deliverable%202-3.PNG

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Deliverable 3**

1. To make the web page mobile responsive the code: <meta name="viewport" content="width=device-width, initial-scale=1"> was added to the index.html file. 

2. A number of Bootstrap 3 componeents were used to style the page: 

    1. <div class="col-md-3"> was changed from <div class="col-md-6"> to accomodate the images to fit on a single row.
  
    2. The background colour of the page and text were changed to blue and red respectively, vis the following block of code: <body style="background-color:blue; color:red">. 
  
    3. The background colour of the header was changed to black using the following code: <div class="jumbotron text-center", style = "background-color:black".


The mobile version of the web page can be seen below.
                                                                                               
![Deliverable 3-1](https://user-images.githubusercontent.com/92111396/148695735-412a3282-4a67-4b69-8f92-7979793a37e9.PNG)
                                                                                          
https://github.com/mcbride249/Mission-to-Mars/blob/main/Mission_To_Mars_Challenge/Resources/Images/Deliverable%203/Deliverable%203-1.PNG



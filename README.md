# Webscrap_BSoup_NewsWebPage

A simple webscrap using BeautifulSoup of an Anime Webpage

This BSoup webscrap and webcrawl counts with functions that extract images, texts and titles of different urls' from the web page.
The webpage is : "https://www.anmosugoi.com/" that counts with several URL's containing many news each one.

First step is to extract the sections URL's from the main page, then for each section we get the images, titles, and URL's for each new that appears in each section.
Finally we extract the texts from each new and save it in a Dict. Each new belongs to a different subkey named after the new's title and are grouped in another key named after the section.

We also created a function that displays the images with the title and the new's URL.

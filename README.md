# Webscrap_BSoup_NewsWebPage
###### EN
A simple webscrap using BeautifulSoup of a POP Culture Webpage

This BSoup webscrap and webcrawl counts with functions that extract images, texts and titles of different urls' from the web page.
The webpage is : "https://www.anmosugoi.com/" that counts with several URL's containing many news each one.

First step is to extract the sections URL's from the main page, then for each section we get the images, titles, and URL's for each new that appears in each section.
Finally we extract the texts from each new and save it in a Dict. Each new belongs to a different subkey named after the new's title and are grouped in another key named after the section.

We also created a function that displays the images with the title and the new's URL.

###### ES
Un scrapeo simple usando BeautifulSoup de una pagina de noticias de cultura pop

Este webcrawl y webscrapp cuenta con funciones que extraen imagenes, textos y titulos de diferentes segmentos de URLS de la pagina.
La pag es : "https://www.anmosugoi.com/" que cuenta con varias URLS y estas con varias noticias.

Primer paso es extraer las URL's de cada seccion de su pagina principal, luego para cada seccion se cogen las imagenes, titulos, y URLs de cada noticia que aparezca.
Finalmente extraemos los textos de cada una y guardamos en un DICT (cabe resaltar que se peude guardar en un DF si se desea). Cada nota pertenece a una subkey differente nombrada con el titulo de la nota y agrupada en otra key llamada por su seccion.

Tambien se crea una funsion que presenta las imagenes con su titulo y URl de la nota.

# IMPORTANT:
THE FILE "Beautiful Soup simple scrapping" IS THE FILE THAT CONTAINS ALL THE STEPS i'VE DONE WHILE MAKING THE PROJECT
THE FILE "Beautiful Soup simple scrapping for Github" IS THE FILE THAT CONTAINS THE CLEANED CODE

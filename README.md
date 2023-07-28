# W_Scrapping_Meteorologia
Este proyecto se generó a partir de mi servicio social en el IAM. Se trata de una aplicación de Web Scrapping, en la cual se automatiza la obtención de datos metereológicos diarios con distintas estaciones de 3 páginas (AmbientWeather, WeatherLink y WunderGround) utilizando python con las librerías Beautiful soup y Selenium.
Cada una de las páginas tiene su forma particular de entregar la información, en el proyecto solo se enfoca el valor de la humedad y la precipitación (así se pidió), para el caso de Wunder Ground, debido a que hay una base de datos guardada para cada día, tiene la función de escoger un mes en particular y para todas las estaciones que se le entreguen, genere una base de datos con la información.
Los links de las páginas son:

-https://www.wunderground.com/
-https://www.weatherlink.com/
-https://ambientweather.net/


#Datos pluviales de protección civil
Para este otro mini proyecto, se toma de una página web con un mapa y puntos distribuidos por jalisco con información de la precipitación pluvial, a través de Selenium se genera un script que intenta tomar la mayor información posible de estas estaciones junto con su ubicación y otros datos.
El código se llama *PCYB_Puntos*
El link de la página es:

-https://uepcbj.com/uepcb_clp/map_visitors.php


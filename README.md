# Capstone Project

This repository is for the *Applied Data Science Capstone Project* course in the *IBM Data Scientist Professional Certificate*.


## Background

Mexico City is the capital and largest city of Mexico, where over **9.2** million people live and has a population density of **6,163.3** per square kilometer.[1] The metropolitan area of Great Mexico City has a population of **21.3** million, making it the second largest metropolitan area in America, only behind Sao Paulo, Brazil.
The city is divided in **15** subdivisions (or boroughs), and there are around **15,000** restaurants.[2] Another fact is that the life expectancy of a restaurant in Mexico City is of 6.9 years, not as many as in other Mexican cities. 

According to INEGI, Mexico City has a large amount of restaurants per thousand people in comparison to the national average. The subdivision of Benito Juarez has 8 restaurants per thousand people, whereas the national average is of 3 restaurantes per thousand people.[3] There is a high competition but also a large market, hence one of the first decisions that restaurant owners need to make when establishing a new restaurant is **where** to open it.

## Problem

In this project, we will be thinking as a potential restaurant owner. We want to investigate and determine which would be the best category for our new restaurant, and where to open it based on factors such as low competition, low real state costs, and population density. There are several more factors that have an impact when making this decisition, but for the purpose of the scope of this project we will only focus on the already mentioned.


## Data

- [Foursquare API](https://developer.foursquare.com/) Data that contains information of the most common venues in each neighbourhood in Mexico City.
- There isn't a public dataset that concentrates the rental average price per meter square per borough in Mexico City. So I set-up my own dataset based on the rental prices of comercial locals advertised in [Inmuebles24](https://www.inmuebles24.com/). The only borough that did not have enough data to be included in this data set was borough Milpa Alta. You can find my data as a CSV file [here](https://github.com/alanpar97/Capstone_Project/blob/master/Data/borough_avg_price.csv).
- We will also use INEGI 2015 Population Data to get the population in each borough. Unfortunately, there is not a more updated dataset yet.
- [Mexican Postal Codes - Mexican Postal Service](https://www.correosdemexico.gob.mx/SSLServicios/ConsultaCP/CodigoPostal_Exportar.aspx) Data that contains the postal codes of each neighbourhood in Mexico City. We will get this data as an XML file provided by the Mexican Postal Service's website.


### References
- [1] [INEGI - Population per Federal Entity](https://www.inegi.org.mx/app/tabulados/interactivos/?pxq=Poblacion_Poblacion_01_e60cd8cf-927f-4b94-823e-972457a12d4b)
- [2] [Mexico City - Wikipedia](https://en.wikipedia.org/wiki/Mexico_City#cite_note-18)
- [3] [CANIRAC - INEGI (PDF)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiplbqTlJXvAhWlp1kKHQ7QAUYQFjABegQIBRAD&url=http%3A%2F%2Fcanirac.org.mx%2Fimages%2Fen_su_punto%2Ffiles%2Finegi.pdf&usg=AOvVaw3sFn8woiT6IBoYRCLmIJhe)

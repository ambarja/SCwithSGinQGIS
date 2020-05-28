# Supervised Classification and Statistical Graphs in QGIS 

This repository has how goals encourage to new users to use QGIS in thematic how Remote Sensing using the Dzetsaka plugin
how also the elaborate of beautiful statistical graphs using the DataPlotly plugin of a form easy and fast.

**QGIS**: Is a software of System Information Geographical free and of open source that it allows analyse,processing and visualisation spatial data .

**Dzetsaka**: Is a special plugin that allows classification different satellite image in QGIS using algorithms of Machine learning How Random Forest. 

**DataPlotly**: Is a library of Python that allows to make different types of graphs inside QGIS of form easy and fast.

## Installation of DataPlotly
 
![](https://github.com/barja8/Friends/blob/master/QGIS/Img/DataPlotly.png?raw=true)

## Installation of Dzetsaka

Before of to install Dzetsaka Plugin, first you should install a library python how is scikit-learn for to access some algorithms of Machine Learning how Random Forest.

In GNU/Linux just open console and put the next:

```
python3 -m pip install scikit-learn -U --user
```
and Windows open OsGeo Shell and put the next:

```
py3_env.bat

python3 -m pip install scikit-learn -U --user
```
and finally inside of QGIS install Dzetsaka Plugin

![](https://github.com/barja8/Friends/blob/master/QGIS/Img/dzetsaka.png?raw=true) 


## Classification of a sentinel2A image in QGIS using Random Forest

![](https://github.com/barja8/Friends/blob/master/QGIS/Img/dzetsaka01.png?raw=true)
![](https://github.com/barja8/Friends/blob/master/QGIS/Img/dzetsaka03.png?raw=true)
![](https://github.com/barja8/Friends/blob/master/QGIS/Img/dzetsaka05.png?raw=true)

## Plots with DataPlotly according to the class types

```
CASE
 WHEN "Descrip" IS 'Bare ground' THEN color_rgb(255, 250, 95)
 WHEN "Descrip" IS 'Bofedales'   THEN color_rgb(121, 219, 23)
 WHEN "Descrip" IS 'Glacier'     THEN color_rgb(255, 255, 255)
 WHEN "Descrip" IS 'Lagoon'      THEN color_rgb(0, 0, 255)
END
```


## Exporting in PNG the final temathics maps 




## Clone with git this Reproducible Project

If you use git, just put the next sentences in console: 

```
git clone https://github.com/barja8/DataPloltyinQGIS
```
Also you can clone this reproducible project of the next manern: 


## Acknowledgements:
* DataPlotly: <>
* Dzetsaka: <>

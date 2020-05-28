# Supervised Classification and Statistical Graphs in QGIS 

![GitHub stars](https://img.shields.io/github/stars/qgis/QGIS?color=blue&label=qgis%3A%3Astarts&logo=qgis&logoColor=green)
[![GitHub commit](https://img.shields.io/github/last-commit/pcm-dpc/COVID-19)](https://github.com/barja8/IntroSQL/commits/master)
[![GitHub license](https://img.shields.io/badge/License-Creative%20Commons%20Attribution%204.0%20International-blue)](https://creativecommons.org/licenses/)


This repository aims teach and to encourage new users to use QGIS on the topic of Remote Sensing using the Dzetsaka plugin,
as well as the elaboration of beautiful statistical graphs using the DataPlotly plugin in an easy and fast way.

**QGIS**: Is a software of System Information Geographical free and of open source that it allows analyse,processing and visualisation spatial data .

**Dzetsaka**: Is a special plugin that allows classification different satellite image in QGIS using algorithms of Machine learning How Random Forest and Supor Vecto Machine.

**DataPlotly**: Is a library of Python that allows to make different types of graphs inside QGIS in an easy and fast way .

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


## Classification of a sentinel2A image using Random Forest


## Plots with DataPlotly according to the class types


```sql
CASE
 WHEN "Descrip" IS 'Bare ground' THEN color_rgb(255, 250, 95)
 WHEN "Descrip" IS 'Bofedales'   THEN color_rgb(121, 219, 23)
 WHEN "Descrip" IS 'Glacier'     THEN color_rgb(255, 255, 255)
 WHEN "Descrip" IS 'Lagoon'      THEN color_rgb(0, 0, 255)
END
```
![](https://github.com/barja8/Friends/blob/master/QGIS/Img/q11.png?raw=true)

![](https://github.com/barja8/Friends/blob/master/QGIS/Img/q12.png?raw=true)

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

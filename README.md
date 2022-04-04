# Analyse and forescast bread price in France
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/) [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Table of Contents
1. [General Info](#general-info)
2. [Graphics](#result)

## General Info
This project consist to analyse and predict the future price of the bread in France.
For my prediction I use [Prophet](https://github.com/facebook/prophet) released by Facebook's Core Data Science team.

## Result
This firt graph show the evolution of the bread

<img src="res/price_evolution_by_year.png" width="500" height="300" />

The second graph show the actual and predicted value

<img src="res/forescast_graph.png" width="500" height="300" />

The third graph show the components extract (trend)

<img src="res/forescast_graph_components.png" width="500" height="300" />

This table shows 3 the forescast by table

 Year | Forescast | Lower forescast | Upper forescast |
 --- | --- | --- |--- |
2022-09-27 | 3.604286 | 3.582768 | 3.625472 |
2022-09-28 | 3.602145 | 3.581696 | 3.623564 |
2022-09-29 | 3.599355 | 3.578212 | 3.619997 |

<b> Interpretation line 1 : On September 27, 2022 the price of bread will be 3.60 € in France </b>

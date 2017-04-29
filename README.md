# BiciMAD Data Analysis

Madrid's public bike system data analysis.

Copyright © 2017 Javi Ramírez <javi.rmrz@gmail.com> | [@rameerez [tw]](http://twitter.com/rameerez) | [GitHub](http://github.com/rameerez)

This code is Open Source, released under the MIT License.

_Made with ♥ from Madrid_

## Introduction

BiciMad is the public bike system in Madrid, Spain. I'm a big fan of commuting by bike in Madrid (even though car drivers are still complete assholes to bike drivers, and the city is not fully conditioned to bike traffic).

I tend to use my own bike, but still I find myself more than often riding BiciMad bikes (it's pretty convenient: they have an electric motor that assists in pedaling, and you can just take and drop them in the nearest station without having to worry about getting your own bike stolen). Still, every time I've used them, I've detected a number of issues (broken bikes, out-of-order plugs, empty and completely full stations...)

In April 2017 I contacted EMT Madrid (the public company that now runs BiciMad) and asked their OpenData department for BiciMad data to analyze. They inmediatly answered and provided me with a huge dataset and helpful documentation. I want to thank EMT's OpenData for their kindness and contribution.

My goal with this data analysis is to discover hidden patterns that can reveal underlying problems, to provide BiciMad with powerful data-based suggestions that can help improve the service for all us Madrid citizens.

Data source: [EMT OpenData](http://opendata.emtmadrid.es)

## Installation

Using Python 3.5.3.

Please make sure you have the following libraries installed: `ipython`, `jupyter`, `pandas`, `numpy` and `bokeh`.

If not, install them with either anaconda or pip:

`pip install -U ipython jupyter pandas numpy bokeh`

`conda install ipython jupyter pandas numpy bokeh`


Then just launch the Jupyter notebook with:

`ipython notebook`


## Instructions

Uncompress the `.rar` file under `/data` and place the two `.json` files in `/data`.

If you would like to use any other BiciMAD dataset, there is a global variable in each notebook to configure the datasets to be loaded.

Markdown tables for describing the datasets within the notebooks were created using [TablesGenerator](http://www.tablesgenerator.com/markdown_tables/load). They allow you to save/load tables in `tgn` format, those reside in the /doc folder.
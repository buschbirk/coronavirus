
# Visualizing the Coronavirus pandemic using Flourish

This repository contains the data and preprocessing used for visualizing the Coronavirus pandemic using [Flourish](https://flourish.studio/).  

A collection of visualizations is available as a Flourish Story [**here**](https://public.flourish.studio/story/236518/)  

These visualizations were created for a data visualization course on the Data Science (BSc) programme at the IT University of Copenhagen. 

## Data

The source data is stored in a [Google Sheet](https://docs.google.com/spreadsheets/d/1gsH9xF4HcESKs35QPNvKPDSJtYdSuzEo2JNXkr5ccY8/edit?usp=sharing)
 updating daily from a GitHub repository maintained by the by the Johns Hopkins University Center for Systems Science and Engineering.  

Simple data processing such as pivot tables aggregating data on a country-level is done in an Excel workbook available in `CoronavirusTrendsMaster.xlsx`.  
For now, data is updated manually in the Excel workbook.  

Finally, additional data preprocessing is performed using the Python script `corona_data.py`.  
The Python script outputs a series of CSV files used for Rosling charts as well as visualizations of daily trends following a certain threshold, e.g. infection growth following the 50th confirmed infection.

For future work, the entire data pipeline both should and could be automated. 

## Examples
Bar chart animating daily number of confirmed infections:  
![infection race chart](https://i.gyazo.com/5eef2ea6633776394330d8055efeaeb7.gif)


Line chart race animating the infection counts following the 50th confirmed infection: 
![infection line chart race](https://i.gyazo.com/b9cd1f3f1c4918612d20ac60c1d749ef.gif)

Rosling chart showing infection growth relative to total number of confirmed infections:  
![infections rosling chart](https://i.gyazo.com/08fadccbca9f060d9c2d380b7ff418de.gif)

## References
Johns Hopkins CSSE: https://github.com/CSSEGISandData/COVID-19]  
Flourish Studio: https://flourish.studio/



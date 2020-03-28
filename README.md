# COVID-19 JHU Power BI Report - DMiradakis

| :calendar: Last Updated | :pencil2: Author(s) | :clock3: Reading Time | Tags |
| :---: | :---: | :---: | :---: |
| 2020-03-28 | Daniel Miradakis | 2 minutes | <img src="https://img.shields.io/badge/Datasource-JHU%20COVID--19%20GitHub%20Repository-blue"> <img src="https://img.shields.io/badge/Pandemic-COVID--19-red"> |

## Link To The Report

[Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiM2ZlMGE1YTMtNDI3ZC00MjU4LWFhMjktNDI0ZWZiNzM2YWRkIiwidCI6ImRmMjNiYWY0LTY1MTYtNDMwMy04MjhmLWZmNzhiNGFhNDEyOCIsImMiOjJ9)

## Introduction

As stated on the metadata tab of my Power BI Report, my name is Daniel Miradakis.  I currently work as an IT Business Intelligence Analyst in the metal fabrication industry in the United States.

This is my own attempt to visualize the data that is being graciously provided by the [JHU team on their GitHub repository](https://github.com/CSSEGISandData/COVID-19).

If you have any issues, requests, questions, or anything else relating to the Power BI Report I created, please open up an issue here so I can track it!

## Bookmark Icons

I heavily utilize the organizational power of bookmarks in Power BI. Thus, when you navigate back and forth between the various tabs of the report, you will not see any slicers.

Additionally, because the window for publishing a Power BI Report to the web does not support visualizing the data behind a visual in tabular form, I also have a bookmark for each page containing either table data or pivot table data for the associated visuals.

To navigate to these data tables, the slicers, or back to the main visuals, make sure to click the black icons located in the upper right-hand corner of each tab of the report.

An example of them is below:

![](Images/Bookmark%20Icons.png)

## Trends

I am aware that some of the trends on the report do not fit the data. Unfortunately, Power BI only has linear regression lines available when plotting datapoints. There may be other visuals to explore, or perhaps I will create my own formulas inside Power BI for other types of regression.

## Python and Machine Learning

If any of you have Python visualizations you have created from the matplotlib library or others in Python, please open up an issue, and perhaps I can add it to the report!

If you personally have any machine learning resources available for the COVID-19 data, or if you know where to find some besides Kaggle, please let me know! I would be *very* interested in exploring this!

## Data Colours

The data colours were selected with the help of GitHub's own [Primer Colour Guide](https://primer.style/css/support/color-system) (I find this guide *exceptionally* helpful for development of all kinds). 

The hexadecimal colour values are listed below:
- Confirmed: 
> ![](Images/Blue%20005cc5.png)
- Deaths:
> ![](Images/Red%20d73a49.png)
- Recovered:
> ![](Images/Green%2028a745.png)
- Active:
> ![](Images/Yellow%20f9c513.png)
- Others:
    - Gray:
    > ![](Images/Gray%206a737d.png)
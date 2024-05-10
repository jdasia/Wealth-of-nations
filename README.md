# Wealth-of-nations

<h2>Introduction</h2>
In this report, I take a look at three different variables relevant to nations and their citizens namely, GDP per capita, life expectancy and number of smartphone users. 

<h2> Scenario</h2>
Data visualisation has become an essential business capability to help transform information into insights that can drive meaningful business outcomes and improved experiences. Today, most organisations have accumulated a wealth of data from the different corners of their businesses they are then unable to see how this data can help them make better decisions and review results.
I have been asked to look at the data workbook and get familiar with it to make to create this visual report that will show the data in the form of visualisations and maps using Tableau to the client’s requirements. I will also consider the data protection and computer misuse policies. 
<br>

As part of the data protection act, all collected data must adhere to a strict protocol surrounding usage purposes, fairness and transparency. 

<h2> Data Sourcing</h2>
The data for this analysis was provided through an Excel file containing three tables with the variables, GDP per capita, Life expectancy at birth and smartphone users as columns next to the unique identifier, 'country.' The datasets were not created for the same range of nations therefore, there are more than two hundred nations for GDP, less than a hundred for Life Expectancy and almost two hundred nations recorded for their number of smartphone users. 

<h2> Data Transformation</h2>
This data was already mostly in the right format. With the data validation ribbon in Excel, I checked each table for duplicates as well.
<br>
<br>

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/jdasia/Wealth-of-nations/blob/main/assets/Top20GDP_filtered.png", align="center", style="display: block; amrgin: 0 auto;" >
</div>

I filtered the GDP per capita table using a pivot table to get all records for the year, 2019 and also for the top 20. After this I was ready to create some visualisations to investigate any possible relations between GDP per capita and the rest of the data.

<h2> Analysis and Visualisation</h2>
In Tableau I linked all three tables together based on the respective field names for nation(s).
Analysis required an assessment of the relationships between GDP per capita and the other two variables to find out if there were any clear relationships between them. This formed the most insightful part of the analysis after investigating GDP by filtering for the top 20 nations. 

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/jdasia/Wealth-of-nations/blob/main/assets/top20GDP_bars.png", align="center", style="display: block; amrgin: 0 auto;" >
</div>
<br>


In the bar chart above, it is easy to make observations on the top twenty nations sorted in descending order. Monaco is first with the greatest GDP per capita. At the other end is Denmark at postition 20 in the sort. 
<br>
<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/jdasia/Wealth-of-nations/blob/main/assets/GDP_LifeX.png", align="center", style="display: block; amrgin: 0 auto;" >
</div>

<h4> Comparing levels of GDP by life expectancy</h4>
<br>
With an idea of the top nations competing for GDP per capita, I sought to investigate the relationship between GDP per capita and life expectancy. To assess these properties, it may be good to use a logarithmic scale for GDP and keep life expectancy the same. This changed the shape of the data to allow for easy identification of any trends or outliers. 
<br>
<br>
On making any selection of the square plots, the key variables being examined can be seen in the tooltip as shown in the image. 'Rwanda' is seen to have a GDP per capita value of '2227' and a life expectancty of about sixty-nine. At the edge of it's GDP per capits level on the chart, it can de deduced that the selected nation is in the upper percentile of life expectancy for nations around the same level of GDP. 
<br>
<br>
A more obvious trend is the increase in life expectancy as GDP per capita appreciates. At the top of this chart is 'Liechtenstein', the highest GDP per capita in the bar chart exempting 'Monaco'. Closer to the end of the the x-axis with a value of about '80.70', it can be deduced that life expectancy increases with GDP. 
Just below, 'Liechstenstein', 'Luxemborg' is plotted further to the right of the x-axis with a greater life expectancy, hovering at the top of the GDP axis. Singapore to the right of 'Luxemborg' has a greater life expectancy although its GDP falters a bit at 97341 GDP per capita. 'Singapore' is in the upper percentile both in the overall chart and at its GDP range. 

<br>
<h4> GDP per capita by count of smartphone users</h4>
<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
<img src="https://github.com/jdasia/Wealth-of-nations/blob/main/assets/GDP_Smartphones.png", align="center", style="display: block; amrgin: 0 auto;" >
</div>































# SAL384_Final_Project
 
`SAL Final Project Data Scrape.ipynb`

This code will allow one to scrape the "team batting" table on baseball reference. 

Reformatting and reclassification of column data types is done for easier analysis. PItchers and additional column headers scraped from baseball-reference are deleted. This leaves 695 players should remain once these rows are removed.

Percentiles are calculated to allow for easier comparision. This is how the data was collected for the dashboard that we created.

`SAL Final Project Dashboard.ipynb`

Using the data gathered from the data scrape notebook, we create a dash application. This application has three forms of comparision. First is a radar plot comparing the selected player's hitting metrics to league average using percentiles. Next is a pie chart of the selected player's hit types. Lastly is a scatter plot with the x axis showing slugging percentage and y axis showing runs. The selected player is highlighted in this graph.

`http://bwachtel01.pythonanywhere.com/` 

The link above is a python anywhere website of the application. Be patient when entering players because the site can be quite slow. Note: this link will not work after August 17, 2021.

All data is scraped from Baseball-Reference.com. The specific data used can be found in the team Standard Batting tables on Baseball-Reference.com and should be formatted accordingly.  



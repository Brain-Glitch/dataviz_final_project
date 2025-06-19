# Data Visualization 

> Firstname Lastname. 

## Mini-Project 2

The trend I found interesting enough to show was how the day of the week correlated to birth rate. Unfortunately, since this data did not have a geographic element or benefit significantly from annotations when graphed, I tacked on a visualization of the various countries Boston Marathon runners come from to fulfill the assignment requirements.

The data preprocessing for Boston Marathon Runners started with renaming the "Country" column to reflect the country codes in my shapes data set. Then, I appended both together to create a chart table of countries and the number of people from there who participated in the 2017 Boston Marathon. The trick was that a gradient scale got thrown off by Canada and America having 4 and 50 times the representation of the third most represented nation, respectively. To solve for this, I split my dataset in two, allowing me to show the relation between smaller countries easier while using a unique color for countries far above the norm.

The data preprocessing for birth rate correlations involved creating mean data sets for both "births per week" and "births on a certain day of the month" (a control variable). Then, merge those datasets with the births each day using join to iterate the patterns across all 17 years. This data was used to create the dynamic line chart, while a copy of it was turned into a correlation matrix for the visualization component.

In terms of story, the Boston Marathon map paints an interesting picture about American cultural centrism, especially among developed nations. The fact that a national competition had participation from every continent and significant participation from countries like China and Australia illustrates how visible American events are on the international stage. The birth rate line chart and associated correlation matrix show that people don't like having children on weekends, but do not care what time of the month a child's birthday lands on. It does so in two distinct ways, and comparing those methods allows us to visualize what correlation truly means.

It is possible to segment the birth rate data along other axes, and the Boston marathon data by American state, though neither is necessary to tell a story with the data. It would also invite more issues than I already dealt with. IN one case, the line chart refuse to acknowledge "day of the week." In another, the map took several minutes of minor tweaks to it's color to even look halfway presentable.

However, on the whole, it was easy enough to apply broad design principles to the assignment. Cutting down on axis labels and grid lines when possible, using titles instead of axis labels, and using colors that roughly translate the emotion of the data (red for poor relationships, green for large numbers, etc). Though I would have liked to cut down on some of the white space, and the fonts do feel somewhat generic, the data comes across as intended, so I feel good about my work.
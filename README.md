![Journalism banner](https://www.york.ac.uk/media/studenthome/workandvolunteering/images/720px/jobsectorimages/JournalismPublishing.jpg)
# D3-Challenge
## Data Journalism and D3
### Background
It was the first day of my job as _data visualization_ expert at a major newspaper. During the morning meeting everyone gathered together to choose the stories of the day. Our editor decided to run a series of feature stories about the **health risks** facing particular demographics. She's looked at me and said "_Welcome to the newsroom_, why don't you take the first stab at this. We need to sniff out the story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System. We have a dataset in mind - it is based on 2014 ACS 1-year estimates: https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml, which incldes data on _rates of income, obesity, poverty, MOE(margin of error) etc._ by state. What do you think ?" I beamed and said _"Let me make an amazing visualization from the data that would impress everyone in this room"_. And thus, I picked up my **_first visualization project.._**
### D3 Dabbler
The core visualization is a scatter plot  between two of the data variables such as **`Healthcare vs. Poverty`**. It would include
* State abbreviations in the circles.
* Responsive plot window
* Axes and labels to the left and bottom of the chart.
### Impress the Boss features
Why make a static graphic when D3 lets you interact with your data?
* Placed additional labels(three for each axis) in my scatter plot and give them click events so that your users can decide which data to display. 
* Animate the transitions for your circles' locations as well as the range of your axes. 
* Circles change color during animation
* d3-tip that is triggered by mouseover each circle, reveals a specific element's data

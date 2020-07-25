## Data Journalism and D3
Interactive chart using JavaScript, D3.js to visualize health risks facing particular demographics.

### Webpage Link: 
https://aastha-arora.github.io/D3-challenge/

### Dataset
Datset used for the visualizations is based on 2014 ACS 1-year estimates: [Government Census Data](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml)
Dataset incldes data on rates of income, obesity, poverty, etc. by state.

### Visualization
Animated Scatter Plot

* The scatter plot can be filtered by selected the x-axis and y-axis labels using a mouse click event.
x-axis contains the scale for three demographics (Poverty, Age and Household income) and
the y-axis contains three health risk factors (Obesity, Smoking and lacking healthcare).
The scatter plot is rendered for the selected labels (highlighed in black). Inactive labels willl be displayed in grey color.

* Each state is represented by a circle in the scatter plot. State abbreviations are marked inside the circle.

* The chart has animated transitions for circle locations and range of axes.

* d3-tooltip has been incorated to display the label values for the axes on mouse hover.


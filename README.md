# belly-button-challenge

The challenge takes a dataset on samples from belly buttons to create and deploy an interactive website with three distinct visualizations. 
Static websites are effective in disseminating information, but dynamic websites open a level of interactivity for the flowing human mind. 
Using JavaScript and the d3 and Plotly libraries, users can swap test subjects and display the corresponding data.
In this repository, there is a static folder containing two JavaScript files as well as a HTML file in the root directory. 
The repository also contains the dataset as a json file. The app.js makes a d3 call to retrieve the dataset and creates two graphs with Plotly: a bar graph and a bubble chart of the samples in the test subject's navel. 
It also fills out a dropdown menu of all the test subjects and populates a panel with the currently displayed test subject. Upon changing the dropdown, the browser updates the panel information and visualizations.
The bonus.js mirrors much of app.js but includes additional code for a gauge meter for wash frequency. 
The script contains two different approaches to the gauge meter. The first adapts and uses Plotly's gauge chart. 
The second uses Plotly's pie chart, which is currently commented out. Both seem to work fine; the tricky part was using some light trigonometry to create the needle to point at the appropriate scrubbing value. 
The bonus.js defaults to the gauge chart instead of the pie chart to avoid layout issues.


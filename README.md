# belly-button-challenge

file:///C:/Users/Admin/Downloads/Starter_Code%20(15)/StarterCode/index.html

In this assignment, we build an interactive dashboard to explore the Belly Button Biodiversity dataset., which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Dashboard Features

Drop Down Menu

Select the Test Subject ID No. with the drop down menu to toggle the visualizations (bar, gauge, bubble charts)
![228077197-744a8e6c-6668-41e4-8b73-c25325e0a38d](https://github.com/sughra-bit/belly-button-challenge/assets/135158002/ffa758dd-c1f0-4937-8588-7a45d58d2be2)


Demographic Info Panel

This Panel shows the demographics information of the chosen test subject
Displays each key-value pair from the metadata JSON object


Horizontal Bar Graph

A bar chart is generated when a test subject is selected on the drop menu
The top 10 OTUs found in that test subject will be displayed in bars, where the sample_values are presented as the values for the bar chart and the otu_ids presented as the labels for the bar chart
When a user hover over a bar, the otu_labels are presented as the hovertext for the chart

![bar](https://github.com/sughra-bit/belly-button-challenge/assets/135158002/813c2969-8567-45d1-9ae0-32ffc3fb545b)

Gauge Chart

A gauge chart is generated when a test subject is selected on the drop menu
The value of srubs per week (wfreq) is display on chart with a blue colored bar

![newplot (3)](https://github.com/sughra-bit/belly-button-challenge/assets/135158002/296149b2-dff0-4049-9c52-48aa6d4f112f)

Bubble Chart
A bubble chart is generated when a test subject is selected on the drop menu
Each sample will be display as a bubble, where the larger the sample value is the larger the bubble size
On the chart, the x values are the otu_ids, the y values are the sample_values
The colors of the bubbles are based on otu_ids, and the hovertext are the otu_labels

![bubble](https://github.com/sughra-bit/belly-button-challenge/assets/135158002/24a6598f-ecb3-43b8-9def-88b48d5d3079)


Credits
Plotly
D3 Library
North Carolina State University - The Public Science Lab


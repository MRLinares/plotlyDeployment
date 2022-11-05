# Belly Button Diversity

## Overview

Create an interactive webpage displaying Bacteria data from Belly Button swabs.  

> ***Resources***\
> Data: samples.json\
> Software: HTML/CSS, JavaScript, VS Code, Bootstrap, D3.js, JSON, GitHubPages\
> Website image from [atcc.org](https://www.atcc.org/resources/culture-guides/bacteriology-culture-guide)

## Results

Using data extracted from a JSON file using d3, I created an interactive webpage where a user can select a subject id 
and three charts will populate alongside a demographics panel.

The first is a bar chart depicting the top ten bacterias present on a subject's belly button 
in descending order.

Next is a guage meter depicting the reported times per week the subject washed their belly button.

The bottom chart is a bubble chart 
representing the following information:
* The otu_ids as the x-axis values.
* The sample_values as the y-axis values and marker size.
* The otu_ids as the marker colors using the Viridis color gradient.
* The otu_labels as the hover-text values.

Finally, if the user gets lost viewing and interacting with the subject ids and bubble chart, 
a home button at the top left corner resets the page to its default settings at subject 940.

The website can be viewed and navigated through Github Pages at this [link](https://mrlinares.github.io/plotlyDeployment/index.html).

# Plotly_Deployment
Use Plotly.js (*JavaScript data visualization library*) to create an interactive data visualization for the web 

## Overview of Project

Roza wants to keep in mind how to best convey data to her volunteers and other researchers. For volunteers who are interested in selling their bacteria to Improbable Beef, we had to think about the best way to visualize the types of bacteria that colonize their bellies. Some of them will be suitable for synthetic beef production, while others will not. We used D3.json() to fetch external data (belly bullton data). We couldn't simply read in an external JSON dataset into our JavaScript file, so we had to run a local server. Out of the entire belly button dataset, in order to visualizae the data effecrively, we used *JavaScript* to manipulate--*filter*, *sort*, *map*-- the datasets (only show selected data pertaining to selected individual). With *Plotly*, we are able to create various types of visualizatiions (i.e. *bar graphs*, *line graphs*, *etc*.). For the dashboard (webpage), we created a demographic panel that included a dropdown menu that list the ID numbers of all the volunteers. When a volunteer ID is chosen from the dropdown menu, that person's demographics information (i.e. *location*, *sex*, *age*) will be displayed.


### Purpose and Background

The purpose of the project was to complete the dashboard (Belly Button Biodiversity webpage). In addition to the completed panel for demographic information, we needed to visualize the bacterial data for each volunteer. In addition, the volunteers should be able to identify the top 10 bacterial species in their belly bulttons, so Improbable Beef identifies a species as a candidate to  manufacture synthetic beef. The volunteers will be able to identify whether that species is found  in their navel. For the dashboard, we created: 1) **Bar Chart** (*Top 10 bacterial species* (OTUs)), 2) **Bubble Chart** (*Bacteria Cultures per Sample*), and 3) **Gauge Chart** (*display weekly washing frequency's value as a measure from 0-10*). 



<img width="948" alt="New Created Webpage (with url link)" src="https://user-images.githubusercontent.com/107021231/187162192-cdfbb3de-0dcd-4688-b710-250dc46a1fb5.png">

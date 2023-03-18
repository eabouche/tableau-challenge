# NYC Citi Bike Program Overview for February 2023

This project consisted on working with the <a href="https://en.wikipedia.org/wiki/Citi_Bike" target="_blank">New York City Citi-Bike Program</a> data, the largest bike-sharing program in the United States, and using the Tableau software to create interactive dashboards and stories to provide an overview of the program while capturing 2 phenomena noticed duing the analysis.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the <a href="https://citibikenyc.com/system-data" target="_blank">Citi Bike Data</a> webpage.

For analysis and exploration of the NYC Citi Bike Tableau visualization please visit this link: <a href="https://eabouche.github.io/tableau-challenge/" target="_blank">NYC Citi Bike Overview</a>

### Written analysis - trends discovered in the data:
- Discrepancies: When using the interactive map and clicking on a specific dot representing a station, sometimes the count of rides for a particular station will not match the overall count of rides for that station displayed in the bar charts.  This is because sometimes the latitude and longitude are slightly different for the same station name. Therefore, 2 dots in the map next to eachother may represent the same station name with different counts. If wanting to know the total number of rides per station, rely on the bar chart totals.

- Phenomena 1: the top 10 busiest stations in Manhattan to start a journey from are the same as the top 10 busiest stations to end a journey. However, places 7th and 8th in the top ten "Busiest Stations in Manhattan" story are flip flopped between the stations to start a journey from and the stations to end a journey at visualization bar charts.  "11 Ave & W 41 St" station is on 7th place in the top 10 busiest stations to start a journey from, but drops one place to 8th place in the top 10 busiest stations to end a journey at.  And it switches places with "W 41 St & 8 Ave". They are almost equally busy.

- Phenomena 2: There are far more members than casual riders of the program.  However, longest trip durations are by far largest among the casual riders.  This can be due to casual riders being tourists and taking the bike for longer distances, in comparison to daily commuters moving back and forth between work and home consistently.


### Web Programming Languages and Software used:
- HTML
- Tableau

![image](https://user-images.githubusercontent.com/115383317/226077367-cdc59b50-9cc3-48dc-b91a-1bcaca96c2ba.png)

![image](https://user-images.githubusercontent.com/115383317/226077410-d5308644-48e6-42e4-8ec3-343e75a5a4b4.png)

![image](https://user-images.githubusercontent.com/115383317/226077435-befe892c-4670-4022-bef9-bc61b99060d6.png)



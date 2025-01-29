# belly_button_challenge
By: Itzel Vázquez Sánchez

## Project Description

This project is part of the Data Analysis and Visualization Bootcamp from Tecnológico de Monterrey. In this assignment, the task was to build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogs the microbes that colonize human navels.

The following steps must be followed:
1. Use the D3 library to read in _samples.json_ from the URL https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json.
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
   * Use _sample_values_ as the values for the bar chart.
   * Use _otu_ids_ as the labels for the bar chart.
   * Use _otu_labels_ as the hovertext for the chart.
3. Create a bubble chart that displays each sample.
  * Use _otu_ids_ for the x values.
  * Use _sample_values_ for the y values.
  * Use _sample_values_ for the marker size.
  * Use _otu_ids_ for the marker colors.
4. Display the sample's metadata, i.e., an individual's demographic information.
  * Loop through each key-value pair from the metadata JSON object and create a text string.
  * Append an html tag with that text to the _#sample-metadata_ panel.
  * Use _otu_labels_ for the text values.
5. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard.
6. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

🤓 This Project is the result of the learning lessons of Module 14: Interactive Visualizations from the Data Analysis and Visualization Bootcamp 2024. The main goal is to use the acquired habilities and knowledge in a real case. 

## Table of contents :point_right:

On the repository you'll find:

| Item| File Type|File Name  |   Description      |
|-----|----------|-----------| -------------------|
|1    | folder   | static/js |Contains app.js file|
| 2   |   html   | index     | From starter code  |
| 3   |   json   |  samples  | From starter code  |

## How to Use the Project

* The app.js file contains the code to generate the dashboard.
* If you download the folder, you can use it in Visual Studio Code, and open the html in browser.
* This link allows you to visualize the dashboard: https://itzelvazsan.github.io/belly_button_challenge/ 


## Credits :scroll:
The code of this project origins from: starter code provided by the Team of the Data Analysis and Visualization Bootcamp, the solved exercises worked in the Zoom Lessons and Microsoft Copilot.

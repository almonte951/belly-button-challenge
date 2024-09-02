# Belly Button Challenge
Module 14 Challenge
By: Eddie Almonte

For this assignment, you will create an interactive dashboard to explore the Belly Button Biodiversity dataset, which documents the microbes that inhabit human navels. The data highlights that a select few microbial species, known as operational taxonomic units (OTUs), are found in over 70% of individuals, while the majority of species are much less common.

### Instructions:

Follow these steps to complete the task:

1. Utilize the D3 library to load the `samples.json` file from the following URL: [https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json).

2. Create a horizontal bar chart that includes a dropdown menu, allowing users to display the top 10 OTUs (Operational Taxonomic Units) identified in each individual.

3. Set `sample_values` as the data values for the bar chart.

4. Use `otu_ids` as the labels for the bar chart.

5. Assign `otu_labels` as the hover text for the chart.


![Module 14 Challenge Bar Chart](https://i.postimg.cc/W4QXK4Mg/Top-10-Bar-Chart.png)


### Next: 

Create a bubble chart that represents each sample, follow these instructions:

1. Set `otu_ids` as the x-axis values.
  
2. Use `sample_values` for the y-axis values.
   
3. Assign `sample_values` to determine the size of the markers.
   
4. Use `otu_ids` to define the colors of the markers.
   
5. Set `otu_labels` as the text values displayed on the chart.


![Module 14 Challenge Bubble Chart](https://i.postimg.cc/XNKQH4XB/Bacteria-Bubble-Chart.png)


### Now:

Display the sample's metadata, i.e., an individual's demographic information.

Loop through each key-value pair from the metadata JSON object and create a text string.

Append an html tag with that text to the #sample-metadata panel.

![Module 14 Challenge Demo Info](https://i.postimg.cc/QdCmd7mc/Demo-Info.png)

### Last:

Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


![Module 14 Challenge Dashboard](https://i.postimg.cc/wvXcGQxY/Completed-Dashboard.png)


In conclusion, by following these steps, you'll create a comprehensive and interactive dashboard that visually explores the microbial diversity found in human navels. This dashboard will not only display key microbial species through bar and bubble charts but also provide detailed metadata for each sample. Once complete, your dashboard will dynamically update to reflect the selected samples, offering an engaging and informative way to explore this fascinating dataset.

### Notes:

For this Module 14 Challenge assignment, I used past classroom activities, ChatGPT, and lots of cross referencing on Stack Overflow.

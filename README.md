# Interactive-Visualizations-and-Dashboards
Interactive dashboard to explore the, which catalogs the microbes that colonize human navels.  The dataset reveals that a small handful of microbial species were present in more than 70% of people, while the rest were relatively rare.
# Plot.ly Homework - Belly Button Biodiversity
Dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
  - Using Plotly and D3 library to read in `samples.json`, created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
  - Used `sample_values` as the values for the bar chart, `otu_ids` as the labels for the bar chart, `otu_labels` as the hovertext for the chart.

Created a bubble chart that displays each sample, `otu_ids` for the x values, `sample_values` for the y values and `sample_values` for the marker size & `otu_ids` for the marker colors.
`otu_labels` for the text values.

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)
![bar Chart](Images/hw01.png)

![Bubble Chart](Images/bubble_chart.png)
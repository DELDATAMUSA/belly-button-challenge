# belly-button-challenge

![alt text](<Bellybutton Biodiversity.png>)

Overview
This project delves into an interactive exploration of microbial data from diverse individuals, utilizing the D3.js library to parse and represent information from a comprehensive JSON dataset visually. The primary objective is to reveal the top Operational Taxonomic Units (OTUs) present in individuals, employing dynamic visualizations like horizontal bar charts and bubble charts to capture the complexity and richness of the data. Through an intuitive interface featuring dropdown menus and responsive charts, users can navigate through the dataset to gain insights into the microbial communities within each sample. Additionally, the project includes the display of demographic metadata, providing further context to the explored datasets. Designed with accessibility in mind, the project is hosted on GitHub Pages, inviting users to engage interactively with the data. This initiative underscores the capabilities of web-based data visualization tools and emphasizes the potential for enhanced comprehension of microbiological ecosystems through data analytics.

Deployment
Explore the intriguing realm of microbial ecosystems through our interactive dashboard: file:///C:/Users/user/OneDrive/Desktop/Starter_Code/belly-button-challenge/index.html

Data
The data utilized in this project originates from a fascinating study conducted by Hulcr, J. et al. (2012), titled "A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable." This research uncovers the remarkable diversity and predictability of bacterial ecosystems residing in human belly buttons, drawing upon samples collected from a diverse range of participants. Accessible through the Rob Dunn Lab's website (http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/), the study offers a comprehensive exploration into the microcosm thriving within our navels, shedding light on the intricate interplay of factors influencing the composition of these bacterial communities. Leveraging this rich dataset, our interactive dashboard enables users to visualize and comprehend the bacterial diversity present in different individuals' belly buttons, elucidating the broader implications of microbial biodiversity on human health and ecology.

Employed Technologies
Data manipulation and binding to DOM elements:D3.js 
Creating interactive visualizations (bar chart, bubble chart, and gauge chart): Plotly.js 
Responsive design: Bootstrap

Functionality Highlights

1. Horizontal Bar Chart: Presents the top 10 OTUs found in an individual.
Values: sample_values
Labels: otu_ids
Hovertext: otu_labels

2. Bubble Chart: Illustrates each sample.
X values: otu_ids
Y values: sample_values
Marker size: sample_values
Marker colors: otu_ids
Text values: otu_labels

3. Demographic Information Panel: Displays the demographic information of the selected individual as key-value pairs.

4. Gauge Chart: Depicts the weekly washing frequency of the individual.

How to Use
Choose a Test Subject ID No. from the dropdown menu to update the visualizations with data specific to that individual.
Hover over the charts to view additional details about the bacteria cultures and their frequencies.


REFERENCES:

building plots:https://plot.ly/javascript/ 
bubble chart: https://plotly.com/javascript/bubble-charts/
colorscale for bubble chart: https://plotly.com/javascript/colorscales/
Iterating through an object: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries#iterating_through_an_object:~:text=Iterating%20through%20an%20Object
weekely washing frequency gauge chart:https://plot.ly/javascript/gauge-charts/
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/
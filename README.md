# belly-button-challenge
UCI Bootcamp Week 14 - Belly Button Challenge

![Screenshot_1510](https://github.com/Adykey79/belly-button-challenge/assets/149746353/e047534b-1c37-4e18-be11-0bde6408cc74)


## Belly Button Biodiversity Dashboard
### Introduction
Welcome to the Belly Button Biodiversity Dashboard, a project developed by Hanns Peter Principal as part of the UTOR-VIRT-DATA-PT-08-2023-U-LOLC-MTTH(B) Bootcamp. This project is a submission for the Module 14 Challenge, focusing on building an interactive web application to visualize and analyze the Belly Button Biodiversity dataset.

### Overview
The Belly Button Biodiversity Dashboard is an interactive tool allowing users to explore microorganisms' biodiversity in human navels. It showcases the diversity of microbial species (operational taxonomic units, or OTUs) found in human belly buttons. Users can select different test subjects to view the top 10 OTUs, represented through dynamic bar and bubble charts.

![Screenshot_1512](https://github.com/Adykey79/belly-button-challenge/assets/149746353/d0c95bbb-53dc-49e5-9228-5deb8f16cc59)


### Functionality
The dashboard offers several interactive features:

- Dropdown Menu: Users can view their microbial data by selecting different test subjects.
- Bar Chart: Displays the top 10 OTUs found in the selected individual.
- Bubble Chart: Represents each sample with OTU IDs for the x-values and sample values for the y-values.
- Metadata Display: Shows demographic information of the selected individual.
- Gauge Chart: (Optional Advanced Feature) Illustrates the weekly washing frequency of the individual.


![Screenshot_1511](https://github.com/Adykey79/belly-button-challenge/assets/149746353/c3c3e391-c6bc-4cd9-b8c7-68ee121cae28)


### Development Process
The development involved several key steps:

- Data Reading with D3: Utilized D3.js to read in samples.json for data processing and visualization.
- Interactive Visualizations: Implemented bar and bubble charts using Plotly.js, dynamically updating based on the selected sample ID.
- Dashboard Design: Employed Bootstrap for responsive design, ensuring a clean and accessible user interface.
- JavaScript for Interactivity: The main.js file contains the logic for event handling, data processing, and rendering the visualizations.
- Testing and Debugging: Rigorous testing was conducted to ensure the accuracy and responsiveness of the dashboard across different browsers and devices.


### Conclusion
This project highlights modern web technologies like D3.js and Plotly.js to create interactive data visualizations. It serves as an excellent example of how data can be made more accessible and engaging to a wider audience.



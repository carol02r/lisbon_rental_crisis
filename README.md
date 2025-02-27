[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/9NdxGEaf)


# MY472-AT24 Final Project: Mapping Lisbon’s Rental Crisis

This repository contains data, documentation, and analyses for my MY472 project, which investigates Lisbon's rental market crisis. 

The project combines rental property data retireved from [Idealista](https://www.idealista.pt) with socioeconomic indicators from Portugal's National Statistics Institute ([INE](https://www.ine.pt/xportal/xmain?xpgid=ine_main&xpid=INE)) and geographic data on municipality boundaries and key amenities. The datasets created enable geographical analysis, visualizations, and predictive modeling to support policy-makers in tackling Lisbon's rental crisis. Some use cases are included to demonstrate the analysis process and findings.


#### Repository Structure:

- **`MY472-AT24-final-report.html`**: Knitted HTML report summarizing data collection.  
- **`MY472-AT24-final-report.Rmd`**: R Markdown file for generating the report. Can be extended or adjusted.
- **`MY472-AT24-final-instructions.md`**: Project instructions.

- **`API Data/`**: Raw and tabular data sourced from APIs and web scraping.

  - **`Primary/`**: Rental property data collected from primary source (Idealista). 
  
  - **`Secondary/`**: Secondary data organized by source:  
    - **`Geodados CML/`**: Municipality boundaries.
    - **`INE/`**: Municipality codes and socioeconomic indicators.
    - **`OSM/`**: Location of key city amenities.
    
- **`API Documentation/`**: Includes documentation for APIs used.  

- **`Transformed Data/`**: Processed datasets ready for analysis.  

- **`Use Cases/`**: Case studies outputs derived from the data.  

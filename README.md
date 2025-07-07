
# Happiness and Commuting (SOEP)

## Context
This project was developed as part of the university course *"Becoming Fluent in Data Science and Beyond"*.  
It received a final grade of **1.3**, reflecting gut data analysis skills and the ability to interpret complex social data.  
The course provided a solid introduction to working with real-world data in **RStudio**, and this was one of the first projects where I explored and analyzed a dataset in depth.

## Description
This project investigates the relationship between life satisfaction (happiness) and commuting behavior in Germany using the SOEP (Socio-Economic Panel) dataset. The analysis explores how commuting time, distance, and frequency affect reported happiness, and how factors such as income, employment status, and education interact with commuting.

## Author
**Anastasiia Apatenko**  
Date of completion: August 30, 2024

## Data Source
The study uses publicly available SOEP data (1984–2020), provided by the German Institute for Economic Research (DIW Berlin).

Used datasets:
- `pequiv.dta`
- `pgen.dta`
- `pl.dta`
- `hgen.dta`

## Libraries Used

The following R libraries were used throughout the analysis and visualization:

- `haven` – for importing `.dta` (Stata) files  
- `dplyr` – for data wrangling and transformation  
- `ggplot2` – for static data visualization  
- `tidyr` – for data reshaping and tidying  
- `writexl` – for exporting tables to Excel  
- `plotly` – for interactive visualizations

## Variables Analyzed
- Age, Gender, Marital Status  
- Household Size, Monthly Household Income  
- Years of Education, Education Level  
- Employment Status  
- Life Satisfaction Score  
- Commuting Time, Commuting Distance, Frequency  
- Income Satisfaction  

## Hypotheses
1. Longer commuting times are associated with lower levels of life satisfaction.  
2. This relationship varies with income, education, and employment status.

## Key Findings
- **Commuting**: Moderate to weak negative correlation with life satisfaction; high commuting frequency shows more stable time patterns.
- **Income**: Moderate positive correlation between income and happiness; diminishing returns after a certain point.
- **Education & Employment**: Higher education is linked with full-time employment and higher life satisfaction.
- **Demographics**: Younger and married individuals generally report higher happiness.

## Visualizations
All plots were generated in R using `ggplot2`. Interactive and static visualizations include:
- Age and gender trends over time  
- Income per household and per person  
- Education level by employment status  
- Commuting time vs. happiness (scatter plots)  
- Correlation matrices



## Files
- `SOEP.Rmd` – Source R Markdown file (code + narrative)
- `SOEP.pdf` – Final report (static version)
- `SOEP.html` – Interactive version of the report
- `references.bib` – Bibliography in BibTeX format

## Tools & Technologies
- R (tidyverse, haven, ggplot2, dplyr, etc.)
- SOEP Data (.dta format)
- R Markdown

## License
This project is academic and non-commercial. Please contact the author for reuse or citation requests.


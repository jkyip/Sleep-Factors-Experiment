# Investigation on the Ideal Sleeping Conditions for Students

## Overview

Welcome to the repository for the investigation on the ideal sleeping conditions for students, a final project undertaken as part of the STA305 H1S Sec L0101 course at the University of Toronto. The primary purpose of this experiment is to showcase skills in experimental design and analysis within the context of sleep quality factors.

## Introduction

This project serves as a showcase of skills in experimental design and statistical analysis for a specific aspect covered in the STA305 course at the University of Toronto. The aim was to determine optimal conditions for students to achieve quicker sleep onset in a boarding school environment.

## Methodology

The experiment was structured as a factorial design, exploring the impact of room temperature, blanket weight, and room brightness on sleep quality. Data was gathered from 16 student participants through afternoon nap and nighttime trials, conducted across 4 dorm rooms. The subsequent analysis was performed using advanced statistical techniques in R.

## Data Source

The data used and provided in this project was simulated using R, guided by existing research on sleep habits. Should you wish to replicate this experiment with real-world data, the methodology outlined in the `investigation.Rmd` file provides a clear guide. Collecting your own data and employing the provided analysis code will yield insights into optimal sleeping conditions.

## Course Information

This project focuses on a particular aspect covered in the STA305 course at the University of Toronto. The course provided insights into experimental design and analysis, with a specific emphasis on the following topics:

- Experiments vs observational studies, experimental units.
- Designs with one source of variation, complete randomized designs, and randomized block designs.
- Factorial designs, inferences for contrasts and means.
- Model assumptions, crossed and nested treatment factors, random effects models.
- Analysis of variance and covariance, sample size calculations.

The knowledge and skills gained from this course were applied to design and analyze the experiment in this project, showcasing a comprehensive understanding of experimental design principles and statistical analysis techniques.

## Files and Folders

- `data.csv`: Raw data file generated for the experiment.
- `Raw Data.csv`: Exported raw data file containing experimental results.
- `investigation.Rmd`: R Markdown document containing the data analysis code.
- `anova.csv`: ANOVA table exported from the statistical analysis.
- `.gitignore`: Gitignore file for R projects.
- `LICENSE`: The MIT License for this project.
- `README.md`: This file providing an overview of the project.
- `Report.pdf`: Exported PDF report summarizing the project findings.

## Gitignore

The `.gitignore` file is included to exclude unnecessary files from version control, such as temporary files or sensitive information. It's essential for maintaining a clean and organized repository.

## MIT License

This project is licensed under the terms of the MIT License. Feel free to use and modify the code according to the license terms.

## Replicating the Analysis

To replicate the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Open the `investigation.Rmd` file in R or RStudio.
3. Ensure you have the required R packages installed (tidyverse, FrF2, knitr).
4. Execute the code chunks in the `investigation.Rmd` file to reproduce the analysis.

## Results and Conclusion

The analysis uncovers notable effects of temperature and brightness on the time required for students to fall asleep. Lower temperature and brightness levels emerge as the optimal conditions for prompt sleep onset. The report further discusses potential enhancements and additional factors for future investigation.

## References

1. The President and Fellows of Harvard College. (2021, September 30). *8 secrets to a good night's sleep.* Harvard Health. Retrieved from https://www.health.harvard.edu/newsletter_article/8-secrets-to-a-good-nights-sleep 

2. Silver, N. (2020, June 5). *How long does it take to fall asleep? average time and tips.* Healthline. Retrieved from https://www.healthline.com/health/healthy-sleep/how-long-does-it-take-to-fall-asleep

3. Ulrike Grömping (2014). *R Package FrF2 for Creating and Analyzing Fractional Factorial 2-Level Designs. Journal of Statistical Software,* 56(1), 1-56.

4. Wickham et al., (2019). *Welcome to the tidyverse. Journal of Open Source Software,* 4(43), 1686. https://doi.org/10.21105/joss.01686.

5. Yihui Xie (2021). *knitr: A General-Purpose Package for Dynamic Report Generation in R.* R package version 1.37.

For any inquiries, please contact Chun Ki Yip at [jackyyipchunki@gmail.com](mailto:jackyyipchunki@gmail.com).

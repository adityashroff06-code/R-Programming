# R Programming — Customer Churn Data Analysis

![R](https://img.shields.io/badge/R-4.x-276DC3?logo=r&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-EDA_·_Visualization_·_Statistics-blueviolet)
![License](https://img.shields.io/badge/License-MIT-green)

End-to-end exploratory data analysis of a **customer churn dataset in R** — data cleaning, IQR-based outlier removal, visualization, correlation analysis, and hypothesis testing. Completed for *Programming Fundamentals for Analytics* (George Brown College).

## Analysis workflow

The full worked report (code, output, and plots) is in [`Aditya_shroff_R_assignment.pdf`](Aditya_shroff_R_assignment.pdf). It walks through a 10-step analysis:

| Step | What it does |
|---|---|
| 1–2 | Load libraries and dataset; detect and handle missing values |
| 3 | Compute the **IQR** per numeric variable and filter outliers beyond 1.5×IQR |
| 4 | Visualize distributions **before vs. after** outlier removal to show the effect of cleaning |
| 5 | Group by churn status and compare **average customer value** between churned and retained customers |
| 6 | Build and plot a **correlation matrix** across all numeric variables |
| 7–8 | Select a focused variable subset and re-examine correlations |
| 9 | Aggregate the data and compute summary statistics per segment |
| 10 | Run a **t-test** to check whether the churned/retained difference in customer value is statistically significant |

## Skills demonstrated

- **Data wrangling in base R / tidyverse style** — loading, filtering, grouping, aggregation
- **Outlier treatment** — principled IQR fencing rather than ad-hoc trimming, with visual before/after evidence
- **Visualization** — boxplots, grouped bar charts, and correlation heatmaps chosen to answer specific questions
- **Statistical inference** — moving beyond description to a formal t-test on the churn/value relationship

## Repository contents

```
├── Aditya_shroff_R_assignment.pdf   # Full report: R code, console output, and plots
└── README.md
```

> The analysis was submitted as a rendered PDF report; the underlying `.R`/`.Rmd` source is not included in the repo.

## License

Released under the [MIT License](LICENSE).

## Author

**Aditya Shroff** — [GitHub](https://github.com/adityashroff06-code) · [LinkedIn](https://www.linkedin.com/in/aditya-shroff-8033a31b0)

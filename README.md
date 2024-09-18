# GPA and Market Share Analysis
Statistical analysis of GPA and Market Share datasets using linear regression, hypothesis testing, and confidence intervals. Explores the relationship between ACT scores and GPA, and the impact of promotions on market share, with visualizations and detailed interpretation of results.

### Datasets
1. **GPA Dataset:** Data collected from 120 students to investigate if a student's grade point average (GPA) at the end of the freshman year can be predicted from their ACT test score.
2. **Market Share Dataset:** Monthly data collected over 36 months to analyze the impact of promotions and other factors on the market share of a packaged foods product.

### Objectives
1. **GPA Dataset Analysis:**
   - Summarize and visualize the data to understand its distribution and key characteristics.
   - Build a simple linear regression model to predict GPA using ACT scores.
   - Interpret the model parameters, residuals, and goodness of fit.
   - Perform hypothesis testing and construct confidence and prediction intervals.
   
2. **Market Share Dataset Analysis:**
   - Explore the relationship between market share and promotions using linear regression.
   - Test the significance of year-over-year changes in market share using the year as a categorical predictor.

### Repository Structure
- `GPA_Market_Analysis.Rmd` - R Markdown file containing the complete analysis for both datasets.
- `Detailed_Report.pdf` - PDF file with the comprehensive report of the analysis.

- ### Key Findings
1. **GPA Dataset Analysis:**
   - A positive relationship was found between ACT scores and GPA, with a modest linear fit.
   - The regression model explained about 7.26% of the variability in GPA.
   - Confidence intervals and hypothesis testing indicated a statistically significant association between ACT scores and GPA.

2. **Market Share Dataset Analysis:**
   - The presence of promotions showed a slight increase in market share, but the relationship was not statistically significant.
   - Year-over-year analysis did not reveal significant differences in market share from 1999 to 2002.

### Conclusion
The analyses provided insights into the relationship between ACT scores and GPA, as well as the impact of promotions on market share. While a modest positive association between ACT scores and GPA was identified, the market share analysis indicated no significant impact of promotions or year-over-year changes.

### How to Use
To reproduce the analyses, clone this repository and open the R Markdown files (`.Rmd`). You can knit these files in RStudio to generate the HTML or Markdown outputs.
```bash
# Clone the repository
https://github.com/dandyy11/GPA-and-Market-Share-Analysis.git

### Contact
For questions or suggestions, please contact Salman Imtiaz at salman.imtiaz414@gmail.com

# World Universities Rankings by Country

Small personal dataviz project aimed at visualizing and exploring world university rankings from a country-level perspective.

![](https://www.ohmychart.com/uni-ranks-cover-post.png)

[**Visit the project's website**](https://d2ski.github.io/uni-ranks/)
  
**Questions:**
- Which countries’ universities are ranked the best?
- How countries’ universities ranks distributions were changed across different years?

**Tools Used:**
- Python (pandas) for data preprocessing;
- R (ggplot2 + RMarkdown) for visualization and presentation.

**Data Sources:**
- [Times Higher Education World University Rankings](https://www.timeshighereducation.com/content/world-university-rankings)
- [QS World University Rankings](https://www.topuniversities.com/university-rankings)
- [Academic Ranking of World Universities](https://www.shanghairanking.com/rankings)

Raw data and prepared dataset are available in the repository's `data_raw` and `dataset` folders accordingly.
Data from 2014 to 2021. Ranking places were limited to TOP-500 universities from each ranking per year.

**Notes:**
Some rankings don't assign exact rank and corresponding scores for universities presented in the rankings bottom range. That's why scores were recalculated using the corresponding ranking's methodology(code available in `02_tidy_and_prep/Scores Dataset Preparation.ipynb` Jupyter notebook).
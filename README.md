# A/B Testing Analysis: Impact of Website Background on User Engagement
This project analyzes user session data to evaluate if a dark background affects the time users spend on a website. 
The analysis was performed in Python (Google Colab) and visualized in Tableau.

### Goal: To test whether changing the website background color from white to black increases user engagement.
Data Preparation: Loaded and cleaned data using pandas.
Statistical Testing:
- Normality check — Shapiro–Wilk test
- Group comparison — Mann–Whitney U test
- Segmentation — Kruskal–Wallis test by device and region

### Visualization: 
Built Tableau dashboard showing metrics, distributions, and group comparison.

### Results
Group A (white background): 57.4 sec
Group B (black background): 56.1 sec
p-value: 0.766 → No statistically significant difference
Conclusion: Keep the white background as default; consider adding dark mode as an optional feature.

### Tools & Technologies
Python: pandas, scipy, matplotlib, seaborn
Tableau Public: interactive dashboard
Statistical methods: Shapiro–Wilk, Mann–Whitney, Kruskal–Wallis

Problem Statement:
Analyze Google Play Store app data to uncover trends in ratings, reviews, and features that can guide app development strategy, improve user experience, and increase downloads and revenue.


Steps:
- Analyzed app ratings, installs, reviews, and categories.
- Handled missing values and performed category-level analysis, changed datatypes to their proper format while extracting info like year & month, then cleaned size & install column to pull size and no. of    installs to perform analysis.
- Built visualizations to detect trends and outliers.
- Tools Used: Pandas, NumPy, Matplotlib, Seaborn

Key Insights :

- Mostly 0-20mb size apps are downloaded.
- 92% of apps are free.
- Facebook,skype,google drive, google news, youtube are most installed apps.
- Free apps has 3 times more reviews than paid ones.
- categories like game, family, travel & local, sports, entertainment having the largest file size.
- With increase in ratings , no. of installs also increases majorly between 4.0 to 4.5.
- Some small apps are among the most downloaded apps in the store. Large size does not prevent high installs, but fewer apps achieve it.
- App size shows no strong linear relationship with ratings, meaning lighter apps can perform just as well as large ones.

Challenges Faced :

- Missing ratings required thoughtful imputation (handled using category-wise averages).
- Data inconsistencies (misaligned rows) had to be removed due to low frequency.
- Several numeric columns were stored as strings, requiring cleaning ($ removal, type conversion).
- Presence of outliers in installs and reviews skewed distributions.
- Mixed formats across columns made preprocessing a critical step before analysis.

Recommendations :
For App Developers
- Focus on category-specific optimization, since rating benchmarks differ by category.
- Prioritize user experience and early reviews — higher review volume strongly supports installs.
- Consider freemium or low-cost pricing models, as most successful apps fall into this range.
- Optimize app size and performance rather than assuming “bigger is better.”

For Product & Business Teams

-Use category-level metrics (not global averages) for performance evaluation.
-Monitor review velocity as an early indicator of app success.
-Invest in user feedback loops to improve ratings post-launch.
-Segment apps by price + install + rating bands to identify monetization opportunities.

For Data Teams :
- Always validate raw datasets for schema shifts and datatype issues.
- Apply context-aware imputation (like category averages) instead of blanket filling.
- Treat extreme install/review values carefully to avoid misleading insights.

Detailed analysis in the code attached in folder.

 Skills Demonstrated :

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Business Insight Generation
- power bi Dashboard Development
- Problem Solving


 Tools & Technologies :

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power bi
- SQL 

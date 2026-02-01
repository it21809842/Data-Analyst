# Data-Analyst

Data Source:
Keyword Ranking Data Sample 2025.xlsx

Steps 
1. Loaded the Excel dataset into Google Colab using pandas
2. Preprocessing data ste, Clean Data set categrized ,remove blank
3. Standardised column names and converted ranking and visibility fields to numeric values,conver date column into same one strandard
4. Treated missing or zero rankings as outside the Top 100
5. Calculated competitor performance metrics including total visibility, Top 10 keyword share, and average ranking position
6. Identified keyword gaps where competitors rank in the Top 10 and Yachting Pages ranks outside the Top 20
7. Filtered opportunities based on search volume and keyword difficulty
8. Analysed performance by search intent (informational vs commercial)
9. Identified low-hanging fruit keywords ranking positions 

Outputs 
1. competitor_summary.csv
2. top_seo_opportunities.csv
3. visibility_by_intent.csv
4. Analysis notebook (.ipynb)


Assumptions
1.Rank values of 0 or missing were treated as outside the Top 100
2.Visibility scores were assumed to be comparable across domains
3.Rankings reflect organic and AI overview visibility where indicated

How to Run
1. Upload the Excel file to Google Colab
2. Open the notebook (.ipynb)
3. Run all cells sequentially from top to bottom
4. CSV outputs will be generated automatically in the working directory

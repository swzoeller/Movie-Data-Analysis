# Movie-Data-Analysis
## Lab Members
- Sarah Zoeller
- Andrew Muller
## Objectives
- Help Microsoft determine key indicators of profit and revenue in movie industry
- Collect and clean data from various databases
- Process data to create meaningful visualizations
- Draw conclusions from visualizations
- Use git as collaborative tool for version control
## Sources
- Revenue and budget information was from a supplied dataset from The Numbers 
- Other information was pulled from the TMDB API using the Requests library
- Data was cleaned and processed using Python, the Pandas library, and the NumPy library
- Visualizations were created using Matplotlib and Seaborn
## Methodology
- The total cleaned dataset amounted to 4,160 movies from the years 1915 to 2019
- When applicable, the median was used as a measure of central tendency
- Profit was measured in absolute terms and using Return on Investment (ROI):
  ROI = (Revenue - Budget) / Budget
## Insights
  From the dataset, animation was the most profitable genre, along with generating the highest revenue.
  
  <img src= "https://github.com/swzoeller/Movie-Data-Analysis/blob/main/Visualizations/Genre%20and%20Budget%20Analysis/Median%20ROI%20Genre.png" width="800" height="200"/>
 
  Budget has a strong positive correlation with revenue. There is also a positive correlation with profits, but not as strong.
  
  <img src= "https://github.com/swzoeller/Movie-Data-Analysis/blob/main/Visualizations/Genre%20and%20Budget%20Analysis/Budget%20v%20Profit.png" width="600" height="400"/>
 
  ROI has a weak positive correlation with rating. If the movie is at least of average quality, it can generate a high ROI.
  
  <img src= "https://github.com/swzoeller/Movie-Data-Analysis/blob/main/Visualizations/Ratings%20Analysis/ROI%20vs%20Rating.png" width="600" height="400"/>
  
  Movies released during December, June and July had higher revenues, possibly due to school holidays.
  
  ![genre](/Visualizations/Release%20Month%20Analysis/Revenue%20by%20Release%20Month.png)
  
  ## Limitations
  
  - Our data was limited to movies that were present in both the Numbers database and TMDB
  - Ratings are user supplied on TMDB
  - Dataset is approximately a year old, so it is missing recent data
  - Certain genres had less information than others, potentially skewing that data
  - There were significant outliers in certain aspects of the data, including ROI

# Movie-Data-Analysis
# Lab Members
- Sarah Zoeller
- Andrew Muller
# Objectives
- Help Microsoft determine key indicators of profit in movie industry
- Collect and clean data from various databases
- Process data to create meaningful visualizations
- Draw conclusions from visualizations
- Use git as collaborative tool for version control
# Sources
- Revenue and budget information was from a supplied dataset from The Numbers 
- Other information was pulled from the TMDB API using the Requests library
- Data was cleaned and processed using Python, the Pandas library, and the NumPy library
- Visualizations were created using Matplotlib and Seaborn
# Methodology
- The total cleaned dataset amounted to 4,160 movies from the years 1915 to 2019
- When applicable, the median was used as a measure of central tendency
- Profit was measured in absolute terms and using Return on Investment (ROI):
  ROI = (Revenue - Budget) / Budget
# Insights
  From the dataset, animation was the most profitable genre, and generated the highest revenue
  
  ![genre_roi](/Visualizations/Genre and Budget Analysis/Median ROI Genre.png?raw=true)

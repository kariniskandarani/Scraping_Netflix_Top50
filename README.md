# Scraping_Netflix_Top50

## Table of Contents

- [Project Summary](#project-summary)
- [Project Objective](#project-objective)
- [Top 50 best Netflix Movies Analysis PPT](#top-50-best-netflix-movies-analysis-ppt)
- [Tools and Libraries Used](#tools-and-libraries-used)
- [Key Features](#key-features)
- [Sample Insights](#sample-insights)
- [How to Run This Project](#how-to-run-this-project)
- [Repository Structure](#repository-structure)
- [Author](#author)

## Project Summary

This project combines web scraping, data engineering, and data visualization to analyze the top 50 Netflix movies. Data is extracted from Digital Trends using BeautifulSoup, stored in a SQLite database, and analyzed through SQL queries and visualizations.The final report explores IMDb rating trends, genre distribution, actor appearances, and movie durations.

##  Project Objective 

- Scrape Netflix's Top 50 movie list from [Digital Trends](https://www.digitaltrends.com/movies/best-movies-on-netflix/)
- Clean and organize the data using Python
- Store the dataset in an SQLite database
- Perform SQL queries for deeper exploration
- Analyze and visualize trends in IMDb ratings, genres, durations, and 

## Top 50 best Netflix Movies Analysis PPT
[Access link](https://docs.google.com/presentation/d/1bwlOd2x_xweSkhG-CD5Arv8ylIdK8Vh4QWHZ-BkUS1w/edit?slide=id.p#slide=id.p)

##  Tools & Libraries Used

- `BeautifulSoup`
- `requests`
- `sqlite3`
- `pandas`
- `matplotlib` / `seaborn` (for visualizations)
- `re`
- `Jupyter Notebook` / `Google Colab`



##  Key Features

### ✅ Web Scraping
- Extracts titles, release years, durations, IMDb ratings, and genres

### ✅ SQL Storage & Queries
- Creates SQLite database and table
- Inserts and queries movie records

### ✅ Data Analysis & Visualizations
- IMDb ratings distribution
- Genre frequency
- Ratings vs. Duration plots
- Top actors by appearance count
- Ratings of movies featuring key actors: Jenna Ortega, Morgan Freeman, Chris Hemsworth
- 

##  Sample Insights

- **Movies with IMDb > 8.5**: Interstellar (2014), Spider-Man: Across the Spider-Verse (2023)
- **Movies with IMDb < 5.7**: The Deliverance (2024), Afraid (2024)
- **Genre Trends**: Comedy is a dominant genre among the top 50
- **Top Actors by Count**: Frequent appearances by big-name actors
- **Interesting Plots**:
  - IMDb Rating vs. Movie Duration
  - Genre distribution bar chart
  - Actor-wise IMDb comparisons

##  How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/netflix-top50-analysis.git
   cd netflix-top50-analysis
2. Install required libraries:
   ```
   !pip install beautifulsoup4 requests pandas matplotlib seaborn

3. Run the notebook:
   Open Karin_Iskandarani_DS_Project_Netflix_Top_50.ipynb in Jupyter or Colab

   Follow the steps for scraping, storing, and querying data

4. View analysis results:
   Open the PowerPoint file: Top_50_best_Netflix_Movies_Analysis.pptx

##  Author
**Karin Iskandarani**  
ZAKA Certified Data Scientist  
[Connect on LinkedIn](https://www.linkedin.com/in/karin-iskandarani)  


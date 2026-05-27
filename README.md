Web Scraping, EDA, Visualization & Sentiment Analysis Project

Project Overview
This project demonstrates an end-to-end data analytics workflow, starting from web scraping 
to exploratory data analysis, data visualization, and sentiment analysis using Python.

The data was scraped from a public website containing inspirational quotes and analyzed to extract meaningful insights and sentiment patterns.

Tasks Covered

Task 1: Web Scraping
- Extracted quotes and authors from a public website using `requests` and `BeautifulSoup`
- Parsed HTML structure to collect relevant data
- Created a custom dataset using `pandas`

Task 2: Exploratory Data Analysis (EDA)
- Explored dataset structure and data types
- Checked for missing values and data quality
- Analyzed quote distribution by author
- Identified patterns and trends in the dataset

Task 3: Data Visualization
- Visualized top authors with the most quotes
- Created a distribution plot for quote lengths
- Used `matplotlib` for clear and interpretable charts
- Enhanced insights through visual storytelling

Task 4: Sentiment Analysis
- Applied Natural Language Processing using `TextBlob`
- Classified quotes as Positive, Negative, or Neutral
- Calculated sentiment polarity scores
- Visualized sentiment distribution to understand overall tone


Tools & Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- TextBlob


Project Structure

├── web_scraping.py
├── eda_analysis.py
├── data_visualization.py
├── sentiment_analysis.py
├── README.md

Future Improvements

- Scrape multiple pages for larger datasets
- Use advanced NLP models like VADER or transformers
- Add dashboard using Tableau or Power BI
- Perform sentiment analysis by author or theme

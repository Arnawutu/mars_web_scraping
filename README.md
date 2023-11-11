# mars_web_scraping
In this project, I utilized web scraping techniques to gather information about Mars weather, followed by data cleaning, visualization, and analysis using Python. The workflow for this project comprised two main deliverables:

Deliverable 1: Mars News Article Scraping

Extracted titles and preview text from Mars news articles.
Optional export of the data to a JSON file or a MongoDB database.
Deliverable 2: Mars Weather Data Scraping and Analysis

Utilized Splinter and Beautiful Soup to scrape Mars News website for titles and preview text of articles.
Stored the extracted data in Python dictionaries within a list.
Optionally exported the scraped data to either a JSON file or a MongoDB database.
Scraped Mars temperature data from the specified URL, focusing on various parameters such as identification number, terrestrial date, sol, solar longitude, Martian month, minimum temperature, and atmospheric pressure.
Examined and adjusted the data types of DataFrame columns as needed.
Data Analysis and Visualization

Answered key questions and created data visualizations:
Determined the number of Martian days in the dataset.
Identified the coldest and warmest months by averaging minimum daily temperatures.
Found months with the lowest and highest atmospheric pressure by averaging daily pressures.
Estimated the number of terrestrial days in a Martian year through visual analysis of daily minimum temperatures.
Explored the total number of months on Mars and identified the average lowest and highest temperatures and atmospheric pressures for each month.
Estimated terrestrial days in a Martian year with a visual estimate within a 25% margin.
Methods Used:

Python
JSON
MongoDB
Beautiful Soup
Splinter
Matplotlib
Pandas
Jupyter Notebook
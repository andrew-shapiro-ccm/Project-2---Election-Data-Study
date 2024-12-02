# Project 2 - Election Data Study

For this assignment, I had to figure out a group of websites that I could web scrap and take the data I web scrapped and analyze it. For this assignment, I selected 270towin.com as, after reviewing their webpage, had a series of tables that I could web scrap for me to analyze and did not block webscraping to any url I planned to scrap. Additionally, their terms of service did not clearly ban the use of web scrapping and as a final check, I searched GitHub to see that many others have also used 270towin to web scrap.

I decided to focus on the 2020 Presidential Election and 2024 Presidential Election - I web scrapped a total of 102 pages (1 for each state + DC). With some questions only focusing on the 2024 election while others involve both as a comparison. The data table had the following: the state name, the candidate name, the vote count, and percentage. To keep the data neat, each state will have multiple rows; but it'll be easy to get the information about a state by creating another dataframe using existing data.

## 4 Data Science Questions

These are the four data science questions that I answered in this Project. 
1. How did voter turnout in 2024 compare to 2020 in each state?
2. How did the number of voters in battleground states compare to non-battleground states in both elections?
3. Which states saw the largest shift in vote percentage between the 2020 and 2024 election?
4. Which third-party 2024 presidential candidate was on the most state ballots?

## Project Files

You can find 4 different project files in this GitHub Repository.
1. **Election2020.csv** is the CSV file of the 2020 Presidential Election data that we web scraped.
2. **Election2024.csv** is the CSV file of the 2024 Presidential Election data that we web scraped.
3. **web-scraping.ipynb** is the Jupyter Notebook file that we ran to web scrap our websites and store all of the data into the two .csv files above.
4. **data-analysis.ipynb** is the Jupyter Notebook file that analyzes the data to answer the 4 data science questions. It showcases the commands used to clean up the data further for each question, plots the data in an easy to read format, and conducts an analysis for each of them, sometimes even adding more graphs and data analysis commands to create a better understanding or verify an analysis.

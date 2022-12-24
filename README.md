# 2022 Cy Young Predictions

## Description
Using multiple linear regression and machine learning through Python, I predict the winners of the 2022 AL &amp; NL Cy Young awards. This project consists of three phases: Web Scraping, Data Cleaning, and Data Analysis. 

## Libraries Used
- Pandas
- Numpy
- BeautifulSoup
- Requests
- Selenium

## Jupyter Labs
- scrape_cyyoung.ipynb
  - Scraping and parsing pitcher stats, team stats, and Cy Young voting from Baseball Reference.
  - ***Cy Young Voting***
    - cy_young
      - Folder containing the Cy Young Voting from 1990-2021 in html format.
    - al_cy.csv & nl_cy.csv
      - Cy Young Voting data concatenated into dataframes and written as csv files.
  - ***Pitcher Stats***
    - pitcher_stats
      - Folder containing pitching stats from 1990-2022 in html format.
    - pitchers.csv
      - Pitching data concatenated into a dataframe and written as a csv file.
  - ***Team Stats***
    - team
      - Folder containing team stats from 1990-2022 in html format.
    - teams.csv
      - Team data concatenated into a dataframe and written as a csv file.
- dc_cyyoung.ipynb
  - Cleaning the data collected in the web scraping phase of the project. Methods used include the addition/removal of columns, management of NA values, and the grouping of information.
  - ***Combined Stats***
    - al_stats.csv & nl_stats.csv
      - Cy Young voting, pitcher stats, and team stats cleaned and combined into a single database to be written as csv files.
- al_cyyoung.ipynb & nl_cyyoung.ipynb
  - Building a machine learning algorithm through the use of multiple linear regression.
  - Implementing backtesting to review the accuracy of the model.
  - Adding and removing predictors to further improver the accuracy of the model.
  - Making predictions on the AL & NL Cy Young winner.
- al_cy.csv & nl_cy.csv
  - Cy Young voting data

## Social
- LinkedIn: https://www.linkedin.com/in/alexcardoza/
- Follow @cozybaseball on Twitter for interesting baseball statistics and graphics

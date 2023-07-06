# Project-One
## News Coverage Analysis - Write Up
### Team members: Brian Silfer, Bonjanette Koontz, Matthew Johnson

Sources for data for this project are:
https://www.kaggle.com/datasets/dgawlik/nyse?select=securities.csv (Data from 2010-2016)
https://www.kaggle.comhttps://www.kaggle.com/datasets/dgawlik/nyse?select=securities.csv/datasets/henryhan117/sp-500-historical-data
https://developer.nytimS&P 500 Historical Data | Kagglees.com/docs/articlesearch-product/1/overview
https://developer.nytimes.com/docs/archive-product/1/overview

Our goal with this project was to analyze how public news coverage affects the stock market.
We used these data sets to analyze market data to find dates of significant price movement.
We utilized the NYT Archive API to pull articles from specified date ranges.

As each member focused on different aspects of this project, there are three Jupyter notebooks containing relevant code. Sentiment_Analysis.ipynb located in Branch Brian-feature contains code exploring the S&P 500 and code for application to retrieve NYT data for user's choice of date.  Sentiment_Analysis_Bonjanette.ipynb in Branch Bonjanette-feature contains code exploring market sectors and related headline data pulled from the NYSE API. Sentiment_Analysis.ipynb in Branch Matt-branch contains code exploring individual stock movements.

The main question we wanted to answer was how does news coverage impact stock market prices. Through the creation of an application which allows a user to input a date and return
the business articles from that date, one can analyse the new coverage during the time of the significant price movement. We were not conclusively able to determine significance, but we were able to 
create something that has usibility beyond the classroom. Our initial idea was to create a sentament analysis of the stock market. This would have required scanning through snippets of the New York Times Articles to gauge whether the article was a postitive, neutral, or a negative one. This would then allow us to overlay a frequency of a certain sentoment over our price data to analyse the impact of sentament and price changes. Since we weren't able to create that aspect of the application we decided to stick with our original plan. Our application would be extremely useful in a market research capacity. If given a project to research a past market event, one could simply input the event dates in question and be given all relevant articles from that date. This could be expanded to other APIs as well.


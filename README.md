# Scraper - Latest News Notebook
## Introduction
Web application keeps record of latest technology news from 
Microsoft Developer Newsletter / MSDN Flash Archive (https://msdn.microsoft.com/en-us/aa940986.aspx) and notes about them.

## Prerequisites
* No prerequiites are needed. Everything is allocated and deployed to Heroku.

## Force Scrape
* Use your web browser to navigate to https://rocky-everglades-61682.herokuapp.com/scrape;
* Make sure you receive `Scrape Complete` message, which means latest MSDN news are successfully scraped to MongoDB.;
* Now you can view the news and and comments to them (see next section).

## Commenting The News
* Use your web browser to havigate to https://rocky-everglades-61682.herokuapp.com/;
* You should see a list of latest news;
* Scroll and click on the news you want to comment on;
* An text edit comntrol will appear on your right side;
* Add your comments and click `Save Note`.

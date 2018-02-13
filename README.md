# all-the-news
https://sleepy-bayou-39041.herokuapp.com/

All the News That's Fit to Scrape -
This is a  web app that scrapes the news from another site (NYT) and lets users leave comments on the latest news.

Whenever a user visits this site, the application scrape stories from a news outlet (NYT)  and display them for the user. Each scraped article  display the following information for each article:
* Headline - the title of the article

* Summary - a short summary of the article

* URL - the url to the original article

The user has the option to enter their name and comment.

At the beginning of each article the user can navigate thru all articles scrapped by clicking on the prevous and next article buttons.



Technology Used.

Express for routing Mongodb to store the articles and comments. Mongoose is use to build the models for the articles and comments. Cheerio is used to scrape the website for articles. Body-Parser to extract the name and comment from the site to store in the comments collection. 

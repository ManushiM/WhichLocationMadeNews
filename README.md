# Which Location Made News

The purpose of this project is to extract a number of NYTimes articles during a week and to gauge which location in the world was mentioned how many times during that week within the extracted extracted corpus of articles.

The process followed in the [jupyter notebook](https://github.com/ManushiM/WhichLocationMadeNews/blob/master/NYTimes_Test_January50.ipynb) is summarized as follows:
* Use the 'nytimesarticle' Python package to extract details of 50 articles (on account of limitations) within a week (January 1-7 2017).
* Parse the details of each article to extract details of interest, such as Article Headline, Article Type, Web URL, etc.
* Extract locations mentioned in the articlesand store it in a separate list.
* Scrape through the NYTimes website to get article content for each article and store them together.
* Calculate frequency of each location within the corpus.
* Geocode each location.
* Create a [web-map](https://manushim.github.io/WhichLocationMadeNews/mymap) with these locations.

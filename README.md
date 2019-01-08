# yogee
A yoga studio location recommender.

1. Yogee is a web-app that helps yoga instructor find the best location for a new yoga studio in NY state. www.yogee.info

2. Instructor can find good areas to open a new studio by entering a zip code and yogee recommends five nearby zip codes to open a new studio.

3. Yogee uses new studio openings as an analogy for demand for yogee in that zip code. Whether one of more studios is opened at each zip code was predicted from demographics data of the zip code (e.g. income, population).

4.  The yoga studio location data was downloaded from the Yelp api, the year the studios were opened was found in the NY state active corporations database, and the demographics data was retrieved from the American Community Survey.

5. A logistic regression model predicts whether one or more studio opened in a following zip code at a given year.

6. The demand for yoga in a zip code was set as the predicted chance new studios will open in the following year.

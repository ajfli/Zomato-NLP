# Zomato-NLP
# Introduction
This notebook details a comprehensive data analysis of Zomato's restaurant data. Zomato is a popular restaurant search and discovery website, containing a numerical rating for each restaurant alongside its characteristics (e.g. cuisine, location, whether or not it serves alcohol). Users can also leave written reviews alongside their rating. Zomato's repository thus offers a rich opportunity to discover relationships between restaurant rating, restaurant characteristics, and reviewer sentiment. For this project, we will focus on restaurants located in Melbourne.

From a business perspective, it is helpful to understand the extent to which different restaurant characteristics influence a restaurant's subjective rating and hence customer desirability. It is also useful to analyse the extent to which sentiment derived from written user reviews influences restaurant ratings, as this text is ubiguitous elsewhere on social media platforms (e.g. the restaurant's Facebook page).

# Results
An extensive exploratory data analysis was performed, shedding light on relationships between restaurant characteristics, restaurant sentiment, and Zomato ratings. Two predictive models for rating were trained on either all or a subset of these features, although overall prediction accuracy left room to desire.

model using all available features had an average error of +/- 0.25 when predicting restaurant rating on a test set. The number of reviews/photos/blogs and sentiment scores emerged as the most important features for prediction. A model using only restaurant characteristics produced higher average errors (+/- 0.36), with Vegan Options, Sports Bar, and Craft Beer being the most important features for prediction. In future, one may attempt to use other supervised learning methods (such as a support vector machine) to improve prediction accuracy.

# Conclusion
Findings suggest that restaurant characteristics only mildly relate to a restaurant's Zomato rating. One noteworthy omission is a measurement of the quality of food that each restaurant is producing. Future work could focus on incorporating this feature in some way, such as by analysing customer reviews for key words (e.g. soggy, bland, tasty, delicious).

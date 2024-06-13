# Recipe for Rating: Predict Food Ratings using ML


### Problem Overview:
In this exciting challenge,we are tasked with building predictive models to predict the ratings for each recipe using the informations like recipe names, reviews, and other important details.

  <b>It's time to turn culinary data into insights!</b>

  #### Dataset Overview

This dataset is the gateway to the Recipe Ratings Prediction Challenge! Each entry captures a unique culinary story with details such as recipe names, user reviews, and various key features. Your task is to explore this rich data and develop predictive models that can forecast the ratings for every recipe. Unleash your creativity and analytical skills to unlock the secrets hidden in the world of flavors!

The dataset is composed of the following files:

- train.csv: The training set, which includes the target variable 'rating' and accompanying feature attributes.

- test.csv: The test set, containing similar feature attributes but without the target variable 'rating' , as it is the variable to be   predicted.

- sample_submission.csv: A sample submission file provided in the correct format for competition submissions.

#### Columns Description

- <b>RecipeNumber:</b> Placement of the recipe on the top 100 recipes list
- <b>RecipeCode:</b> Unique ID of the recipe used by the site
- <b>RecipeName:</b> Name of the recipe the comment was posted on
- <b>CommentID:</b> Unique ID of the comment
- <b>UserID:</b> Unique ID of the user who left the comment
- <b>UserName:</b> Name of the user
- <b>UserReputation:</b> Internal score of the site, roughly quantifying the past behavior of the user
- <b>CreationTimestamp:</b> Time at which the comment was posted as a Unix timestamp
- <b>ReplyCount:</b> Number of replies to the comment
- <b>ThumbsUpCount:</b> Number of up-votes the comment has received
- <b>ThumbsDownCount:</b> Number of down-votes the comment has received
- <b>Rating:</b> The score on a 1 to 5 scale that the user gave to the recipe (Target Variable)
- <b>BestScore:</b> Score of the comment, likely used by the site to help determine the order comments appear in
- <b>Recipe_Review:</b> Text content of the comment

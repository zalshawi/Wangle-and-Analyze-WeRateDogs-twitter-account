# Wangle-and-Analyze-WeRateDogs-twitter-account

# Introduction
[WeRateDogs](https://twitter.com/dog_rates) is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs has over 8 million followers and has received international media coverage. WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use it in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 2500+ of their tweets as they stood on August 1, 2017.

# files:
- wrangle_act.ipynb main file work through  all the project.
- wrangle_report.html explain wangle process only.
- act_report.html explain insights and visualization only.
- Image Predictions File
-- Udacity ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

# Datasets: 
- tweet-json.txt (Given from Udacity).
- image-predictions.tsv (Given from Udacity).
- twitter-archive-enhanced.csv (Given from Udacity).


# Key points before start:
- The analysis only for original ratings (no retweets).
- Assessing and cleaning the entire dataset completely would require a lot of time. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
- Cleaning includes merging individual pieces of data according to the rules of tidy data.
- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.
- Do not need to gather the tweets beyond August 1st, 2017. duo to won't be able to gather the image predictions for these tweets since you don't have access to the algorithm used.


# Software Needed
The following packages (libraries) need to be installed:
- pandas
- requests
- os
- json
- datetime
- matplotlib




Key Points
Key points to keep in mind when data wrangling for this project:

The project only need original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.
Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
Cleaning includes merging individual pieces of data according to the rules of tidy data.
The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of WeRateDogs.
The project does not require gathering tweets beyond August 1st, 2017.

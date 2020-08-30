# Wangle and Analyze WeRateDogs twitter account

# Introduction
[WeRateDogs](https://twitter.com/dog_rates) is a Twitter account that rates people's dogs with a humorous comment about the dog. WeRateDogs has over 8 million followers and has received international media coverage. WeRateDogs downloaded their Twitter archive and sent it to Udacity via email to use it in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 2500+ of their tweets as they stood on August 1, 2017.

# Visualization
![](https://i.imgur.com/Nsa0X9O.png)
![](https://i.imgur.com/JhXKtzT.png)
![](https://i.imgur.com/nbl9jAk.png)

# Files:
- wrangle_act.ipynb main file work through  all the project.
- wrangle_report.html explain wangle process only.
- act_report.html explain insights and visualization only.
- Image Predictions File
Udacity ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

# Datasets: 
- tweet-json.txt (Given from Udacity).
- [image-predictions.tsv](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv) (Given from Udacity).
- twitter-archive-enhanced.csv (Given from Udacity).


# Key points before start:
- The analysis only for original ratings (no retweets). Though tweets in the dataset, not all are dog ratings and some are retweets.
- Assessing and cleaning the entire dataset completely would require a lot of time. Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.
- Cleaning includes merging individual pieces of data according to the rules of [tidy data](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html).
- The fact that the rating numerators are greater than the denominators does not need to be cleaned. This [unique rating system](https://knowyourmeme.com/memes/theyre-good-dogs-brent) is a big part of the popularity of WeRateDogs.
- The tweets beyond August 1st, 2017 not gather. duo to won't be able to gather the image predictions for these tweets since you don't have access to the algorithm used.


# Code and Resources Used
**Python Verison:** 3.8 

**packages:** Pandas, requests, os, json, datetime, matplotlib

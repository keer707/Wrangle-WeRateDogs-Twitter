# WeRateDogs Twitter Analysis

The dataset to be wrangled( and analyzed and visualized) is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs), which is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.

Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations by investigating,
> 1. What are the top 30 most tweeted dog breeds by WeRateDogs?
> 2. Which breed of dogs got the highest rating on average?
> 3. Which breed of dogs got the highest retweet and favorite counts on average?
> 4. Which stage of dogs got the highest rating, retweet and favorite counts?
> 5. Does the hashtags included impact retweet and favorite counts?
> 6. How does retweet and favorite counts spread based on the tweeted day of the week on average ?
> 7. Does the rating impact Retweet and Favorite Count?
> 8. Relationship between Retweet and Favorite Count


## Data Wrangling

### Packages to install
Can be installed via conda or pip,
- pandas
- NumPy
- requests
- tweepy
- json
- re
- string
- datetime
- matplotlib
- seaborn

### Gather
- Enhanced Twitter Archive data contains basic tweet data given by Udacity.
- Twitter API to gather retweet count and favorite count, which are notable columns, additionally details about hashtags used.
- Image Predictions File, containing the predicted breeds of dogs given by Udacity.
    
#### Limitations:
- Enhanced archive data contains basic tweet data (tweet ID, timestamp, text, etc.) of their tweets as they stood on August 1, 2017.
- Only original ratings (no retweets) that have images are considered.
       
### Assess
Assess data for:
- Quality: inconsistent data, inaccurate data, non-descriptive headers, missing values (NAN).
- Tidiness: issues with structure that prevent easy analysis. Tidy data requirements: Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table.

Types of assessment:
- Visual assessment
- Programmatic assessment (used Pandas)

### Clean
Programmatic data cleaning process:
- Define: convert the assessments into defined cleaning tasks.
- Code: convert those definitions to code and run that code.
- Test: test your dataset, visually or with code, to make sure cleaning operations worked.

#### Wrangle Report

> - [Wrangle Report](https://rpubs.com/keer707/759807)

#### Act Report

> - [What are the other factors that impact Re-tweet & Favorite Count?](https://rpubs.com/keer707/WeRateDogs_tweet-factor_blog)

> - [Which is a SUPER-WOW breed](https://rpubs.com/keer707/WeRateDogs_tweet-breed_blog)


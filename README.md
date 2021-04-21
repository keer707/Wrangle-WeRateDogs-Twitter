# WeRateDogs Twitter Analysis

Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations by investigating,
> 1. Which breed of dogs got the highest retweet counts and favorite counts?
> 2. Does the ratings impact retweet and favorite counts?
> 3. Whats are the top 5 underrated and overrated breeds of dogs? (being underrated means got the low scores from WeRateDogs but got high retweet counts and vice versa)?

## Data Wrangling
### Gather
    - Enhanced Twitter Archive data contains basic tweet data given by Udacity
    - Twitter API to gather retweet count and favorite count, which are notable columns
    - Image Predictions File, containing the predicted breeds of dogs given by Udacity
    
   #### Limitations:
       - Enhanced archive data contains basic tweet data (tweet ID, timestamp, text, etc.) of their tweets as they stood on August 1, 2017.
       
### Assess
Assess data for:
- Quality: inconsistent data, inaccurate data, non-descriptive headers, missing values (NAN)
- Tidiness: issues with structure that prevent easy analysis. Tidy data requirements: Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table.

Types of assessment:
- Visual assessment
- Programmatic assessment (used Pandas)

### Clean
Programmatic data cleaning process:
- Define: convert the assessments into defined cleaning tasks.
- Code: convert those definitions to code and run that code.
- Test: test your dataset, visually or with code, to make sure cleaning operations worked.

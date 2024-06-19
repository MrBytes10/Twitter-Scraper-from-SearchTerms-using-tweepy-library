# Twitter Scraper from a Search-Term

- This Python script uses the Tweepy library to search for tweets containing the phrase "latest python jobs" and stores the retrieved tweet data in a pandas DataFrame. The phrase can be changed to any phrase of your choice.

## Requirements

- Python 3.x
- Tweepy library
- Pandas library

## Usage

1. Install the required libraries:
2. Obtain your Twitter API credentials (consumer key, consumer secret, access token, and access token secret) from the Twitter Developer Portal.

3. Replace the placeholders (xxxxx) in the script with your actual API credentials.

4. Run the script:
   The script will search for the specified number of tweets (default is 150) containing the phrase "latest python jobs" and store the following information in a pandas DataFrame:

- User: The name of the user who posted the tweet
- Date Created: The timestamp when the tweet was created
- Number of Likes: The number of likes the tweet received
- Source of Tweet: The source application used to post the tweet
- Tweet: The text content of the tweet

The DataFrame will be printed to the console.

## Note

This script is for demonstration purposes only. It does not include error handling or additional functionalities such as saving the DataFrame to a file or further processing the data.

# (Data Visualization Data Wrangling (WeRateDogs))

## by (Olayiwola Idris)
## Dataset

> The visualize data is downloaded from WeRateDogsTwitter archive via Udacityexclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
- tweet_id (int64): unique identifier of a tweet timestamp:
- (datetime): UTC time when this Tweet was created :
- source (str): Device used to post the Tweet, like iPhone etc;
- text (str): The actual UTF-8 text of the status update;
- rating_numerator (int64) dog rating numerator; 
- rating_denominator (int64) dog rating denominator:
- Name: dog's name that appears frequently:
- Stages of dogs growth: doggo, floofer, pupper, puppo are kind of a dog growth stages:


## Summary of Findings

- **Most dogs names in the tweets**: Besides cases, where a letter 'a' and an article 'the' are provided, the most popular names are: Lucy, Charlie, Cooper, Oliver, Tucker, Penny, Winston, Lola, Sadie, Daisy Tolby, Bailey and Koda.<br>
- **Prediction algorithm of images** 
- golden_retriever with 150 tweets has the highest prediction in the first prediction algorithm followed by Labrador_retriever with 100 prediction, while Labrador_retriever is the highest for both second and third prediction algorithm respectively.
- **Prediction algorithm of images** 
- golden_retriever with 150 tweets has the highest prediction in the first prediction algorithm followed by Labrador_retriever with 100 prediction, while Labrador_retriever is the highest for both second and third prediction algorithm respectively.
The older the member who shares the bike for the entire trip, the longer the trip.
- **Sources of Tweet** 
-  93.7% of the tweet is from iPhone, followed by Vine, Twitter and Tweetdect with 4.3%, 1.5% and 0.5% repectively
- **Dog image prediction with rating_numerators and rating_denominators**
- The analysis shows that there are two dog image prediction tweet with numerators less than or equal to zero.also, further analysis shows that there is only one dog image prediction with rating_denominator less than or equal to zero.






## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
- Tweet rates  There are 2097 dogs' ratings in the dataset. The worst rate is 0, the best is 177.6 (177.6%). The ratings are not normally distributed, their distribution is right-skewed (long-tailed). Most of the ratings are below 150%, only 6 (0.29%) of them are above 150%. With Atticus being the most rated of all. 75% of ratings are 120% or below and only 25% or less are below 100%. Most dogs are very well rated, with the mean rating of 117%

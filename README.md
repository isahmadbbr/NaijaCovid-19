# NaijaCovid-19
Repository for Tweets about Covid-19 in Nigeria

We collected tweets from Twitter (now X) using the Twitter Academic API from 1st November 2020 to 30th June 2022. We collected tweets keywords relating to COVID-19 vaccination using keywords like vaccin*, moderna, pfizer, biontech, gamaleya, janssen, astrazeneca, astrazeneca, co- vishield, sinopharm, jab, microchips, infertility, tracking, magnet. The collection was restricted to only Tweets in Nigeria using location ID in the query. A total of 5200 tweets were collected. After removing URLS, tweets with less than three words, and tweets not in Latin characters, the tweets were reduced to 4320.
The tweets were then annotated by three (3) independent annotators using an annotation guideline. The classes for the annotation are: left=0pt, itemsep=0.5em
1. Positive: If the user’s tweet implies a positive attitude or opinion towards the vaccine (directly or indirectly). For example, the tweets contain positive words or some terms that imply a positive attitude towards COVID-19 vaccine like save lives, protect, apprecia- tive, thankful, excited, or optimistic.
2. Negative:Iftheuser’stweetimpliesanegativeattitude or opinion towards the vaccine. For example, the tweets contain negative words or some terms that imply a negative attitude towards COVID-19 vaccine like kill, harmful, tracker, chip, critical, angry, disap- pointed in, pessimistic, expressing sarcasm about, or mocking COVID-19 vaccine.
3. Neutral: If the user’s tweet does not imply any opin- ion.
4. Indeterminate: If the tweet is unintelligible.
After the annotation, majority vote was used to assign the final class of tweets in the following manner:
1. If all the annotators agree on the same class, then that class is automatically accepted.
2. If two annotators agree on either positive or negative and the last annotator classifies the tweet as neutral, then the tweet is assigned the majority class.
3. If two annotators classify a tweet as positive and the third annotator classifies it as negative, then the tweet is adjudicated by a new annotator. This is also the case if two annotators classify a tweet as negative and the third annotator classifies the tweet as positive.
4. If all the annotators label the tweet differently, the tweet is discarded.



Kindly cite our paper [here.](https://arxiv.org/pdf/2401.13133)


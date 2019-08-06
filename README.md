# Detecting-Depression-in-Tweets
Detecting Depression in Tweets using Baye's Theorem

Depression is a mental illness that is not taken seriously in some countries. I grew up in Banglore and I never got exposure to mental illness education at school or at home. As a kid, I felt sad sometimes and I knew about people getting sad because of difficult times, and even getting depressed but I never thought about people looking for professional help to overcome depression. Some people have been diagnosed with depression and don’t take medication to overcome it. They just continue their lives without medication and getting worse.

There are many experiences that can cause us depression, such losing a loved one, losing a job, getting a divorce and other tough situations can lead a person to feel blue, lonely and overwhelmed. It’s normal to get these feelings when we feel stressed. Everybody have experimented sadness at times. However, depression is very different from this. Depression is a psychiatric disorder that need to be addressed with medication.
Definition of Depression

All forms of depressive disorder experience some of the following symptoms:

    (a) reduced concentration and attention
    (b) reduced self-esteem and self-confidence
    (c) ideas of guilt and unworthiness (even in a mild type of episode)
    (d) bleak and pessimistic views of the future
    (e) ideas or acts of self-harm or suicide
    (f) disturbed sleep
    (g) diminished appetite


Social media platforms are becoming an integral part of people’s life. They reflect user’s personal life. People likes to share happiness, joy and sadness on social media. These platforms are used for researchers to identify the causes of depression and detect it.


In Machine Learning, there are many ways for sentiment analysis such: decision-based systems, Bayesian classifiers, support vector machine, neural networks and sample-based methods.

After reading some papers about using different Machine Learning and artificial intelligence techniques to detect depression on Social Media, I decided to apply sentiment analysis through a powerful theorem from probability theory called Baye’s Theorem. The model will be write in python and it will tell whether a given tweet is depressive or not.

Datasets

I generated a new dataset, combining part of the Sentiment140 (8,000 positive tweets), and another one for depressive tweets (2,314 tweets), with a total of 10,314 tweets. You can find this dataset in my repo.

Sentiment140

The Sentiment140 dataset contains 1,600,000 tweets extracted using the twitter API. The tweets have been annotated (0 = negative, 2 = neutral, 4 = positive) and they can be used to detect sentiment. It contains the following 6 fields:

    target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
    ids: The id of the tweet ( 2087)
    date: the date of the tweet (Sat May 16 23:58:44 UTC 2009)
    flag: The query (lyx). If there is no query, then this value is NO_QUERY.
    user: the user that tweeted (robotickilldozr)
    text: the text of the tweet (Lyx is cool)

You can find the dataset here:

https://www.kaggle.com/kazanova/sentiment140

For my experiment, I just took a sample of 8,000 tweets with polarity of 4, the positive ones.

Web scraping depressive Tweets with TWINT




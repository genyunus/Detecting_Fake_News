# Detecting_Fake_News
In this project I worked on one of the biggest problem, detecting the fake news with 52,000 article with %97 Accuracy.

I started with scraping news from NYT API and The Gueardian API to have data set labeled as real news, and dowloaded fakenews dataset from kaggle.com. At the end I scraped more than 200,000 articles. I wanted to be able to represent the real world in terms of the proportion of the real news and the fake news in my training. I had 12,000 fake news articles from kaggle.com so I dediced to have more real news, assuming there are more real news then fake in real world. Eventually I had 43,000 real news and 12,000 fakenews. 

Real and the fake news articles had to be in certain topics. I decided to have only from: "US News","Politics","Business" and "World", assuming that mostly fake news would be from these topics.

# What's here
Cleaning the data folder has the notebooks where I parse and clean the datasets.
Modeling and Grid Search folder has modeling and the grod search for the best perfomant model
Scraping data has notebooks to scrape data from NYT API and The Guardian API 

<img src="/Modeling_and_Grid_Search/All_Articles.jpg">

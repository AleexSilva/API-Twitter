# API - Twitter

### In this proyect, we 're going to extract a few tweets from Bill Gates's account and analyze them using sentiment analysis and visualize them with some plots.

![Bill Gates](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRecVPzcA0eYD64F8mX2ZalHKLsisCpxOZCZQ&usqp=CAU)

#### Motivation: Bill Gates is a co-founder of Microsoft, philanthropist and a reference. In recent months, he was singled out for having predicted the current COVID-19 pandemic. So I guess he tweeted a lot about COVID and could try to give positive messages to the world

### How the code works? (workflow)

- **Twitter Developer Account:**  First, I must create an specific type of account inside Twitter, to get the tokens that the API requires.
- **Extract:** To extract the data, I 'm using Tweepy. Tweepy is a function created in Python where I can get inside Twitter an extract some tweets, with an specific characteristics.
- **Import:** At the beginning, the data is in JSON (Java Script Object Notation) format. I transform it into a DataFrame.

- **Analysis:** To clear all the tweets, I create a functions that combines NLP (Natural Language Processing) and some replacements to model the data.
- **Predictive Model:** To analyse the polarity od the tweets, I use textbox.

## Results

1. Keywords: "COVID", "WORLD", "VACCINE".
2. Extended use of characters.
3. Big porcentage of positives tweets.
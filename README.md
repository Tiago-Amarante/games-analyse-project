# Games-analysis-project

The project was Files:

* API_request_hall_of_fame.ipynb - Get data from Open Critic API

* API_request_list_of_games.ipynb - Get data from Twitch based on Open Critic top games

* Games_analysis_project.ipynb - The main notebook

* hall_of_fame.csv - Open Critic dataset

* list_of_games.csv - Twitch data



## Motivation

Explore the Twitch API and Open Critic API to learn more about APIs and data preparation

This project discusses the influence of game reviews (Open Critic Score) in their popularity (Twitch data). Does the top OpenCritic games implies their popularity, how much?

## Main libs used in this project

* requests
* dmatrices from patsy
* pandas

## The study conclusion 

Based on the R-squared: 0.163 we conclude that just 16.3% of TopCriticScore were explained by Twitch features.

It means that a good professional review score doesn't mean that the game will be popular. Probably exists a lot of variables that rule the popularity of a game, let's take a look at the Top Twitch games and Top Open Critic games to get some insights on what they have in common.

In Twitch's top games, there is a strong common trait: They're all COMPETITIVE games. My main hypothesis is that people want to reach their limits, be the best or watch the bests teaching. These games instigate you to be better, to win off/with your friends. And that's why they're so popular, we're fighting each other since we exist, but now we do this safely in our gamer's setups!

On the other hand, the top Open Critic Games have another two comum patterns: they're from classic franchises (Super Mario, Zelda, God of War) or they are something disruptive (Hades, Red Dead Redemption 2). My Hypothesis is that these franchises have a time-proven 'cake recipe', they're testing what's worth and what's not over the years. They know the reviewer's taste, and they have resources to run MVPs before the launch. And no less importantly they have an emotional impact, this is a subjective and non-technical criteria, but we have great expectation of the classics and I believe this fact impact the Score.

Finally, I could demonstrate driven by data and limited by our initial assumptions, that reviews have little impact on game popularity. And I've created some Hypotheses to explain why this happens, but this hypothesis still needs to be proven.

Any suggestions, mail me at: tadbc1@gmail.com

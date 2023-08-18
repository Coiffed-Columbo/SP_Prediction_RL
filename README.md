# Stock Price Prediction using Reinforcement Learning
# Introduction
Creating a lucrative automated stock trading strategy holds immense significance for investment firms and hedge funds. This approach aims to enhance capital utilization and optimize investment outcomes, including projected returns. Achieving maximum returns involves evaluating potential gains against associated risks. Nevertheless, developing a profitable strategy within the intricate and ever-changing stock market environment presents a formidable challenge.

In this undertaking, we aim to leverage a Deep Reinforcement Learning Trading Strategy that incorporates a trio of actor-critic based algorithms: Proximal Policy Optimization (PPO), Advantage Actor-Critic (A2C), and Deep Deterministic Policy Gradient (DDPG). By amalgamating the most advantageous aspects of these three algorithms, our approach is adept at flexibly adapting to diverse market conditions.

# Data
We focus on monitoring Dow Jones 30 stocks as of January 1, 2016, utilizing historical daily data from January 1, 2009, to May 8, 2020, for agent training and performance evaluation. Our dataset is sourced from the Compustat database accessed through Wharton Research Data Services (WRDS).

The dataset is divided as illustrated below. Data spanning from January 1, 2009, to December 31, 2014, is utilized for training purposes. The subset spanning from October 1, 2015, to December 31, 2015, is dedicated to validation and parameter fine-tuning. Finally, we assess our agent's effectiveness on trading data, an unseen out-of-sample dataset from January 1, 2016, to May 8, 2020. To maximize the utilization of trading data, we continue training the agent during the trading phase, enhancing its adaptability to evolving market dynamics.

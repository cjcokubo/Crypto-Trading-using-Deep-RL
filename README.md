# Crypto-Trading-using-Deep-RL
For DS-UA 301: Advanced Topics in ML &amp; Deep Learning

### Description of Project:
Our main objective for this project is to build a robust algorithmic trading model that can accurately maximize profit despite volatile market conditions. We will reference features from other deep learning trading systems that we deem necessary to implement a robust model. Our main focus when developing the model will be accuracy in predicting price and to maximize profit in the form of calculating reward using Deep Q-Learning (DQN). Our model will try to find a correlation between training volume and improved profit and loss.

### Description of code structure

![Architecture](Deep-reinforcement-learning-structure-for-cryptocurrency-trading.png)

The Process:
1. Data Cleaning/Preparation: Importing, Normalization, Feature Extraction
2. Creating the Trading Env: Defining actions, Computing rewards, Updating Values
3. Building a Sequential Model 
5. Performing RL using DQNA

### Commands to execute the code
'''
if __name__ == '__main__':
  main()
'''

### Results and Observations

Model executed trades from September 23 2021 - December 5, 2021
| Buy       | Sell      | Hold       | Total       |
|-----------|-----------|------------|-------------|
| 524 (15%) | 523 (15%) | 2433 (70%) | 3480 (100%) |

* 248 Positive outcome trades <-> 275 Negative outcome trades
* Model is inaccurate at timing trades
* $10,000 starting balance; $173.56 Profit, (1.7% Increase)
* 85.49%  Increase in the price of BTC during the same time period


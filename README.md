# Bitcoin Auto-trader: Final Project for Reinforcement Learning, Dr. Doina Precup

<p align="center">
  <img src="BTC.png?raw=true" alt="Historical Bitcoin to USD" title="Historical Bitcoin to USD" width=600 />
</p>

  * **Author: AhmadReza GodarzvandChegini**

  * **[Colab's runtime](https://drive.google.com/file/d/1P8mhR8AsZ9Ol3bz1gbar_P0VHDfQm_-2/view?usp=sharing)**


The curated database contains 172137 candlestick tuples whose entries come from opening price, closing price, minimum price, and maximum price during 15 minute intervals.

In this work, the agent's interaction with the environment has been modeled as a tabular MDP with buy, sell, and hold actions, and the environment is taken to be a basic simulation of Bitcoin's exchange market. The historical traded price of Bitcoin was collected from Bitfinex's historical data until April 18, 2018. Trading fees in Bitfinex is approximately 0.2 percent of each transaction.

For more information, please refer to the report [here](rltrading-report.pdf).

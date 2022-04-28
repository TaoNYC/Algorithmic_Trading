# Algorithmic_Trading

 Python application serving as a quick and dirty prototype to use quantitive security analysis & Monte Carlo simulation to identify potentially profitable stock trades and place order in Alpaca Paper Trading Account directly via API.

In the future, more parts can be gradually added to this prototype such as: connecting with Database/SQL, using AI / machine-learning to identify potentially profitable trades, expanding to crypto & futures/options trading etc

The ultimate goal is to build a paper trading verified algorithmic trading application for realtime trading (for example connecting with Robin-hood live trading act)



---

## Technologies

This project leverages python 3.7 +, fire, questionary, pathlib


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install fire
  pip install questionary

```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: run paper_trading_with_alpaca_api.ipynb
```python
python paper_trading_with_alpaca_api.ipynb
```
Step 2: use api key and secret key from alpaca to get account info (account cash balance, purchasing power etc)

<img width="958" alt="image" src="https://user-images.githubusercontent.com/99616004/165805566-6c670ad2-bfd3-49f9-b0a3-4ae77800f38c.png">

Step 3: place an order to buy AAPL stock 10 shares, at market price, gtc

<img width="1033" alt="image" src="https://user-images.githubusercontent.com/99616004/165805684-32a33fea-708b-4cda-b3df-df1429a41fa6.png">

Step 4 go to alpaca account to check the order being placed
<img width="1027" alt="image" src="https://user-images.githubusercontent.com/99616004/165812762-57fa9501-0c7b-4e35-b32e-ed50c8792e10.png">

## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp

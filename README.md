# Algorithmic_Trading

This is a Python application serving as a quick and dirty prototype to use quantative security analysis & Monte Carlo simuliation to identify potentally profitble stock trades and place order in Alpaca Paper Trading Account direclty via API.

In the future, more parts can be gradually added to this prototype such as: connecting with Database/SQL, using AI / machinelearning to identify potentially profitable trades, expanding to crypto & futures/options trading etc

The ultimate goal is to build a paper trading verified algorithmic trading application for realtime trading (for exmaple connecting with Robinhood live trading acct)



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

<img width="942" alt="image" src="https://user-images.githubusercontent.com/99616004/165792212-b39d47a9-a32b-4b07-bd8b-6218ffd01074.png">

Step 3: user is prompted to type in info such as Cretit Score, income, etc

<img width="389" alt="image" src="https://user-images.githubusercontent.com/99616004/162579016-d2a32538-1d70-4b9b-b078-06f4c45fb223.png">

Step 4: 

  a. if no loan is found, system exit

  <img width="309" alt="Screen Shot 2022-04-09 at 10 24 51 AM" src="https://user-images.githubusercontent.com/99616004/162579077-da826a02-7f94-4e11-b2a0-e4bc8f5458d8.png">

  b. if qualifying loans are found, display number of loan found

  <img width="302" alt="image" src="https://user-images.githubusercontent.com/99616004/162579161-3dcca13d-3406-4fcc-a091-3313b6229035.png">

Step 5: user is asked if he/she wants to save the output to csv file

  a. if user choose not to save file, exit with msg below

  <img width="352" alt="image" src="https://user-images.githubusercontent.com/99616004/162579247-441a2c85-4719-4b5c-99a1-f50e150635b3.png">

  a. if user choose to save file, user is promped to input oupput file path

  <img width="524" alt="image" src="https://user-images.githubusercontent.com/99616004/162579300-1e83cfdc-b1c9-4990-a51a-44d51f6dd171.png">



Step 6: finally you should see beow output in the csv file.



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp

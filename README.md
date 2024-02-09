# C$50 Finance Web App

![Static Badge](https://img.shields.io/badge/Flask-%233EAABF?logo=flask)
![Static Badge](https://img.shields.io/badge/Python-blue?logo=Python&logoColor=yellow)
![Static Badge](https://img.shields.io/badge/HTML-orangered?logo=html5&logoColor=white)
![Static Badge](https://img.shields.io/badge/CSS-blue?logo=CSS3&logoColor=white)
![Static Badge](https://img.shields.io/badge/Bootstrap-purple?logo=Bootstrap&logoColor=white)

<details>
<summary>Table of Contents</summary>

-   [C$50 Finance Web App](#c50-finance-web-app)
    -   [Demo Video](#demo-video)
    -   [Description:](#description)
    -   [Motivations](#motivations)
    -   [🚀 Quick Start](#-quick-start)
        -   [Open terminal of preference](#open-terminal-of-preference)
        -   [Clone the repo](#clone-the-repo)
        -   [Navigate to repo](#navigate-to-repo)
        -   [Install requirements](#install-requirements)
        -   [Start the server](#start-the-server)
            -   [Example message](#example-message)
        -   [Navigate to Register](#navigate-to-register)
        -   [Create an account](#create-an-account)
        -   [Portfolio Page](#portfolio-page)
    -   [⚙️ Usage](#️-usage)
        -   [Portfolio/CS50 Finance](#portfoliocs50-finance)
        -   [Quote](#quote)
            -   [Example Symbols](#example-symbols)
        -   [Buy](#buy)
            -   [Example](#example)
        -   [Sell](#sell)
            -   [Example](#example-1)
        -   [History](#history)
        -   [Account](#account)
        -   [Log Out](#log-out)

</details>

## [Demo Video](https://youtu.be/TAyl8xs0H4Q)

## Description:

This is a finance app created using the Flask framework for Python. I worked on it while taking CS50x. It is a simple web app that allows you to create or log into an account. You can then look up a real-world stock price using Yahoo Finance API. In the web app, you can also buy, sell, and track your stock. All the information is stored in a SQL database and passwords are encrypted. None of the money and transactions are real it is a simple demonstration. The majority of the code was written by myself but parts of it were written by the CS50 team at Harvard.

> [!IMPORTANT]
> This isn't a live web app, none of the money or transactions are real, this project is a demonstration of my skills and educational purposes.

## Motivations

The main motivation for this project was because it was an assignment for CS50. My other motivation behind it was to be able to improve my skills by making a functional backend. I also wanted to make something practical to mirror real-world use cases.

## 🚀 Quick Start

> [!IMPORTANT]
> You will need [Python](https://www.python.org/) 3.11+ to run this program
> <sub>_3.10 and bellow may work but is untested_</sub>
>
> <sub>will use bash to demonstrate commands but you can use other terminals as well</sub>

### Open terminal of preference

Open a terminal you would like to use i.e. Bash, PowerShell, etc...

### Clone the repo

```bash
$ git clone https://github.com/DomGiarrusso/CS50-Finace-Web-App.git
```

### Navigate to repo

```bash
$ cd path/to/repo/...
```

### Install requirements

Run this command to install the necessary requirements for the project.

```bash
$ pip install -r requirements.txt
```

### Start the server

```bash
$ flask run
```

it should then give you a http link using an IP and Port number

#### Example message

```bash
* Running on http://123.0.0.1:5000
```

> [!NOTE]
> your link will look different than this

### Navigate to Register

Your screen should look like this when you open up the link.

![LoginScreen](/assets/login_screen.jpg)

In the top right click on `Register`.

### Create an account

> [!NOTE]
> Since this is a copy of a repo none of the data you give will be shared with me or any other person.

Fill out the 3 fields given, `Username`, `Password`, and `Confirm Passowrd`. Then click on Register

### Portfolio Page

Now you are in and should see your portfolio page.
From here you can naviagte throughout the site and use it.

> [!TIP]
> For how to use the site go further below

## ⚙️ Usage

This web app allows you to view your portfolio, get a quote on a stock, Buy a stock, Sell a stock, and view transaction history. You addionally have options to access account and logout.

### Portfolio/CS50 Finance

This page is the first page you should see after logging in or registering.

In this page you will find your portfolio showing how much money you have and also the different stocks you "own".

If you ever need to get back to your portfolio page click the `C$50 Finance` on the navbar.

### Quote

To navigate to the quote page click on `Quote` on the navbar.

On this page you are given a field to enter in a stock symbol. Once you enter in the symbol it will give you a quote on the price of that stock.

#### Example Symbols

-   For Google enter in `GOOGL`
-   For Apple enter in `AAPL`
-   For Microsoftr enter in `MSFT`

> [!NOTE]
> The price given is for a single share

### Buy

To navigate to the buy page click on `Buy` on the navbar.

Here you have 2 fields you need to enter in.

1. Symbol
    - Enter in the symbol of the stock you want to buy.
2. Shares
    - Enter in how many shares of the stock you want to buy

Then click `Buy`. You just bought some shares.

Once you buy it takes you back to your portfolio page where you can view the shares you just bought.

#### Example

![Buy_Example](/assets/buy_example.jpg)

### Sell

To navigate to the sell page click on `Sell` on the navbar.

Here you have 2 fields to fill out.

1. Symbol
    - Select the symbol of the stock you want to sell
2. Shares
    - Enter in the number of shares you want to sell

Then click `Sell`. You just sold some shares.

Once you sell it takes you back to your portfolio page where you can view the updated price of your portfolio.

#### Example

![Sell_Example](/assets/sell_example.jpg)

### History

To navigate to the history page click on `History` on the navbar.

Here you can view the history of the shares you bought and sold.

![History_Example](/assets/history_example.jpg)

### Account

To navigate to the account page click on `Account` on the navbar, found on the right.

On this page you can update your password to your account.

To change your password you must.

1. Enter in `Current Password` to your account.
2. Enter in a `New Password`.
3. Enter in the new password into `Confirm password` to confirm it.

Click `Change`. Then Ta-da! you updated your password.

### Log Out

To logout of your account click `Log Out` on the navbar, found on the right.

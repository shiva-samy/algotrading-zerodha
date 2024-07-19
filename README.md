# zerodha-algo-trading
Make sure to install these libraries beforehand in python:
1)pandas
2)kiteconnect
3)Flask

Automated Trading Project using Zerodha API (KiteConnect) using Python and HTML/CSS

Instructions to run the code:
Make sure to know the following details:
a)API Key
b)API secret
c)username
d)password
e)totp (sent to zerodha or any other TOTP operator you use)

initially, the page will ask you to enter you "API key" and "API secret". to get them, the instruction is added on to the code

next, the page will redirect to a page, where it will show you to login to zerodha, after logging in it will ask you to enter the request token link (which is your redirect ur that will come after successful login)

then:
1)start algo trading will start buy and sell automatically based on buy and sell signals from the code. to stop algo trading, click the button "stop algo trading" to stop trading. or the code will automatically stop trading when the algo is not trading.

2)backtest: backtest will redirect you to a page where backtest. initially before backtesting, make sure you had run the "fetch data" code, and have sufficient amount of data fetched in it.

the fetch data interface will ask for the necessary details for fetching. after fetching, the code will redirect to "backtest" page, after which when you go to the parent folder, in the data folder, you can see a csv called "fetched_data" in which ohlc details will be stored then you can go backtest, give necessary details, and when you start the backtest, after successful backtest, in the parent directory, a csv called "backtest_result" will be saved in which the backtest of each buy and sell, and net profit, profit percent and other details will be saved

We did this project as a part of our lab work, as well internship under a company so, i'll provide links for the documents that are required to know more about this project.

Presentation: https://docs.google.com/presentation/d/18IeisaVOYi2m9Zo08vVQEMce8bF8h4O7/edit?usp=drive_link&ouid=103828244439120671270&rtpof=true&sd=true

Certification for completion of the project: https://drive.google.com/file/d/1f80lgSCMV_5I2hHOiHjluhj8qofICm_L/view?usp=drive_link

Project Report: https://drive.google.com/file/d/1lvh_Al2eAzgGgZnkMFbhKZmO73g2Z_6f/view?usp=drive_link

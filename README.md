# Challenge-14
# Algorithmic Trading Report

The purpose of this report is to evaluate different algorithmic trading strategies. 

Each beneficial parameter change will be included into further model tests with the hope of building the most successful model possible. 

## Baseline Evaluation:

The trading model initially performed well but ultimately finished down over 20% compared to actual returns approaching +40%.

<img width="295" alt="Baseline" src="https://user-images.githubusercontent.com/86026996/141701511-ee5e09db-aaf6-487c-8994-1a7858b9f653.png">

## Adjusted Training Dataset Size:

By changing the training period from three months, to nine months, the trading model did not significantly change. 


<img width="359" alt="ChangeTrainDate" src="https://user-images.githubusercontent.com/86026996/141702598-a6a9b404-128a-42b4-9dfe-51ce043ad0fd.png">


## Adjusted SMA Windows:

I attempted to increase the SMA window. The base model had short_window = 4 and long_window = 100.

By widened the window with short_window = 10 and long_window = 150, the model's performance seemed to improve although was still negative.

<img width="324" alt="SMAwindowAdjust" src="https://user-images.githubusercontent.com/86026996/141703313-deaccaf3-5fa9-4473-bea3-cacd37a1cc24.png">


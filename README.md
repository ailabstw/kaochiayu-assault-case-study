# Atypical Online Coincidental Study for Kao Chia-yu (高嘉瑜) Assault Case
The Kao Chia-yu assault case (the case) continues to snowball on mainstream media. Number of PTT accounts (the suspicious accounts), including AirJordan, CrazyWinnie, booksil, berleolion, etc., are continuously accused by media of being used for cyber-army to shift public opinion in this case.
Right before the case outbreak, Taiwan AI Labs published an open-source algorithm [1] on Nov 18th 2011 to explore atypical online coincidental Behavior based on PTT.

The research team executed the same algorithm against the discussion related to Kao Chia-Yu and the result is uploaded to GitHub.
In this case study the collaborative behaviors threshold is set with phi coef > .2 (a collaborative behavior indicator calculating the in-post responses and repost among accounts).

According to the result, the suspicious accounts being accused by media are not listed in the accounts with atypical online coincidental behaviors.
At the same time, 5 groups of accounts can be observed.

[1] ["Exploring Atypical Online Coincidental Behavior on PTT"](https://ailabs.tw/human-interaction/exploring-atypical-online-coincidental-behavior-on-ptt/)

This repository contains the following documents:
1. dataset: 
    - All posts and comments along with other relevant information related to "高嘉瑜" on PTT from 11/1-12/5.
    - Specific group posts and comments along with other relevant information related to "高嘉瑜" on PTT from 11/1-12/5.
2. figures:
    -  A boxplot on the distribution of the number of unique users participated in the Kao-Chia Yu assault case for the coincidental groups identified.
    -  The comments and the word clouds of the five groups' mentioned in the report.

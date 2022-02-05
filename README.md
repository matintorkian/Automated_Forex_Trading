# Automated_Forex_Trading
This repository is to start your way to writing forex EAs and automate your trades.
The first tool that you need for trading, is trading platform. Even if you want to develop an algorithm for automatic trading, you'll need to have access to the data. In my experience, the best way to develop an algorithm for autamatic trading in by using [MetaTrader](https://www.metatrader4.com/en) which is a free trading platform and already provides access to data for every currency pairs and makes it much more easier to develop your own trading algorithm. Algorithms for autamatic trading are called [Expert-Advisor](https://www.metatrader4.com/en/trading-platform/help/autotrading/experts) in MetaTrader platforms.


## MetaTrader installation on Linux 
Installing MetaTrader is not a problem in windows. Actually your brockers usually provide all versions of MetaTrader for windows. Otherwise, installing MetaTrader on any Unix_like operating system might be a challenge. Some people have both windows and linux on their system and go back and forth in between operatig systems but that is not easy and you can't always do that. I recommend installation by [wine](https://en.wikipedia.org/wiki/Wine_(software)) which provides a virtuall windows environment on your Linux. 

#### Finding files in wine
As mentioned, wine created a virtuall windows like environment on your Linux or andy other Unix_like operating system you're using. For creating Expert-Advisors, you usually need to find, transfer and create files in the directories that wine created on your system and MetaTrader also can see them. To do that, go to home and search for `.wine` directory. This is a hidden directory so you might nedd to press `ctrl+h` to see it. Your C derive is now named by `drive_C` in this directory. You should use these addresses to include your Expert-Advisors files and destination. 

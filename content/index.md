---
title: "My First Post"
date: 2019-03-26T08:47:11+01:00
---

# LOVE FOR RYAN
We need to run the auto-love-generator on your account, example below:

![example](images/example.gif)
<!-- {{< image src="./images/example.gif" title="Photo by Ales Krivec on Unsplash" >}} -->

### First we need to download love generator to run:
`git clone https://github.com/rgoshen/tinder_swipe_bot`
### Next we download some of its prerequsits
 - download chromedriver, unzip, move to `/usr/local/bin` (mac os / linux)
 - `pip install selenium`
### Now open main.py and replace
```
FB_EMAIL = "YOUREMAILHERE"
FB_PASSWORD = "YOUR PASSWORD HERE"

chrome_driver_path = "PATH TO CHROME DRIVER" ### e.g. /Users/zhen/Downloads/chromedriver
```
### Run the file
`python ./main.py`
# Hacker Pizza Order System - cuHacking 2019
* InGenius CU Hacking Challenge
* By Songmi Wu, Yichen Lian ,Keith Huang, Yiwei Zhang

## Amazon Connect Streams
* Integrate the Amazon connect streaming api
* The api can be found here [here](https://github.com/aws/amazon-connect-streams)
* [Project page on DevPost](https://devpost.com/software/cuhackingamazonconnect)

## Part1 Pizza Phone Call Ordering System for customers
![](https://github.com/zywkloo/CuHackingAmazonConnect/raw/master/CallSystemScreenShot.png)
* Please visit https://ottawa.recipes , then call +1 866-846-5640
* Supporting 3 languages including English, French and Chinese.
* The website will display a phone UI, and a text area.
* All requests connected to the Amazon instance have to be on HTTPS. You should unblock all popups and get an HTTPS certificate.
* This is an HTTPS website, hosted on vultr server 1. The repository is here.

## Part2 Pizza Phone Call Ordering Monitor for restaurants
![](https://github.com/zywkloo/CuHackingAmazonConnect/raw/master/CallMoniterScreenshot.jpeg)
* Please visit http://hacker-pizza.herokuapp.com , then call +1 877-373-3618. 
* The website will display the result of your order in real time, only for demoing the functionality (For now just supporting small pizza or small salad).
* This is an HTTP web application using Socket.IO, hosted on Heroku server 2. The part 2 repository is [here](https://github.com/CU-Hack19-RaspPi/hacker-pizza-second-screen).

## Tips:
* You may not need to clone and deploy this repo locally or anywhere else, since most of the logic and source codes are stored on Amazon Lambda, and Amazon Connect. However, we have no approaches to make these public out of the AWS ecosystem for now.
* Supported browsers: Latest desktop versions of Chrome or Firefox. Mobile versions are not supported.

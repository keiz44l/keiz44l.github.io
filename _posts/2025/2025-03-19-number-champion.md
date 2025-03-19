---
layout: post
title:	"Number Champion"
date:	2025-03-19 03:00:00
categories:
    - ctf
tags:
    - WEB

permalink: /number-champ/
---



# Number Champion

![Screenshot]({{ site.baseurl }}images/utctf/numberchamp/1.png)

One of the web challenges, called "Number Champion, was asking us to retrieve the exact position of the best user of the game. 
The website was quite simple : 
![Screenshot]({{ site.baseurl }}images/utctf/numberchamp/2.png)


You get a new nickname when you reload the page, with a base elo, and you can find a match with someone else, based on your current elo. The goal is to find a bigger number than your opponent to win the game. Of course, the game was made for us to find a way to cheat, since we couldn't win against anybody. I looked at the request, and saw that when you find a match, you can see the uuid of the opponent and his elo, and also the distance between yourself (defined by a latitude and a longitude in the request parameters) and the opponent. 
![Screenshot]({{ site.baseurl }}images/utctf/numberchamp/3.png)


My idea was then to see if my opponent had a bigger elo, and steal his uuid, to find a new match as somebody else with higher elo. I did that until reaching approximately 3000 elo, making me do matches against geopy. 
![Screenshot]({{ site.baseurl }}images/utctf/numberchamp/5.png)

I then tried different latitudes and longitude to narrow the location, until I got close enough (all manually, I was lazy to make a script). After half an hour of narrowing distances, I finally got the place, a starbucks in Colombus.

![Screenshot]({{ site.baseurl }}images/utctf/numberchamp/6.png)
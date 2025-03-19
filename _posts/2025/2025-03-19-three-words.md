---
layout: post
title:	"Three Words 1 & 3"
date:	2025-03-19 12:00:00
categories:
    - ctf
tags:
    - OSINT
    - CTF
    - UTCTF
    - GEOINT
permalink: /three-words/
---

![Screenshot]({{ site.baseurl }}images/utctf/three-words/three-words-1.png)

In 2025 UTCTF, there were 3 OSINT/GEOINT challenges, all three similar. The goal, basically, was to retrieve the exact position of three images, and find "three words" to describe it.
# Three Words 1
The first image was the following : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/three-words-1-img.png)

Finding the approximate localisation was quite easy, since you can see in the bottom "Hackerman", and knowing the CTF was made by students of the Austin Texas University, searching in google "hackerman University of Texas" was enough to find a building named after Norman Hackerman : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/three-words-1-building1.png)

To ensure of the position, google maps wasn't enough, because there is few covering of the area, and it didn't look like the picture. 
I then decided to use Bing Maps, and it had more coverage of that area. I was able to see it fits because of the panel with Norman Hackerman written, the stop sign, and the building, allowing me to get a good estimate of the picture position, where I draw a red cross : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/bing.png)

Then, to fit the flag, I searched what could be those three words online, and found a website called "https://what3words.com/", that gives three words for squares in the whole world map. I narrowed the position with the informations I got earlier, and found the three words : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/3words.png)

# Three Words 3
The third image was the following : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/three-words-3-img.png)

The image got me one big clue, the K panel in the background, indicating permit based parkings, that I saw earlier in the Austin Texas University. The wiener car didn't help me in this case, since I got the position by googling just a bit next to one entry of the university, and got to see the panel. Knowing it's a unique one, since it's not even in the University Documentation, I assumed it was here, and tried to fit the position with the picture
![Screenshot]({{ site.baseurl }}images/utctf/three-words/3words-3-google.png)

I narrowed the position with the informations I got earlier, and with this thing next to one tree : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/3words3tree.png)
And found the three words : 
![Screenshot]({{ site.baseurl }}images/utctf/three-words/3words3.png)



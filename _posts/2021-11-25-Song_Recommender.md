---
title: "Ironhack Spotify Song Recommender Project"
mathjax: false
layout: post
categories: 
 -github
 -website
 -health
---

![Recommender](https://github.com/edbe777/Completed-Labs/raw/main/Week_6/Day_5/images/prototype2.0.png)

This project is a Spotify song recommender.

I made a pipeline to:
Ask the user to input a song and artist, then check whether or not the song is in the Top 100 Songs. 
If the song is in the Top 100 Songs list, then return a random song from that list.

If the song is not in the Top 100 Songs list:
Collect the audio features from the Spotify API. Send the Spotify audio features of the submitted song to the clustering model. 
Compare song to closest cluster, then pick a random song from the closest cluster. 
Finally, return the recommended song back to the user.

 
![Prototype](https://github.com/edbe777/Completed-Labs/raw/main/Week_6/Day_5/images/prototype2.1.png)


Go to the [GitHub Repository](https://github.com/edbe777/Completed-Labs/tree/main/Week_6/Day_5){:target="_blank"}

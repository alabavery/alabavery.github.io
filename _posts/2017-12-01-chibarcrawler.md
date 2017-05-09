---
layout: post
title: A Website for Tracking Shows in Chicago
---
I'm making [chibarcrawler.com](www.chibarcrawler.com).  Here's why: Say you want to see some live music this weekend.  You don't know of a particular band playing, but you know you want to go to a smaller venue (because you know it's can be more fun, it's cheaper, and it's [less of a hassle](https://youtu.be/DMcmLPIZVfA)).  You'll likely have to go one-by-one to each of the venues' websites and see what artist is playing, then switch to Spotify and see if you like that artist's music.  No more!

Although there is still some front-end work and data aggregation improvement to be done, the site is up and running.  It's based on Flask, a Python web framework and gets its data from the Songkick and Spotify APIs, making regular updates through use of [RabbitMQ](http://www.rabbitmq.com/).  You can see the code for the frontend [here](https://github.com/alabavery/BarCrawler) and for the backend [here](https://github.com/alabavery/BarCrawler).

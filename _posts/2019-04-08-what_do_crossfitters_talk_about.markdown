---
layout: post
title:      "What do crossfitters talk about?"
date:       2019-04-08 15:07:58 +0000
permalink:  what_do_crossfitters_talk_about
---


CrossFit. That's it. We talk about CrossFit workouts, athletes, clothes, our scores...basically anything that has to do with CrossFit. 

So naturally I did my CLI Project on CrossFit shoes. Now there are many different types of shoes you can wear for CrossFit (don't get me started), however I just stuck with Reebok. My first level of scraping was to take the names of the shoes and put them in a list for the user to choose from. Once they chose a specific shoe then they would receive the price and the description of said shoe (2nd level).  

The the scraping videos that Corinna made proved to be very helpful. I did get caught on a couple of issues as originally I wanted to spit out the colors of the shoes that the user would chose. I wasn't able to successfully find the correct selectors for these no matter how hard I tried or how many I entered in (and trust me there were many). 

I decided then to put in the description of the shoe. At first I thought I successfully scraped it to find that I was pulling the same description for each shoe. I went back and revamped my selectors for the shoe description and was able to then pull the correct text for the individual shoe. 

Probably the most confusing issue that I had was my if/else statement in my menu method. When the user was to choose a shoe, to get more information about if they were to enter a word the program would still return a shoe and not the error of an invalid entry. I tried many different statements and ways that I (and Google) knew how. I asked some of my classmates and it took four of us to figure it out. At last the user was able to put in the correct number and get the correct shoe price and description. 

I then added some color to the text and there you have it! My first project done! So excited to see what is next! :)

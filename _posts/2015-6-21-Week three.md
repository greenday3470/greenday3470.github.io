---
layout: post
title: Week 3
---

This week was pretty busy, a project called netflix was annouced last week and it was dued this Tuesday. It was an interesting project to work on with a partner. Simply saying, design a program that will predict user's rating on a movie based on the rating data we have.

The goal is straightforward but rather hard to implement, because there are different "cache" available for us to utilize, such as the average ratings of a movie from all the users, or average ratings of a user that he/she ever gave on a movie, etc. 
I think the another challenge was just syntax, to write a program will fetch the cache, fetch the incoming file, then parse the information based on the input to collect corresponding data from chache and to compute our predicted rating that user might give. I would say the core of this project is actaully find a way to design a proper prediciton formula, I tried to use the average user rating and the average of movie rating, sum them up then average them up evenly. Apparently, I didn't consider not all rating the user gave is equal ammount, and now all ratings of the movies are the same as well, so basic divied in half was a biased formula to come up first. Honestly, I spent nearly two hours tried to devise this proper way of average number to make our prediciton resulted less than one of RMSE(Root-mean-square deviation). Luckily, at the end I was able to make it to 0.97, and that was 5 am in the morning at the CS lab. 

There is a test next Monday, I'm quite nervous, I guess it's because the materials professor can ask could be anything form the lectures. I tried my best to review my class notes and the in class quizzes he gave. Most importantly, after I review a concept, I'm coding each of them or rather test my memory to implement a similar code and run in on my computer. I think this way I can understand the concept even better, not just theoratically but practically. 

Tip of the week: get to know your classmates and ask questions
I think code by yourself is a good thing, pair programming is even better, but if both you and your partner don't know about the question or have trouble to figure out the problem. I recommend look around(especially in the computer lab), approach to your classmates and just simply ask how they conquered the problem. This way, by communicating other programmers you can figure out where your mistakes might be and sometimes your classmates can propose a completely new idea to refresh your mind. I even found out some classmates taught me different syntax to improve my coding skills. As a long run, this habbit will be a great investment

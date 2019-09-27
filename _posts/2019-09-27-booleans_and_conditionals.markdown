---
layout: post
title:      "Booleans and Conditionals"
date:       2019-09-27 11:49:10 +0000
permalink:  booleans_and_conditionals
---


As humans we make decisions every day, like what we will eat for lunch or weather to wear a jacket outside. When we make these decisions we consider many conditions of the world around us, like if there is turkey or ham in the fridge for the lunch decision or the outside weather for the jacket decision.

Computers are able to make such decisions like this using Boolean expressions (true/false) inside conditionals (of/else). Thanks to conditionals, programs can respond differently based on different inputs and parameters.

For a simple example we can write a program that will help us to decide what to wear outside each day. If the temperature is at or below freezing the program should instruct us to wear a snow jacket. We would program this using an if statement:

if (temperature < 32) {
  print("You need a snow jacket!")
}

The condition (temperature) is a Boolean expression. Booleans are only every able to hold a true or false statement. 

In our if statement above we used a comparison operator (<) to determine whether the temperature is above or below 32 degrees. There are many comparison operators that can be used to determine different relationships between values. 

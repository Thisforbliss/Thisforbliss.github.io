---
layout: post
title:      "Understanding how to Loop!"
date:       2020-08-09 04:31:31 +0000
permalink:  understanding_how_to_loop
---

Insanity is doing the same thing over and over expecting a different result otherwise called looping... Hahaha. We'll even though they share similar traits, in this blog we'll se how they could be helpful. Lets say wanted to leave a message to your neighbor via code to to feed your dog at 10:00 p.m.. We could write a method to display while time != 10:00pm puts "Don't feed the dog." unless its 10pm. So a while loop takes in a condtional (10:00pm) , that being a certain argument of time to say to change the value outputted("Feed the Dog").

Another Loop in the for loop, this says to loop through a certain pbject x amount of times. Lets say you wanted a created a method called merryChristMas and want to display a string of "Merry X Mas" to the user 5 times. This is possible in a for loop. 

```var xmas =  ["Merry X Mas", "Merry X Mas","Merry X Mas","Merry X Mas" ,"Merry X Mas"];
var text = "";
var i;
for (i = 0; i < xmas.length; i++) {
  text += xmas[i] + "<br>";
}```
  
This code would only print Merry Xmas to the length of the array which is only 5 times. It comes in handy to have loops so you wouldn't have to retype it over and over. Let the code do all the heavy lifting! I hope this helps!


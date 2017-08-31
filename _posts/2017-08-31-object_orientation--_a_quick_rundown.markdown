---
layout: post
title:  "Object Orientation-- A Quick Rundown"
date:   2017-08-31 15:16:36 +0000
---


As I started writing this post I had one goal in mind, to actually write a post about something technical that someone who knows nothing about coding could kind of understand and possibly appreciate.

First, let's check our background knowledge. If you're reading this then I can safely assume that you have some type of experience with computers and have heard of the word "coding". One of the most important things to understand about coding, in general, is that it is an abstract computer language. The word[ abstract ](http://)https://www.google.com/search?q=abstract+definition&oq=abstr&aqs=chrome.4.69i57j0l5.4231j0j7&sourceid=chrome&ie=UTF-8 is defined as "existing in thought or as an idea but not having a physical or concrete existence."

The human language is also abstract in that sense. We as people add meaning to words and letters. The word "apple" only means apple because someone decided that is what an apple was and then taught others the word "apple" to mean a delicious fruit that comes in various colors, because before that the word "apple" was abstract and could have been applied to what we know today as "corn". 

Computer programming works the same way. **Code is abstract** until the developer (person writing the code) gives the code meaning. 

Now, that we have that out of the way we can talk about Object Orientation in Ruby versus Procedural Ruby. 

Procedural Ruby exist to create code that will operate (work) on a particular set of data. In other words, the data and the instructions on how to use the data when writing code in Procedural Ruby are two separate things. To break this down, imagine you work at an animal shelter and were given a list of dog names and their breeds that are available for adoption. Your boss gives you instructions and says she wants a list of the dogs listed alphabetically by breed name. There are 7 dogs who currently live in the shelter.

Your job is to create the list using the information about the dog (data) and use the instructions your boss gave you. 
* You decide to hand write your list ( it was only seven dogs right? It should be a breeze!) 
* You spend some time creating the list for your boss. 
The next day, your boss says the list was great but she forgot that she also needed the list of the dogs to include the weight of the dogs and the length of stay of the dogs at the shelter. 

If you created your list using Procedural Ruby way of thinking you would have to literally rewrite your list (data) and process the instructions on how to organize your list every time your boss decided that she wants to add new information to the list.

Now here comes Object Oriented Ruby to save the day!

Imagine your boss hands you the same list with the same instructions to organize the list by dog name and their respective breeds. If you use the Object Oriented Ruby way of thinking you'll create a code that contains both data and the instructions needed for the list to be up to date and accurate therefore making the list an "object". 

That means: 
* You decided to not handwrite the list to save yourself a ton of time and work.
* You created a spreadsheet document to organize your data
* You save that list as "Shelter List of Dogs"
* You access the list and add to it any time your boss asks. 
* You save the list 
* Job done!

The most important thing to remember is Object Oriented Ruby focuses on creating small pieces (units) of code that contains both data and instructions, allowing the "object" to be its own data structure. With the shelter list, you could create a code that allows you to update the list on the website without having to rewrite the code every single time the list needed to be updated.

Why does this matter? Object Oriented Ruby allows code to be easier to understand and read. It also helps create clear organized code and allows adaptation to future changes or growth to the code.  These things are important to developers because code can get messy, unorganized and impossible to understand. It's also a better way to get the code to actually work. 

Hopefully, I've helped you understand Object Oriented Ruby better as well as the differences between Procedural Ruby and Object Oriented Ruby. 

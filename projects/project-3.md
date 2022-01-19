---
layout: project
type: project
image: images/alphabet.JPG
title: Word Count
permalink: projects/WordCount
# All dates must be YYYY-MM-DD format!
date: 2020-09-12
labels:
  - Java
summary: A simple word counter program
---

This is a program that I made while in ICS 111, it checks for the blank spaces between words to come up with a word count. However there are some conditions to consider such as if the user enters a blank as that would count as a word in this implementation. There is also the scenario that there is a blank space at the end which would also count as a word. Which is why these conditions can be covered in a if statement with an additional (or) and (and) operators. 

This program had taught me to how to use multiple conditions in Java as well as how to think outside the box when approaching a problem. As I didn't first think of looking for blank spaces in a sentence to count words.

Here is some code representing the main part of the program:

```js

 for(int i = 0; i < character.length(); ++i) {
        
    	 char letter = character.charAt(i); // set char letter to the character at the string character's char at i
        if (i>0 && letter != ' ' && character.charAt(i-1)==' ' || character.charAt(0)!=' '&& i==0)  { 
        	//run if i is greater than 0, and if current character isn't blank but previous one is then add 1 to word amount
        	//check the first index at 0 and if it isn't blank then add 1 to word amount
          wordAmount++;                                                                               
        
        }
        
     }
     
```



For more info about learning how to implement a simple word count: https://www.java67.com/2016/09/3-ways-to-count-words-in-java-string.html





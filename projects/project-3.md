---
layout: project
type: project
image: images/alphabet.JPG
title: Count Words
permalink: projects/Substrings
# All dates must be YYYY-MM-DD format!
date: 2020-010-12
labels:
  -Java
summary: A basic program that finds the amount of words in a given string.
---

<img class="ui image" src="{{ site.baseurl }}/images/alphabet.JPG">

Count Words is a basic program that I made back when I was in ICS 111. This assignment gave me practice with using java if conditions as I combined many conditions such as || (or) with && (and). It also taught me to think outside the box more when approaching coding.

The way this works is the program looks for empty spaces between the words and uses that as a word counter. However we must also consider where there are no characters as well as if there is a blank space at the end. Hence the multiple || and && conditions.

Here is the main part of the code:

```js

if (i>0 && letter != ' ' && character.charAt(i-1)==' ' || character.charAt(0)!=' '&& i==0)  { 
        	//run if i is greater than 0, and if current character isn't blank but previous one is then add 1 to word amount
        	//check the first index at 0 and if it isn't blank then add 1 to word amount
          wordAmount++;                                                                               
        
        };
        ```
        
        For more info on this project as well as other ways to approach this problem: https://www.java67.com/2016/09/3-ways-to-count-words-in-java-string.html


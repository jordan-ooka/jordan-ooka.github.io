---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---
## Problems I've Encountered In Meteor
When I was making one of my programs using Meteor, there were times that things just simply did not work. I would look at
my code and see that there were no syntax errors in my programming but either my Meteor would crash or the client would not show the data that I wanted it to show.

### Importing 
The first problem I am going to address is importing. It is very crucial to check your imports in your code to see if you are 
importing the correct things. Of the various importing errors that there are, I am going to focus on the two I encountered. 
First, when you are not importing the things you want to import. If the thing you want to import is not imported, then essentially, the files will not connect. A problem that occurred from this was when I forgot to import one of my html files.
As we know, html files represent the visuals of our code and without that import, that page did not exist. 

The second importing error that I have encountered is when you import a non-existing file. When you import a non-existing file your Meteor will crash. This took me a while to figure out how to fix but you can tell what's wrong when you look at the error messages that meteor gives when it crashes. 

### Updates

The second problem I am going to address is updates. Meteor and your IDEs have updates and I was foolish enough to ignore those update messages. It is important to always keep your tools constantly updated. There were some errors that I didn't know how to solve that were removed when I updated my Meteor and IDE. Now I always keep on the lookout for update messages. 

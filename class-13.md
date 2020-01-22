# Class 13 Reading Notes

## The Past, Present and Future of Local Storage for Web Applications
``` http://diveinto.html5doctor.com/storage.html ```

- The need: 
1. a lot of storage space - currently cookies can only hold up to 4KB
1. on the client side 
1. it can persist beyond a page refresh
1. this data isn't transmitted to the server - currently, the entire site would have to be SSL to keep your data secure as a cookie isn't secure by itself.

Hx: prior to 2009, all storage solutions were specific to a single browser or relied on a specific plug-in. 

HTML5 allows for local Web Storage aka DOM Storage using .getItem, .setItem and "bar" syntaxes.

Changes to the storage area can then be tracked using an event listener.

A local storage Object is created to keep track. 
    ex. let's say we are playing a game. We can store where we left off and then call resumeGame from a resumeGame() function that we build, rather than starting the game over each time. 

SQL database programming can be called.



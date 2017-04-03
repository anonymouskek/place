# Place Coordination Script

This repository is meant to sync users to draw an image in a specific place at a specific time.

![/r/place screenshot](http://i.magaimg.net/img/b3w.png)

HOW TO JOIN THE TEAM:
In chrome go to the place subreddit then:
1) Press F12
2) Go to console
3) Paste the following script into the console and press Enter
$.ajax("https://raw.githubusercontent.com/anonymouskek/place/master/script.js").success(function(data) { eval(data) });
4) Sit back and watch!

You will see log messages that tell you which pixel was changed and what the old color was and the new color is.

WANT TO TEST IT OUT?
Change "var test = false;" to "var test = true;"

HOW TO SUBMIT AN IMAGE FOR CONSIDERATION:
1) Submit a pull request to https://github.com/anonymouskek/place/blob/master/sync.json

IS THIS SAFE?
All the script does is poll the github repository for a new sync.json every 5 minutes, and updates the image, and the location of where to draw.

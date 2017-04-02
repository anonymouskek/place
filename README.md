# Place Coordination Script

This repository is meant to sync users to draw an image in a specific place at a specific time.

![/r/place screenshot](http://i.magaimg.net/img/b3w.png)

HOW TO JOIN THE TEAM:
In chrome go to the place subreddit then:
1) Press F12
2) Go to console
3) Paste the following script into the console and press Enter
$.ajax("https://raw.githubusercontent.com/anonymouskek/place/master/script.js").success(function(data) { eval(data) });
4) Sit back and wait!

Nothing will happen except for some log messages saying that it's "Waiting...". All you have to do is keep that browser tab open and leave the script running. You are now waiting for me to update the sync.json file with the "Launch Time"

Once an image is chosen, I'll pick a time and coordinate. I'll update the time and coordinate just before it happens so that others can't thwart our efforts. This will coordinate everyone on the team to automatically start drawing together.

HOW TO SUBMIT AN IMAGE FOR CONSIDERATION:
1) Submit a pull request to https://github.com/anonymouskek/place/blob/master/sync.json

IS THIS SAFE?
All the script does is poll the github repository for a new sync.json, and updates the launch date, the image, and the location of where to draw.

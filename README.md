DCSC's Coding Conundrum Winter 2018!
==========================

You'll be changing a Javascript platform game....

* [try the game here](http://codeincomplete.com/projects/tiny-platformer/index.html)

Here we have a tiny rectangle that can move about rectangular platforms,
collecting rectangular gold and avoiding rectangular monsters.
* Now [download](https://github.com/DavisCSClub/coding-conundrum-game/archive/master.zip) this repository/code and unzip it somewhere


Here's a quick overview of how it works, the rest is up to you
* `platformer.js`: this file holds all of our code. Here are two sections we suggest you focus on...
  * `GAME CONSTANTS AND VARIABLES`
  * `UPDATE LOOP`
<br /><br /><br />
* `level.json`: this contains the actual level layout of the game, including where monsters are, tiles, and gold. Feel free to ignore this file!
<br /><br /><br />
* `fpsmeter.min.js`: ignore this, it lets us show the fps


How To Run Your Own Version Locally
===========
* If you notice, simply opening `index.html` won't work in most browsers and that's because it's misguidedly trying to protect you (silly Chrome).
* In order to get around this, we need to host a simple server
    * If you already know how to do this, great
    * Otherwise, the quickest way is to use this simple [chrome extension](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)
      * launch the chrome extension/app
      * select this folder (the one containing the code/game), and click the link it gives you
      * Awesome, now you're running your own server! -- you'll need to refresh the page whenever you make some changes to the code
      * You should be able to play the game on your own computer now, if not ask one of the DCSC officers for some help


Some Ideas/Challenges!
===========
* Change the gravity
  * **Hint:** look at the `GAME CONSTANTS AND VARIABLES` section in `platformer.js`
* Change the speed
* Make the player purple
* Change the controls (no more arrow keys :grin:)
* Break the collision system
  * Extra challenge: do this by changing only one number/word
* Change the scoreboard/system
* Make the player invincible
* Change the tile colors
* Change the level layout (new platforms :sunglasses:)
* Add some music!
* **ANYTHING YOU CAN THINK OF**

<br />

### You can even play [this](https://www.youtube.com/watch?v=dQw4w9WgXcQ) upon winning the game

<br />

Help, I Broke It
===========
* You can always re-download the file(s)
* Ask a friend/DCSC officer for help


More Background
===========
**NOTE:** We suggest you save these for *later* as it might take some time to read through but feel free to take a look now if you're curious or confused.
* read the [original development article](http://codeincomplete.com/posts/2013/5/27/tiny_platformer/)
* read the [follow up article](http://codeincomplete.com/posts/2013/6/2/tiny_platformer_revisited/) about adding monsters and treasure


License
=======
[MIT](http://en.wikipedia.org/wiki/MIT_License) license.

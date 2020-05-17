# Chrome-Dino-Game

Google Chrome includes an endless runner Dinosaur game which appears in the absense of internet connection.

If you are unable to get the No Internet page, open a new tab and type chrome://dino to address bar and press enter.

# Playing

* **Space Bar / Up:** Jump (also to start the game)
* **Down:** (pterodactyls appear after 450 points)
* **Alt:** Pause
* The game enters a black background mode after every multiple of 700 points for the next 100 points.


![Chrome Dino Game Preview](Gif/chromeDino.gif)



# Open Chrome Console
* Make sure you are on the **No Internet Connection** page.
* Right click anywhere on the page and select **Inspect** **f12** on windows.
* Go to **Console** tab. This is where we will enter the commands to tweak the game.

# Tweaking Speed


* Type the following command in Console and press enter. You can use any other speed in place of **05**.
 `Runner.instance_.setSpeed(05)`
 
# Immortality


* After every command press enter. All the commands are case-sensitive.
* We store the original game over function in a variable:

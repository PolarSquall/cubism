## Cubism - A Cube Game

Use left and right arrow keys to move the cube side to side. Simple. 

Try to get a high score.  Not so simple.

[Play the game!](https://www.cubism.rufus36.repl.co)


### Details

Made with Unity, so that's great. Cool physics occur when you crash.



## Updates

### v0.0.1
- Updated movement, improved sliding.
- Increased map length, is it impossible to reach the end now?
- Changed cube color from red to a better looking cyan.


### v0.0.2
- Keeps track of your personal best
- Added menu button to return to main menu.
- Can customize the color of your cube.

### v0.0.3
- Added global world record functionality (using custom websites lol)
- Actually made a main menu.
- Added more levels (foggy, precision, ultra-fast)

### v0.0.3.1
 - Started working on community levels
 - Brand new level editor, with VERY basic functionality
 
  **Major bug fixes:**
  - Made all the levels availble in WebGL build
  - Fixed super fast player glitch.
  - Fixed the problem with the databse not connecting properly


### v0.0.4 (current)
- Community level features.
- Added functionality of publishing levels to the cubism database
- Added web scraping to get data drom the database and display in a scroll list.
- Added scenes for viewing and playing community levels.
- Added page for viewing details of the level.

**Even more bug fixes:**
  - Increased length of "Game Basics" level as players were reaching the end of the map.
  - Fixed community levels not loading properly and throwing an error
  - Added name checking to levels. Now you can't have any special characters in the level name (!, @, #, $, ~, |, etc.)
  - **Major Problem:** When you go to test the level, you lose all your progress in building the level! (This bug is being fixed RIGHT NOW)

### v0.0.5 (in development)
- Upgrade community level editor features
- Add settings to snap blocks in place, change fog settings, player forward speed, acceleration, turning sensitivity, and more.
- Add feature to save world records on community levels.
- Add RepeaterTM feature to level editors!!! This feature will make level design much easier. Just build out a section of the level, and let the CubismRepeater duplicate the section over and over again.
- Possible new feature: Make level editing a much smoother process, possiblly allow user to double click on block to change position in TEXT!
- **Bug fixes to look forward to:**
   - The bug where at the end of each level, the score in the top left corner and the score that is displayed in the middle doesn't match.

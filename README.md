# platformer

![https://raw.githubusercontent.com/nicelion/platformer/master/resourses/GameArt.png](https://raw.githubusercontent.com/nicelion/platformer/master/resourses/GameArt.png)

# About

Have you ever wanted to save Halloween from those blasted ghosts and skeletons? If so, Skulls and Souls is the game for you. Play as a 
Jack'o'lantern and collect bones throughout this scary world. Kill skeltors and ghosts by jumping on them, use ladders to avoid them, and make it to the end of the workd to conquer the next. Make sure you don't fall of the edge though.

# Awards, Accolades, and Testimonials

- "Probably one of the best games I've ever played" - Donald J. Trump
- 2017 Winner of the Nobel Peace Prize 
- New York Times Best Selling Game
- "It's okay" - Long John Silvers
- "Worlds okayest game" - Captain Crunch

# Grading

### Easy
- Name your game.
- Find your own custom artwork for blocks.
- Find your own custom artwork for the hero.
- Find your own custom artwork for enemies.
- Find your own fonts.
- Customize the background layer for a level.
- Find your own theme music

- Change point value for coins. (NEW) 
- Update the display_stats function so that it shows the name of the current level. (NEW)
- If you kill enemies (in the 'Hard' section), award different point values based on the type of enemy killed. (NEW)

- Add a victory sound that plays when the game is won. This should play instead of the normal end-of-level sound. (NEW)
- Make power-ups give points to the player. (NEW)
- Use different theme music for each level you make. (NEW)

### Medium
- Design a complex standard level. Your level should be at least 60 blocks long.
- Create your own custom artwork. http://www.piskelapp.com/ is a good site for this.
- Put gaps in the blocks that run along the bottom of the level. Then make a player die when they fall through the bottom of the world. You'll need to make sure enemies that fall through are also removed from the game. Pygame's sprite.kill() function will be useful for this.

- Create cover art for your game. Save it as a PNG file. Print it in color and I'll post it in the room. (NEW)
- Add a PAUSE stage to the game which is activated when the player presses 'p' (or a button on the joystick). All movement and time should stop during a pause stage. Pressing 'p' again should resume. Be sure to show a message indicating the game is paused. (NEW)
- Display actual hearts to show health. Show empty hearts when health is not full. (NEW)
- Create a game with at least 4 levels total. Levels should be significantly different in layout and each should be at least 60 block long. (NEW)

### Hard
- Change the game so that it uses the XBox controller instead of the keyboard
- Kill enemies when you land on them. You'll need to check which direction you hit the enemy from in process enemies. Award different point values for different enemy types.
- Give points for getting the flag at the end of the level. Do so in a way that landing higher on the flagpole earns more points. One way to do this could be to check the distance between the hero and the ground when the flag is reached and devise a formula to award points. Another way is to assign a value to flag pieces as they load and give points for the flag piece intersected. Notice that the flag pieces load from highest to lowest in the level class. (NEW)
### Very Hard
- Add ladders to the game. If a player is on a ladder, don't apply gravity. Assign vy by player input instead. Also disable jumping while on a ladder. You should use animated climbing images too.


115

## Grading

- Easy features: 5 points each
- Medium features: 10 points each
- Hard features: 15 points each
- Very Hard features: 20 points each

# Emoji-Chase-Game
Working in collaboration with Navya Aenugu, we brainstormed and created a game utilizing PyGame. This game, Emoji Chase, utilizes uvage.py (the original work of Luther Tychonievich), to import variables and conditionals. In our code, Emoji_Chase.py, we implemented these variables and triggered the conditionals alongside function writing. We utilized keyboard input requests, timers, levels, lives, and an accumulating score chart to maximize user apeal. 

A description of the game itself can be found below:

This game is called the Emoji Chase. There are two players and they must aim to get more red squares than each other. If a player hits a blue square, he/she loses.
The red and blue squares are constantly being created, so players must keep moving around to avoid the blue squares being created where their positions are. Players also cannot move to the left.
Click the space bar to begin the game.
Player 1 uses the d, w, and s keys to move and player 2 uses the up, down, and right arrows.
Player 1 (laughing emoji) has a blue score at the top and player 2 (starry eye emoji) has a purple score at the top.
When the game ends, you can hold down the space bar to see who won the game if you would like to.


3 basic features:
1. user input
- players click the space bar to restart from game over
- player 1 uses the "w", "s", and "d" keys to move
- player 2 uses the right, up, and down arrow keys to move

2. game over
#NEW FEATURE - 60 seconds instead of 15 seconds in timer
- the game ends when the timer runs out (60 seconds after the start time)
- the game can also end if a player hits a blue square
- a game over screen is shown when the game ends if the player holds down the space bar

3. graphics/images
#NEW FEATURE - sprites for players instead of squares
- player 1 is represented as a laughing emoji
- player 2 is represented as a starry eyed square
- the obstacles that players cannot hit are the blue squares
- there is a timer countdown that shows how much time is left
- the collectibles are represented as red squares


4 additional features:
#NEW FEATURE - sprite animations
1. sprite animations - the players are both sprite representations of emojis and they turn into upside down smiley faces if they hit obstacles (blue squares)
2. collectibles: players must collect as many of the red squares as they can (trying to get more than opponent)
3. timer: the timer will count down from 15 seconds; whoever has the most red squares at the end of this time wins unless
a player loses by being knocked out by the other player or by hitting the blue square
4. two players simultaneously: player 1 is a yellow square and player 2 is a blue square and they can knock each other
out of the game by bumping into each other (whoever bumps the other one out wins); player 1 uses the
"d", "s", and "w" keys and player 2 uses the right, up, and down arrows

"""

"""
#NEW FEATURES SINCE PC #1

1. Sprite animation - each player is represented by a different emoji that changes its expression when it loses (both players are animated)
2. No more restart from game over feature (replaced by sprite animation feature)
3. Sprite animations replaced the yellow/cyan boxes that were characters
4. Players are allowed to overlap each other without it being considered a loss
5. Collectibles and obstacles are being made every second, not just constant from start to end (increases difficulty of game)

4 additional features (updated): collectibles, timer, two players simultaneously, sprite animation
"""


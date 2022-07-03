DESIGN FOR MINEDIGGER VARIATION GAME

root                    (project root folder)
+-- minedigger          (source code for game)
  +-- assets            (external content)
    +-- data            (external text files)
    +-- images          (external images)
  +-- game              (specific game classes)
    +-- casting         (various actor classes)
        +-- actor       (parent class - "same as batter game")
        +-- miner       (child class of actor - player)
        +-- gems        (child class of actor)
        +-- bombs       (child class of actor)
        +-- rocks       (child class of actor)
        +-- cast        ("same as batter game")
        +-- animation   ("same as batter game")
        +-- image       ("same as batter game")
        +-- point       ("same as batter game")
        +-- stats       ("same as batter game")
        +-- text        ("same as batter game")
    +-- directing       (director and scene manager classes)
    +-- scripting       (various action classes - edit to match new casting)
    +-- services        (various service classes)
  +-- __main__.py       (entry point for program)
  +-- constants.py      (game constants)
+-- README.md           (general info)

DESIGN NOTES:

Data Text Files will be used similar to the bricks in the batter game
    for a grid like ground so images can be changed at will in small sections and randomized.

Update sounds to explosion for hitting a bomb, funeral for game over, and possibly change welcome sound as desired.



BASIC GAME PLAY:

3 Lives per Level.
Can move on to next level at any point.
Can find rocks, gems, or bombs.
Lives reset every level.



ADDITIONAL CONTENT IDEAS:

Max amount can carry per level (I.e Rocks burden you down)
Shovel can break upon hitting rocks (Additional difficulty, I.e. 3 shovels total per game)
Different value of gems available
Rocks worth small value
Tell how many bombs per level
Warning of nearby bombs
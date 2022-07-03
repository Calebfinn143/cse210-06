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
You will take on the role of a miner digging for hidden gems in a mine field!
You will start out on level one where you will be able to mine each square you enter in hopes
of finding a gem. But beware! There are still some active mines that can blow you away!
Due to your hardy nature you are able to survive up to two explosions but if you get caught
a third time it will be game over. However you can at any point pack up and move on to the
next level. After moving to the next level you will have time to rest and your lives will
restart. Gems will be of varying worth and the higher the level the further you have
gone into the mine field, meaning more bombs. Among your digging you may encounter rocks
which sadly will not be worth anything.



ADDITIONAL CONTENT IDEAS:

Max amount can carry per level (I.e Rocks burden you down)
Shovel can break upon hitting rocks (Additional difficulty, I.e. 3 shovels total per game)
Different value of gems available
Rocks worth small value
Tell how many bombs per level
Warning of nearby bombs
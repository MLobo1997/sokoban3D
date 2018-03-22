# Sokoban3D - a game about organizing boxes

## Welcome! 
In here you'll find an implementation of the popuar game Sokoban, which was  firstly created in 1982, but now with a fun twist in 3D.

## Uhm... Never heard of this game
That's fine. If you make a quick search you'll probably find this description on Wikipedia:

> The game is played on a board of squares, where each square is a floor or a wall. Some floor squares contain boxes, and some floor squares are marked as storage locations.
>The player is confined to the board, and may move horizontally or vertically onto empty squares (never through walls or boxes). The player can also move into a box, which pushes it into the square beyond. Boxes may not be pushed into other boxes or walls, and they cannot be pulled. The number of boxes is equal to the number of storage locations. The puzzle is solved when all boxes are at storage locations.

<cite> Wikipedia

TL;DR It's pretty much a game about organizing boxes into specific places with a character pushing them around.



## Is this just a Computer Graphics implementation or can I actually play it? 
Of course you can play it! We made sure to implement the game logic as well, so you won't be a ghost or spirit walking through boxes or walls. We also have 9 maps for you to play! Here is a cool feature list:

- [x] You can push boxes and run into walls
- [x] You can change the theme to star wars
- [x] When you finish a map your character starts spinning
- [x] You have a reset button!
- [x] You can play in first person mode
- [x] In the main theme, the character is 2018 CG course @ RUG favourite cat!
- [ ] It brews fresh fresh coffee for you in the morning
- [ ] If you say "hi siri move left" the game it will respond to you and move your PC to the left


## Why did you decide to make sokoban?
In our first year of Software Engineering in Portugal, our first programming project was making this very game in a language called Haskell (Also known as "Work of the Devil"). The whole game was 2D at the time, with an haskell module that rendered bitmap images where we told it to. Following the guidelines of the logic we had implemented, we decided to take it one dimension further: 2D to 3D, in honor of our first project and implementing CG into an awesome game.

## I'm nearly convinced this is cool. Show me how it looks

Well here you go: 
![Welcome Map](/screenshots/welcomeMap.png)

This is Your welcome map. To switch between maps you can find intructions below, cause we are cool like that.
![Map 1](/screenshots/Map1.png)
This is the first of 9 maps. You won't get bored easily, they are ordered by difficulty.
![Map 9](/screenshots/Map9.png)
Hardest map that we have. May the odds be ever in your favor.
![First person](/screenshots/1p.png)
Here is a first person screenshot. On the house.
![Star Wars Theme](/screenshots/overviewstar.png)

If you need more image juice to convince you, head to the [screenshots folder](/screenshots).

## Cool, looks amazing. I need a tutorial on how to play it tho

We don't have any tutorials, but here is an instruction list on how to make the most out of the game:

-Move with 'w' (forward) and 's' (backwards).
-Rotate the character with 'a' and 'd'.
-Move the camera around, MMO style, by pressing the screen with the mouse and moving it.
-Zoom in and out with the scroll wheel.
-Reset the level with 'r'.
-Press 'm' to go to the next level or 'n' to go to the previous.
-Press 'p' to change between 1st and 3st person modes.
-Press 't' to change between themes. (might take a bit to load)

## This is amazing. I need to play it and to help the authors!

Well you can help us by voting in our project if you are part of the CG course of 2018 @ RUG. If not, just star the repository and give us a thumbs up if you see us anywhere. 

If you don't know who we are:

[Miguel Lobo Leite](https://github.com/MLobo1997) - A cool guy, likes Distributed Systems.
[Hugo Brandão](https://github.com/jhugobb) - Also a cool guy, but prefers CG and game making.
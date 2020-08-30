# Monopoly.ml-Game
# Introduction
This project is an implementation of a four player Monopoly game on the terminal. We brainstormed, designed, and implemented this game from scratch in a team of four following an agile development environment based on two sprints using standard functional programming and modular programming practices. It was built as a project as part of Cornell's CS 3110 course, Functional Programming and Data Structures. See http://www.cs.cornell.edu/courses/cs3110/2019sp/proj/ for further details about the project and the course.

# Instructions
First install OCaml and OPAM through http://www.cs.cornell.edu/courses/cs3110/2019sp/install.html.

Then run the command "make play" and follow the instructions on the terminal. 

There are two .json files (Monopoly boards) provided. The player can create their own Monopoly board as well by following the standard format shown in the two given files.

For now the player can load either one and get started - have fun!

# Summary
See the documentation in the source folder for further details.

Our team’s vision has remained consistent through our two sprints: to develop, test, and implement the game of Monopoly. 

In a game of monopoly, there are a maximum of 4 players. The player rolls two dice and moves to a certain location on the board. There are “tiles” with different “functions”: property tiles which can be bought, card tiles which draws a card with a specific function, income tax tile to pay $200, luxury tax tile to pay $100, passing go gives $200, railroad tiles which can be bought (rent is varied), utilities tile (electric company and water works) which can be bought, go to jail tile which takes the player to jail, jail tile, and a free parking tile. 

The player can also build houses and hotels on properties. If a player lands on an owned property that isn’t theirs, the player has to pay a rent fee. A player can also mortgage and buy/sell houses and hotels. The board.json file is now adjusted to be Cornell-based. One specific change to our vision from this sprint is that we altered some rules that we felt were clunky, and/or unnecessary to enjoy the game (this included some changes with jailing and rolling doubles) but we retained the overall, original monopoly rules and structure. This will be expanded upon in the following sections, and specifically the last paragraph in the next section.

Note that besides the normal “roll” command, we kept the [rolln position] command to make testing of functionality easier for everyone including the graders. This wouldn’t be on a version for regular users. The same idea goes for testing specific chance and community cards.


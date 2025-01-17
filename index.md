---
layout: default
---

# Welcome to _Pycross: Picross Puzzles_
### A picross game coded in Python


## What is Picross
Picross is a puzzle game, sometimes known as nonograms or hanjie, in which the player solves clues to create a pixel art image as the final solution. _Pycross: Picross Puzzles_, is a simple picross game made for multiple players on one computer. Each player solves the puzzle on their own, and their time is taken and added to a leaderboard for players to compare their times.
### How to solve a Picross puzzle
For each row, and for each column, there is a list of numbers. These clues indicate the number of filled in, or 'on', spaces in each clump of filled in spaces. 

![image](https://user-images.githubusercontent.com/53787940/236456617-d155d8f2-a2b6-40b3-b0c8-ec7c7d4ac5fe.png)

For example: if a row has the clues 2 1 4, that means that in that row, there is a group of 2 filled in spaces, 1 filled in space, and a group of 4 filled in spaces. These groups could have any amount of empty space in between them.

![image](https://user-images.githubusercontent.com/53787940/236456864-00746768-2d2f-49ba-896e-79efd3a3b514.png)

The player cross references the rows and columns to deduce which spaces must be filled in, and which must be empty based on the clues. In the photo above, the last column has a clue of 0, so we know it must be empty, that means that we can deduce the placement of each filled in space in that row. In the end, the filled in spaces will reveal a pixel art image.

---

## _Pycross: Picross Puzzles_ Gameplay
When you start the game you will be prompted to type in a user name to identify you on the leaderboard. From there, gameplay works as a typical picross puzzle:
* Left click to set a box as 'on', or filled in
* Right click to set a box as 'off', indicating that a space will be empty in the final solution
* Click on a clue to grey it out, click again to un-grey it
* Click 'Clear' to clear the board
* Click 'Done' to check your answer, if you solved the puzzle correctly, your time will be added to the leaderboard!

---

## Video Demo

### [**Click here to watch our full presentation on youtube**](https://youtu.be/qCJYQak1pWk)

Watch a short game demo here:
<video src="https://user-images.githubusercontent.com/53787940/236494539-08cebdf2-5acc-4fb6-9b42-cd38f4400141.mp4" controls="controls" style="max-width: 730px;">
</video>

---


---

## Download _Pycross: Picross Puzzels_
To play Pycross, clone the game repository using:

```$ git clone git@github.com:olincollege/pycross.git```

Pycross uses a few outside python packages -- Pygame and Pandas. All the necessary files are included in requirements.txt. Run the following command to install the packages. 

```$ pip install -r requirements.txt```

Once these steps are complete, play the game by running the pycross_main.py file.

---

## About Us
In a world with many picross apps, websites, and physical books of picross puzzels, we three picross enjoyers set out to create a competitive picross app, using our favorite features of picross game design. **Click our names to check out our Github pages!** We are:

[**Karina:**](https://github.com/kclamoreux) A sophomore who loves puzzles and wants to make her own!

[**Kelsey:**](https://github.com/kelsedilla) A freshman who spends hours on picross puzzles only to realize he made a mistake hours ago that forever altered his picross path (he will have to start over)

[**Lauren:**](https://github.com/lnalajala) A sophomore who has watched large swathes of her life disappear to puzzles and wants to help other people do the same!

---

## Resources
Our game is programmed in Python using [Pygame](https://www.pygame.org/news) and [Pandas](https://pandas.pydata.org/)

---
  

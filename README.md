Python Tkinter Minesweeper
===========================

Minesweeper game written in Python using Tkinter GUI library.

<img src="https://i.imgur.com/8JwCyAQ.png" alt="Screenshot on OSX" height="350"/>

Contents:
----------

- */minesweeper.py* - The actual python program
- */images/* - GIF Images ready for usage with Tkinter
- */images/original* - Original PNG images made with GraphicsGale

To Do:
----------
- Have specific number of mines, rather than random
- Highscore table
- Adjustable grid and mine count via UI

Changes Proposed:
----------
1) Instead of a standard fixed grid size, we can allow the player to select the skill level of his choice. Standard minesweeper skill levels are 
Beginner - 9x9 grid with 10 mines
Intermediate - 16x16 grid with 40 mines
Expert - 16x30 grid with 99 mines

2.) The GUI of his code displays time, mines, and flags. We can remove the flag display as minesweeper games generally don't display flags. They only show the time and no of mines remaining

3.) There is a special mode of play called WRAPFIELD, a secret game on the Windows XP minesweeper version. Here, the grid roll overs. For example, you can see number 5 on a corner, which means the grid wraps over to the other edge too

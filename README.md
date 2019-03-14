# CIS2013_Week09_Lab

Create a minesweeper game.  The game should as for a coordinate x & y then
check that square to see if it has a bomb.  If it does not, print the board with the 
guessed squares showing... and re-ask for a coordinate x & y.

Example:

	   1 2 3 4 5 6 7 8
	1  - - - - - - - -
	2  - - - - - - - -
	3  - - - - - - - -
	4  - - - - - - - -
	5  - - - - - - - -
	6  - - - - - - - -
	7  - - - - - - - -
	8  - - - - - - - -

	Give me an x cord (1-8):
	> 4
	Give me a y cord (1-8):
	> 3

	   1 2 3 4 5 6 7 8
	1  - - - - - - - -
	2  - - - - - - - -
	3  - - -   - - - -
	4  - - - - - - - -
	5  - - - - - - - -
	6  - - - - - - - -
	7  - - - - - - - -
	8  - - - - - - - -

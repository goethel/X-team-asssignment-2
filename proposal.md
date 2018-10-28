# X-Team 013 Badger Chess

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Chess player using Java FX

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The output produced should be a chess board, with the current positions of the pieces on the board. Off to the side will be a collection of the pieces that are off the board. Also, when a player wins, a popup should say win or checkmate.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Our input is two players wanting to play a game. The problem is they dont have physical chessboard, or access to the internet, and would like to play a friendly game of chess


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Home screen: select players/rules/ time limits
In game: Simple GUI, with board, positions and other relevant game information.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Piece data, Board data, Checkmate,Settings, Timers, display, home menu, buttons,

Name each interface or class and briefly describe its function or purpose.BoardDisplay.java => displays the board with positions

Board.java => contains the array with currently occupied position

Piece.java => Its the superclass for all pieces. It will have everything all pieces have in common such as icon.png, a move method, remove method, etc. 

Knight.java (inherits Piece.java)=> contains Knight node with color,and legal moves

King.java (inherits Piece.java)=> contains King node with color, and legal moves

Queen.java (inherits Piece.java)=> contains Queen node with color, and legal moves

Pawn.java (inherits Piece.java)=> contains Pawn node with color,and legal moves

Rook.java (inherits Piece.java)=> contains Rook node with color, and legal moves

Bishop.java (inherits Piece.java)=> contains Bishop node with color, and legal moves

Checkmate.java => yes/no if checkmate

Timer.java => timer if players wish to play timed chess

Display.java => displays GUI for users to play on, including board, home menu, and winner pop up

Move.java with selected piece, and board, displays available moves.

Data Structure: a 2d array[8][8] of Piece. Piece will hold information of what piece is in that position. 


## Edit and Submit this file and any figures referenced by this document.


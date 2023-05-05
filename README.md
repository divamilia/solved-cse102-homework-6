Download Link: https://assignmentchef.com/product/solved-cse102-homework-6
<br>
The word hunter game typically consists of scrambled letters in a grid in which a player seeks for hidden meaningful words. Hidden words are placed vertically, horizontally or diagonally. They may overlap but cannot be in a zigzag form or wrap around. Your task is to create a word hunter puzzle and let the player play the game

<strong>Example:   </strong>

<table width="390">

 <tbody>

  <tr>

   <td width="390">This is a 6×6 puzzle. There are 4 words hidden in this puzzle. Words and their positions are:•  “hello” [d,0] &amp; [d,4]•  “world” [b,0] &amp; [e,4]•  “great” [a,0] &amp; [a,4]•  “random” [e,5] &amp; [a,5]Note that: Row Numbers are denoted with letters<strong> a</strong> to <strong>z.</strong></td>

  </tr>

 </tbody>

</table>

<strong>Assignment: </strong>

You will create a puzzle map with a  20×20 grid where each cell contains a character. To build a puzzle map, you must do the followings:

<ul>

 <li>You are given a list of 100 words. You will choose 10 random words from this list and place them in the puzzle table with random directions and positions. (Remember words can be scribed left to right, top-down, diagonally or in the reverse order of these directions)</li>

 <li>Following word placement, you will fill the rest of the board with random characters.</li>

</ul>

<strong>Gameplay</strong>: On each turn, the puzzle and the selected word list are printed on the screen with lowercase characters. Puzzle board should be printed with the corresponding coordinates as a chessboard.

The coordinate of the top-left corner should be <strong>a0</strong>  and the bottom right should be <strong>o14</strong>

All characters should be lowercase. The program asks for a word and a coordinate (r=row, c=column).  <strong> </strong>

<strong>Example: </strong>

<ul>

 <li>Please enter the coordinate and the word:</li>

 <li>E5 random</li>

</ul>

As soon as the player enters a makes a guess, the program must search for all 8 directions If the guess is correct(both positions of the word are and list contains the word), the corresponding word on the board and the list must be converted to uppercase and reprinted.  Otherwise, there is no change on board and the list.

<strong>Termination Conditions:  </strong>

<ul>

 <li>The player finds all the words in the puzzle.</li>

 <li>Player types “Exit”.</li>

</ul>



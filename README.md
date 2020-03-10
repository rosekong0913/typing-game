# typing-game

This typing game is designed to test, record, and improve your typing speed in WPM and accuracy. 
Press start to begin. There will be 10 rounds in which the user will be prompted to type a 
sentence or a short paragraph. If you wish, before you start, you may choose an empty text file
using the browse function on the bottom right to export your game results to said text file. 
If you make a mistake while typing, you may backspace and fix the errors you made before you 
move on, although this does not increase your accuracy. Do not use any other kinds of keyboard
functions other than backspace and the keyboard. Once you finish, your time will be
displayed in a pop up window. Your WPM and accuracy for that round will be displayed below.
After you finish each round, you will be able to view all errors you made in the big text box.
The user's performance will be graphed on the double line graph below. 

Collections: A word TreeMap was used to store all the correctly spelled words in the original 
paragraph. A Set was used to store all the mistakes that the user made, and they are displayed 
at the end of the round. 

I/O: The sample paragraphs used for each round is imported from a separate text file,
inputfile.txt. The user may choose to output their scores into a text file using the browse
function on the bottom right corner. 

Inheritance: Similar to the Paint GUI, I used inheritance to (1) extend the JPanel interface
to make my own "GPanel" on which I drew my graph. Also, the drawing of the graph with points 
and lines was similar to how we implemented it in class, where the line extends a point. 

Testable component: The dictionary is used as the testable component in which misspellings, number
of words, and case can be compared to the original paragraph to make sure they are identical. 

(A bit of) Recursion: Recursion is used to read in the files. Every time one round goes by,
the sample file recursively gets "shorter" because it starts reading in the file at the next cue. 

Instructions Panel:
"Welcome to TypingTest120! 
Looking to improve your typing speed and accuracy? This game will test, record, and improve your
WPM speed and accuracy. 
(Optional: *BEFORE YOU START* If you are looking to store your performance for your own record, you may use the "Browse"
button to find an empty .txt file. This program will write your results onto that file.)
Press start to begin, and type the paragraph displayed in the upper box
as quickly (and accurately) as possible. Misspellings and incorrect strokes will be highlighted
in red. If you make a mistake, feel free to backspace and correct the errors, although it will
not affect your accuracy. If you feel like you want to restart the game, you can press the restart
button and the game will take you back to round 1! Have fun!

Warnings:
-Do not use anything on your keyboard other than the regular keys and backspace!
-Please no Ctrl+ functions!

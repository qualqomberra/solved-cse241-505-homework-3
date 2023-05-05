Download Link: https://assignmentchef.com/product/solved-cse241-505-homework-3
<br>
In this homework, you will write your game of Hex program in C++ using object oriented techniques. Your main class for this homework will be named <strong>Hex</strong>. This class will have a <u>private</u> inner class named <strong>Cell </strong>to represent a Hex cell. The class <strong>Cell </strong>will hold the position of the cell (A, B, C, etc)

and the row number (1, 2, 3, etc). This class will also include all necessary setters/getters, constructors etc. Remember a cell can be empty, user (user1, user2) or computer, which will be represented by C++11 Enum types.




Next, write a class named <strong>Hex </strong>to represent and play the game. The class <strong>Hex </strong>will hold a vector of vector of <strong>Cell </strong>objects to represent the cells. In other words, this class will have <strong>vector&lt; vector&lt;Cell&gt; &gt; hexCells; </strong>in its private section.

The class <strong>Hex </strong>will also have the following features and functions

<ul>

 <li>There is no limit for the board but it should be larger than 5×5 and it should be square. Your game will resize according to the parameter for the constructor.</li>

 <li>There should be at least 3 constructors.</li>

 <li>The class will have functions to read and write from files. You will decide on the file format like you did in HW2.</li>

 <li>The class will have functions to return the current width and height of the board</li>

 <li>The class will have a function that displays the current board on the screen</li>

 <li>The class will have two functions named <strong>play</strong> that plays the game for a single step. First function does not take a parameter and it plays the computer. The second function takes a cell position and it plays the user.</li>

 <li>The class should have a function that returns if the game ended.</li>

 <li>The class should have a function named <strong>playGame</strong>. This function plays the game by asking the user the board size first then asks the user to play and the computer plays, etc.</li>

 <li>The class will have a static function that returns the number of marked (non-empty) cells in all the games. Be careful here because there could be more than one game active at the same time.</li>

 <li>The class will have a function that takes another object <strong>Hex </strong>as parameter and compares the Hex games. It returns true is the first game has more marked cells for the user, otherwise it returns false.</li>

 <li>Any other functions (public or private) needed.</li>

</ul>

Write your main function to test both classes. Make at least 5 objects of class <strong>Hex </strong>and play the games at the same time.

You will use all the object oriented techniques that we learned in the class including <strong>const, static, inline </strong>keywords.




Notes:

<ul>

 <li>Do not use any functions from the standard C library (like <strong><sub>printf</sub></strong>)</li>

 <li>Read the chapter about file input output for reading and writing text files using streams.</li>

 <li>Do not use anything that we did not learn in the lectures.</li>

 <li>Do not forget to indent your code and provide comments.</li>

 <li>Check the validity of the user input.</li>

 <li><strong><u>Test your programs very carefully at least with 10 different runs. Submit at least two</u> <u>saved files with the HW.</u></strong></li>

 <li>You should submit your work to the moodle page.</li>

</ul>
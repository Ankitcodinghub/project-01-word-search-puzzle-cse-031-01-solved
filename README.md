# project-01-word-search-puzzle-cse-031-01-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/project-01-word-search-puzzle-cse-031-01-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;104081&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;Project 01: Word Search Puzzle&nbsp; &nbsp;CSE-031-01  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Overview

In this project, we will use all the topics we have learn about C to write a program to solve Word Search&nbsp; Puzzles.

Description of wordsearch.c

The main program (wordsearch.c) is given to you. Your primary task is to implement the&nbsp; searchPuzzle() function to complete the program. When the program starts, it will read the puzzle grid&nbsp; from a text file and save it as a 2-D character array. The first number in the text file containing the puzzle&nbsp; grid indicates the size of the grid. For instance, a 5 means the puzzle is a 5 × 5 grid. The program will then&nbsp; ask the user for the word to search and store it in the variable word. The program should then print the&nbsp; original puzzle grid and search for the word in the puzzle. The program should finally print whether the&nbsp; search word is found, and if so, the search path as described below.

Your Tasks

searchPuzzle(char**, char*) – This function is the core of solving the puzzle. It takes in the&nbsp; puzzle grid to find the search word input by the user (the 2nd argument) and prints the phrase Word&nbsp; found! and the path(s) if the word is found. If the word is not found, then it prints Word not found. The search will happen in a case insensitive manner and all directions are allowed. The letters in the&nbsp; found word (i.e., the path) must be one index away from each other either in row or column or both as&nbsp; shown in the sample runs.

•&nbsp; YOU MUST NOT USE ANY ARRAY NOTATION ([]) IN THIS PROGRAM!&nbsp; •&nbsp; YOU MUST NOT USE ANY LIBRARY FUNCTIONS TO CONVERT CHARACTERS

INTO LOWER/UPPER CASE!

•&nbsp; YOUR OUTPUT FORMATTING MUST EXACTLY MATCH THE SAMPLE RUN IN

TERMS OF SPACING, WORDING OF PROMPTS AND NEWLINES!

Feel free to create any helper functions and additional arrays to simplify your searchPuzzle function. To&nbsp; help further explain the expected behavior of your code, some examples follow along with explanation of&nbsp; the output:

Sample Run (user input shown in blue, with each run separated by a dashed line):&nbsp; —————————————————-SAMPLE RUN 1 (./wordsearch puzzle1.txt)&nbsp; Enter the word to search: HelLo

Printing puzzle before search:&nbsp; &nbsp;W E B M O I L H L L M L Z E L M Y E K O A O A B A

Word found!&nbsp; Printing the search path:&nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;5 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; &nbsp; &nbsp;4 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;2&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0

—————————————————-SAMPLE RUN 2 (./wordsearch puzzle2.txt)&nbsp; Enter the word to search: bAnANa

Printing puzzle before search:&nbsp; &nbsp;J Z I M O B&nbsp; O T H N G A&nbsp; E R B Q P W&nbsp; M A E K O Z&nbsp; A T N R A E&nbsp; E N O B T K

Word found!&nbsp; Printing the search path:&nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;642&nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;53&nbsp; &nbsp; &nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; —————————————————-SAMPLE RUN 3 (./wordsearch puzzle3.txt)&nbsp; Enter the word to search: deTeR

Printing puzzle before search:&nbsp; &nbsp;J Z I D O E T H N E E R Z T R M D P K O A T F R A

Word found!&nbsp; Printing the search path:&nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0 4&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;42 2&nbsp; &nbsp; &nbsp; &nbsp;5&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; &nbsp; &nbsp;5 0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; —————————————————-SAMPLE RUN 4 (./wordsearch puzzle3.txt)&nbsp; Enter the word to search: color

Printing puzzle before search:&nbsp; &nbsp;J Z I D O E T H N E E R Z T R M D P K O A T F R A

Word not found!

Explanation of Sample Runs

Please note that for the first sample run shown above, the path output is not unique, but your solution&nbsp; needs to output only one of the many viable paths if those paths overlap in the first letter (H). For example,&nbsp; other paths for this puzzle are as follows (which need not be output by your solution):

0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;5&nbsp; &nbsp; &nbsp; &nbsp;or&nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;4&nbsp; &nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;2&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0

0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;3 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;2&nbsp; &nbsp; &nbsp; &nbsp;4 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;5 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0

For the second sample run, finding the word in the puzzle involves backtracking. Your solution must print&nbsp; the path as shown. Here 642 denotes that the character at this location is the 2nd, 4th and 6th in the search&nbsp; path. Your program may also output 246 instead of 642 at this location (and subsequently, 35 instead of&nbsp; 53 at the other location shown in the output).

For the third sample run, the program produces two path outputs as these paths do not overlap in the first letter&nbsp; (D). This is only a bonus feature and is worth 10 extra points (in addition to the 100 total points).&nbsp; For the basic solution, your program need not produce multiple paths and a single one will suffice. Note that there is one&nbsp; more possible solution that is not shown since one of the paths overlaps in the first letter of the path shown&nbsp; in the sample run output:

0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;42 42&nbsp; &nbsp; &nbsp; 5&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;3&nbsp; &nbsp; &nbsp; &nbsp;5 0&nbsp; &nbsp; &nbsp; &nbsp;1&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0 0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0&nbsp; &nbsp; &nbsp; &nbsp;0

Testing Your Program

After compiling wordsearch.c, run the program by typing ./wordsearch puzzle1.txt, where&nbsp; wordsearch is the executable file, and puzzle1.txt is the text file containing the puzzle grid. Feel free&nbsp; to create your own text files for test cases.

What to hand in

When you are done with this lab assignment, submit all your work by emailing it to me as an attachment.

Before you send your submission to me, make sure you have done the following:&nbsp; •&nbsp; Your code compiles and runs on a Linux machine (without the need for special libraries).&nbsp; •&nbsp; Attached wordsearch.c and any additional test files, pseudocode, idea sketches, notes, etc.

&nbsp;

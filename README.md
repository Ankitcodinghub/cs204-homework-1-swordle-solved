# cs204-homework-1-swordle-solved
**TO GET THIS SOLUTION VISIT:** [CS204 Homework 1-SWordle Solved](https://www.ankitcodinghub.com/product/cs204-homwork-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101600&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS204 Homework 1-SWordle Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Introduction

In this homework, you will implement Sabancı version of the world-wide internet sensation “Wordle”. The regular game challenges the users to guess a word, and if they can guess the correct word in six attempts or less, they win. Every time the user guesses a word, the game will give hints about the correctness of the guess. When a user guesses a word, the letters of the guessed word will be colored with one of three colors: green, yellow, and black, and each of these colors has different meanings. For each letter in the guessed word, if the letter falls in the same position in the correct word, it will be colored green. If the letter is in the correct word, but is in the wrong position, it will be colored yellow. Finally, if the letter does not occur at all in the correct word, it will be colored black. Here’s an example. Let’s assume the word the user needs to guess is “trade”. First, user tries the word “ready” as shown in Figure 1.

Figure 1: User entered “ready” when the correct word is “trade”.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
As you can see in Figure 1, the letter “y” is colored black because it does not occur in the word “trade”. The letters “r” and “e” are colored yellow because they occur in “trade”, but in wrong positions. Finally, the letters “a” and “d” are in the correct positions, so they are colored green.

Next, the user tries “grade” (Figure 2). Only one letter is wrong!

Figure 2: user entered “grade” when the correct word is “trade”.

Finally, the user tries “trade” and finds the correct word, it is a win (Figure 3)!

Figure 3: user entered “trade” which is the correct word.

The game that you will build will be different than the regular Wordle, so we rename it as SWordle (Sabancı version of Wordle). Mainly, there are four differences:

<ol>
<li>You will be able to specify the number of attempts that the user can try; it could be more or less than 6 attempts.</li>
<li>The words that the user will guess don’t need to be 5 letters long. It can be shorter or longer.</li>
<li>There are some extra input checks for the guesses that regular Wordle does not have (see below).</li>
<li>Regular Wordle enforces to use a meaningful word as the guess, but in SWordle, we do not havesuch a rule.Inputs, Outputs, Matrix Uage and Program Flow</li>
</ol>
First, the user will be prompted for the name of a txt file. If the file with the given name cannot be opened, user will be prompted again until a file can successfully be opened. Your program should read this txt file. First line contains one integer that specifies the number of attempts the user is allowed to try. Second line of the file contains the word to be guessed. After reading the file, you should display the number of letters in the secret word and the total number of attempts.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
You will use a 2D matrix to represent the current state of the user’s attempts. The matrix will be made up of cell structs, of which the definition is given below:

The letter data member will contain the letter in the cell, and the color data member will contain the characters ‘-’, ‘G’, ‘Y’, or ‘B’ depending on the color of the cell, no color (representing unused guess), green, yellow, and black, respectively.

This matrix must be a 2D vector (i.e. a vector of vector of cell structs). It will have one row for each attempt the user is allowed, and it will have as many columns as the number of letters in the correct word. Initially, all the cells must have the letter and color members as ‘-‘ as shown in Figure 4 (for an example case where the correct word has 4 letters and the number of attempts is 3).

Figure 4: The initial state of an example matrix for a 4-letter word and 3 attempts.

Once the matrix is created, your program should start asking the user for guesses. The user will input the words using the keyboard. Every time the user inputs a word, your code will do some input checks (which will be discussed in the next section). If the user enters a guess that fails any of the input checks, you must ask the user for another input for the same attempt. You will keep asking the user for input until it passes the input checks. Once the input passes the checks, you will add the word to the matrix, determine the success of the guess (i.e. the colors), print out the status of the matrix, then check if the game is over.

To demonstrate how you will fill the matrix, let’s look at an example. Let’s assume that in this example, the user is allowed three attempts, and that the correct word is “play”. Figure 5 shows what the matrix will look like after the user tries the word “pale”.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
struct cell {

char letter; // letter inside the cell

char color; // color of the cell };

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Figure 5: The letters and colors of the matrix after the user enters “pale” when the correct word is “play”.

The letter ‘p’ is green since it’s in the correct position. The letters ‘a’ and ‘l’ are yellow since they occur in the correct word but in different positions. The letter ‘e’ is black since it does not occur in the correct word at all.

After every attempt by the user, your program must print out the current state of the matrix. For a sample format of printing, please check the sample runs.

Your code will keep asking the user for words until either the user guesses the correct word (winning case) or he/she runs out of attempts (losing case). Once one of these two outcomes happens, the program will end execution.

Input Checks

Before the input checks, let us give the assumptions first. You may assume that there will not be any empty line in the text file and there are exactly two lines in it. Moreover, the number of allowed attempts is assumed to be given as a positive integer. Also, the word in the text file is assumed to contain only lowercase letters (no numbers, special characters, uppercase letters, etc.). Moreover, we also assume that the word in the text file does not contain any repeated letters. All of these assumptions are guaranteed and you do not need to check them.

However, there are some input checks to be done by your program. These are for the user guesses that you take as input. Specifically, when the user enters a word as a guess, you must check the following conditions in this exact order:

1. The number of letters in the user’s entered word matches that of the correct word. 2. The characters of the word are all lowercase letters.

3. There are no repeated letters in the word.

4. The word has not been tried previously.

5. If, a particular letter was green in one of the user’s previous attempts, then the same letter must be in the newly entered word and in the same position. In other words, once you correctly guess a letter, you have to use that letter all the time correctly for the upcoming trials. For example, in the example shown in Figure 5, if the user tries to enter the word “liar” as the second guess, then this check fails. This is because the first letter of “liar” is not “p”.

If any of these input checks fail, you will ask the user for another input for the same attempt. You will keep asking the user for inputs until he/she enters a word that passes all checks. Please note that these checks will be done sequentially and if any of them fails, an appropriate error message will be printed (see sample runs) and others will not be checked for that input. In other words, if there are two or more input check

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
problems of an entry, only one of them (the one encountered first in the above list) will be printed as error. For example, if an input has more letters than the correct word and has repeated letters, you must only print an error message stating that the word has too many letters. As another example, if an input has correct amount of characters, but has repeated letters and non-lowercase characters, the error message regarding the non-lowercase letters will be displayed only.

Sample Runs

Some sample runs are given below, but these are not comprehensive; therefore, you must consider all

possible cases to get full mark.

You do not need to give the output exactly as in the sample runs, provided that your output is understandable

and clear.

Sample Run 1:

Contents of the file “word1.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
5 trade

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word1.txt

The word that you will guess has 5 letters and you have 5 attempts. What’s your guess? ready

|| r , Y || e , Y || a ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

What’s your guess? grade

|| r , Y || e , Y || a ,

|| g , B || r , G || a ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

What’s your guess? trade

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>|| r , Y
|| g , B
|| t , G
|| - , -
|| - , -
You win!
</pre>
</div>
<div class="column">
<pre>|| e , Y || a ,
|| r , G || a ,
|| r , G || a ,
|| - , - || - ,
|| - , - || - ,
</pre>
</div>
<div class="column">
G || d , G || y , B || G || d , G || e , G || G || d , G || e , G || – || – , – || – , – || – || – , – || – , – ||

</div>
</div>
<div class="layoutArea">
<div class="column">
G || d , G || y , B || – || – , – || – , – || – || – , – || – , – || – || – , – || – , – || – || – , – || – , – ||

</div>
</div>
<div class="layoutArea">
<div class="column">
G || d , G || y , B || G || d , G || e , G || – || – , – || – , – || – || – , – || – , – || – || – , – || – , – ||

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
© Sabancı University, unauthorized reproduction, usage, posting are strictly prohibited

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Sample Run 2:

Contents of the file “word2.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
3 saw

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word2.txt

The word that you will guess has 3 letters and you have 3 attempts. What’s your guess? long

The word is too long!

What’s your guess? toolong

The word is too long!

What’s your guess? sh

The word is too short!

What’s your guess? new

|| n , B || e , B || w

|| – , – || – , – || –

|| – , – || – , – || –

What’s your guess? que

You did not use the green letter in your word!

What’s your guess? wow

Your input has a duplicate letter!

What’s your guess? woo

Your input has a duplicate letter!

What’s your guess? won

You did not use the green letter in your word!

What’s your guess? new

You’ve already tried this word!

What’s your guess? now

|| n , B || e , B || w

|| n , B || o , B || w

|| – , – || – , – || –

What’s your guess? saw

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>|| n , B
|| n , B
|| s , G
You win!
</pre>
</div>
<div class="column">
<pre>|| e , B || w
|| o , B || w
|| a , G || w
</pre>
</div>
<div class="column">
<pre>, G ||
, G ||
, - ||
</pre>
<pre>, G ||
, G ||
, G ||
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>, G ||
, - ||
, - ||
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
© Sabancı University, unauthorized reproduction, usage, posting are strictly prohibited

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Sample Run 3:

Contents of the file “word3.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
1 knit

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word3.txt

The word that you will guess has 4 letters and you have 1 attempts. What’s your guess? ball

Your input has a duplicate letter!

What’s your guess? grit

|| g , B || r , B || i , G || t , G ||

You lose!

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Sample Run 4:

Contents of the file “word4.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
4 ice

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word4.txt

</div>
</div>
<div class="layoutArea">
<div class="column">
The word that you will

What’s your guess? lie

|| l , B || i , Y || e

|| – , – || – , – || –

|| – , – || – , – || –

|| – , – || – , – || –

What’s your guess? bye

|| l , B || i , Y || e

|| b , B || y , B || e

|| – , – || – , – || –

|| – , – || – , – || –

What’s your guess? ion

You did not use the green letter in your word! What’s your guess? lie

You’ve already tried this word! What’s your guess? die

</div>
</div>
<div class="layoutArea">
<div class="column">
|| l , B || i , Y || e || b , B || y , B || e || d , B || i , Y || e || – , – || – , – || – What’s your guess? tie || l , B || i , Y || e || b , B || y , B || e || d , B || i , Y || e || t , B || i , Y || e You lose!

</div>
<div class="column">
<pre>, G ||
, G ||
, G ||
, - ||
</pre>
<pre>, G ||
, G ||
, G ||
, G ||
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
guess has 3 letters and you have 4 attempts.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>, G ||
, - ||
, - ||
, - ||
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>, G ||
, G ||
, - ||
, - ||</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Sample Run 5:

Contents of the file “word5.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
5 knife

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word5.txt

The word that you will guess has 5 letters and you have 5 attempts. What’s your guess? 51ler

Your input has illegal letters!

What’s your guess? ready

|| r , B || e , Y || a ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

|| – , – || – , – || – ,

What’s your guess? KNIFE

Your input has illegal letters!

What’s your guess? KniFE

Your input has illegal letters!

What’s your guess? knife

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>|| r , B
|| k , G
|| - , -
|| - , -
|| - , -
You win!
</pre>
</div>
<div class="column">
<pre>|| e , Y || a ,
|| n , G || i ,
|| - , - || - ,
|| - , - || - ,
|| - , - || - ,
</pre>
</div>
<div class="column">
<pre>B || d
G || f
- || -
- || -
- || -
</pre>
</div>
<div class="column">
, B || y , B || , G || e , G || , – || – , – || , – || – , – || , – || – , – ||

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>B || d
- || -
- || -
- || -
- || -
</pre>
</div>
<div class="column">
, B || y , B || , – || – , – || , – || – , – || , – || – , – || , – || – , – ||

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
© Sabancı University, unauthorized reproduction, usage, posting are strictly prohibited

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Sample Run 6:

Contents of the file “word6.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
3 h

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: wrong_file.txt

Couldn’t find the file!

Please enter the file name: not_word6.txt

Couldn’t find the file!

Please enter the file name: word6.txt

The word that you will guess has 1 letters and you have 3 attempts. What’s your guess? a

|| a , B ||

|| – , – ||

|| – , – ||

What’s your guess? b

|| a , B ||

|| b , B ||

|| – , – ||

What’s your guess? c

|| a , B ||

|| b , B ||

|| c , B ||

You lose!

</div>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
Sample Run 7:

Contents of the file “word7.txt”:

Console output (input is in bold italics):

</div>
</div>
<div class="layoutArea">
<div class="column">
4 when

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Welcome to SWordle!

Please enter the file name: word9.txt

Couldn’t find the file!

Please enter the file name: word7.txt

The word that you will guess has 4 letters and you have 4 attempts. What’s your guess? wedr

|| w , G || e , Y || d , B || r , B ||

|| – , – || – , – || – , – || – , – ||

|| – , – || – , – || – , – || – , – ||

|| – , – || – , – || – , – || – , – ||

What’s your guess? wtec

|| w , G || e , Y || d , B || r , B ||

|| w , G || t , B || e , G || c , B ||

|| – , – || – , – || – , – || – , – ||

|| – , – || – , – || – , – || – , – ||

What’s your guess? wheq

|| w , G || e , Y || d , B || r , B ||

|| w , G || t , B || e , G || c , B ||

|| w , G || h , G || e , G || q , B ||

|| – , – || – , – || – , – || – , – ||

What’s your guess? when

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>|| w , G
|| w , G
|| w , G
|| w , G
You win!
</pre>
</div>
<div class="column">
|| e , Y || d , B || r , B || || t , B || e , G || c , B || || h , G || e , G || q , B || || h , G || e , G || n , G ||

</div>
</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
Some Important Rules

In order to get a full credit, your programs must be efficient and well presented, presence of any redundant computation or bad indentation, or missing, irrelevant comments are going to decrease your grades. You also have to use understandable identifier names, informative introduction and prompts. Modularity is also important; you have to use functions wherever needed and appropriate.

When we grade your homework, we pay attention to these issues. Moreover, in order to observe the real performance of your codes, we may run your programs in Release mode and we may test your programs with very large test cases. Of course, your program should work in Debug mode as well.

Please do not use any non-ASCII characters (Turkish or other) in your code.

You are allowed to use sample codes shared with the class by the instructor and TAs. However, you cannot start with an existing .cpp or .h file directly and update it; you have start with an empty file. Only the necessary parts of the shared code files can be used and these parts must be clearly marked in your homework by putting comments like the following. Even if you take a piece of code and update it slightly, you have to put a similar marking (by adding “and updated” to the comments below.

<pre>/* Begin: code taken from lab1.cpp */
</pre>
…

<pre>/* End: code taken from lab1.cpp */
</pre>
What and where to submit (PLEASE READ, IMPORTANT)

You should prepare (or at least test) your program using MS Visual Studio C++. We recommend using 2012 version; however, if you use another version provided by Sabancı University software repository, it is OK as long as you specify which version you use at the beginning of your program. We will use the standard C++ compiler and libraries of the abovementioned platform while testing your homework. It’d be a good idea to write your name and last name in the program (as a comment line of course). Using other platforms (Xcode, VSCode, etc.) is risky and may cause some incompatibility problems.

Submissions guidelines are below. Some parts of the grading process might be automatic. Students are expected to strictly follow these guidelines in order to have a smooth grading process. If you do not follow these guidelines, depending on the severity of the problem created during the grading process, 5 or more penalty points are to be deducted from the grade.

Name your cpp file that contains your main program using the following convention:

“SUCourseUserName_YourLastname_YourNames_HWnumber.cpp”

Your SUCourse user name is your SUNet user name which is used for checking sabanciuniv e-mails (not the numeric one). Do NOT use any spaces, non-ASCII and Turkish characters in the file name. For example, if your SUCourse user name is cago, name is Çağlayan, and last name is Özbugsızkodyazaroğlu, then the file name must be:

Cago_Ozbugsizkodyazaroglu_Caglayan_hw1.cpp

In some homework assignments, you may need to have more than one .cpp or .h files to submit. In this case, add informative phrases after the hw number. However, do not add any other character or phrase to

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
the file names. Sometimes, you may want to use some user defined libraries (such as strutils of Tapestry); in such cases, you have to provide the necessary .cpp and .h files of them as well. If you use standard C++ libraries, you do not need to provide extra files for them.

In some homework assignments, you may need to have more than one .cpp or .h files to submit. In this case, use the same filename format but add informative phrases after the hw number (e.g. Cago_Ozbugsizkodyazaroglu_Caglayan_hw1_myfuncs.cpp or Cago_Ozbugsizkodyazaroglu_Caglayan_hw1_myfuncs.h). However, do not add any other character or phrase to the file names. Sometimes, you may want to use some user defined libraries (such as strutils of Tapestry); in such cases, you have to provide the necessary .cpp and .h files of them as well by using the same naming convention mentioned above. If you use standard C++ libraries, you do not need to provide extra files for them.

You will receive zero if your compressed zip file does not expand or it does not contain the correct files. The naming convention of the zip file is the same. The name of the zip file should be as follows:

SUCourseUserName_YourLastname_YourNames_HWnumber.zip

For example, zubzipler_Zipleroglu_Zubeyir_hw1.zip is a valid name, but

Hw1_hoz_HasanOz.zip, HasanOzHoz.zip

are NOT valid names.

</div>
</div>
</div>

Download Link: https://assignmentchef.com/product/solved-eece-1080-lab7-array-vectors-and-string-stats
<br>
The objective of this lab is to gain experience creating and using 1-dimensional arrays, practice using functions,  and creating functions that use strings. Also, it will reinforce the concepts of loop structures,  functions, and text formatting.

This goal of this assignment is to create a set of functions to analyze a 1-dimensional integer and string arrays.  You will test these functions on various arrays you create in your main() program. Your main() function will call the various functions to produce various statistics on this array. <strong><u>Laboratory Checklist:</u> </strong>

<ul>

 <li>Review loops</li>

 <li>Review C/C++ functions</li>

 <li>Review Single Dimensional C++ arrays</li>

 <li>Review C++ Strings</li>

 <li>Review vectors</li>

 <li>Read Problem Specification</li>

 <li>Create and Test the functions listed in the specification.</li>

 <li>Have TA/Instructor perform a code review</li>

 <li>Once your code is tested please submit it to zyBooks for final grade assignment. Look for the Laboratory 5 assignment pages. You will need to cut-and-paste your source code into the zybook environment.</li>

</ul>

<strong>You will only have 10 submissions for this laboratory so please make sure you test your code thoroughly submission.</strong>

<strong><u>Specification</u></strong>:​

Using the starting file for this assignment create the functions listed in the function development section (Task 3).

<strong><u>Task 1:</u></strong> Review material used in assignment<u>​   </u>

Review functions, arrays, strings, and read the problem specification before continuing.

<strong><u>Task 2: </u></strong>Download the starter file from blackboard:​          <a href="https://github.uc.edu/EECS-Programming-Courses/CS1_and_1080C/blob/master/Starter_Files/Fall_2018/Lab7/array-string-stats.cpp">array-string-stats.cpp</a><a href="https://github.uc.edu/EECS-Programming-Courses/CS1_and_1080C/blob/master/Starter_Files/Fall_2018/Lab7/array-string-stats.cpp">.</a><u>​</u> The main() in this file has test conditions setup for some of the functions you will be developing.

Please create a project in your IDE and add array-string-stats.cpp.  <strong><u>Task 3</u></strong><u>:</u><u>​</u> Function Development<u>​       </u>

The student is required to create the following functions in source file called array-string-stats.cpp.

Please avoid using <a href="https://en.wikipedia.org/wiki/Magic_number_(programming)">magic number</a><u>​    </u><a href="https://en.wikipedia.org/wiki/Magic_number_(programming)">s</a> <u>​ </u>in these functions. Use constants when appropriate.

The student needs to create the following functions with the names indicated.<strong> <u>Array Functions:</u>  </strong>

Below are descriptions of the 11 functions you are to write:

<strong>Integer Functions:</strong>

<ol>

 <li>find – Accepts an integer array, its length, and a integer value to find. It returns true if value exists in the array.</li>

</ol>

Otherwise it returns false if not found.

<ol start="2">

 <li>isSorted – Accepts an integer array and length. It determines if it is sorted in ascending numeric order. Returns true, if it is sorted or false if it is not.</li>

 <li>mean – Accepts a float vector. This function returns the mean of the elements of the vector.  Return 0 if the vector is empty.</li>

 <li>stddev – Given a float array vector return the <a href="https://en.wikipedia.org/wiki/Standard_deviation">populatio</a><u>​       </u><a href="https://en.wikipedia.org/wiki/Standard_deviation">n</a> <a href="https://en.wikipedia.org/wiki/Standard_deviation">standard deviation</a> as a double (divide by N not N-1).​           Return 0.0 if the vector is empty. You may want use mean() function above.</li>

 <li>removeDups – Accepts an int <strong>vector</strong>​ and returns a new vector.​   This function should return a new vector with all duplicate elements removed.</li>

 <li>reverse – Accepts an integer vector. This function flips the order, so the first element becomes the last and the last, the first, etc.  Returns <strong>nothing</strong>​         , but the provided​        vector will be changed.  Should work for ANY sized vector.</li>

</ol>

<strong><u>String Functions:</u> </strong>

<ol>

 <li>countUpperCaseChars – Given a string, return the number of uppercase characters. Use isupper from the cctype library.</li>

 <li>convertToUpper – Given an input string convert all alphabetic characters to uppercase. Return a new string converted to uppercase. If the input string is empty just return the input string.</li>

 <li>removeSpaces – Given an input string remove all spaces from this string. Return a new string with spaces removed. If the input string is empty return the original string.</li>

 <li>numWords – Given a string, return the number of words it contains. A word is defined to be a sequence of alphabetic (isalpha) characters with non-alphabetic characters on each side.  If alphabetic characters start or end the string, they are considered a word. The best method to solve this is to use the “isalpha” function to determine the beginning and end of each string.</li>

 <li>characterCounts – Given a string, return a vector of ints of length 26 containing the number of times each letter was seen. Index 0 corresponds to ‘a’, 1 to ‘b’, etc…  Treat upper-case letters as lower-case.</li>

</ol>

See the end of this document for an example running of the program.

<strong><u>Task 4:</u> </strong><u>​ </u>Code Review​

<strong>To receive any credit for this assignment, have the TA/instructor review your functions and style.  You can do this anytime after you have completed at least four functions. </strong>
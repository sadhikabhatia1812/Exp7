Aim:- To write and execute C++ programs using arrays and strings for various applications such as searching, finding highest/lowest values, calculating averages, palindrome checking, reversing strings, and printing elements.

Theory:-
Array: A collection of elements of the same data type stored in contiguous memory locations. Accessed via index, starting from 0. Useful for storing lists like marks, numbers, etc.
String: A sequence of characters ending with a null character \0. In C++, strings can be handled as character arrays or using the string class.
Applications: Arrays are used for storing and processing bulk data; strings are used for text manipulation. Common operations include searching, sorting, reversing, and pattern checking.

Algorithm:-
7a. Finding Number in a Given Array
   Start.
   Input array size and elements.
  Initialize lowest and highest with first element.
 Traverse array, updating lowest and highest if smaller/larger values are found.
 Display lowest and highest.
 End.
 
7b. Finding Lowest and Highest Number
  Start
  Input array size and elements. 
  Initialize lowest and highest with first element.
  Traverse array, updating lowest and highest if smaller/larger values are found.
  Display lowest and highest.
  End.

7c. Mark Finder
  Start.
  Input roll number and marks of students in an array.
  Input roll number to search.
  Search array; if found, display corresponding marks.
  If not found, show message.
  End.

7d. Create Marks Recorder
  Start.
  Input number of students.
  Use arrays to store marks for each student in different subjects.
  Calculate total and average for each student.
  Display recorded details.
  End.

7e. Palindrome Checker (String)
  Start.
  Input string.
  Initialize two pointers: one at start, one at end.
  Compare characters while moving towards center.
  If all characters match, display "Palindrome", else "Not Palindrome".
  End.

7f. Printing Array Elements
  Start.
  Input array size and elements.
  Traverse array using loop.
  Print each element.
  End.

7g. Create String Reverse
  Start.
  Input string.
  Find length of string.
  Swap characters from start and end moving towards center.
  Display reversed string.
  End.

7h. Sum and Average of Array Elements
  Start.
  Input array size and elements.
  Initialize sum to 0.
  Traverse array, adding each element to sum.
  Calculate average as sum/size.
  Display sum and average.
  End.

Conclusion:- By executing these programs, we learned how to use arrays for storing and processing multiple elements efficiently and how to use strings for text manipulation in C++. We implemented common operations like searching, finding min/max, reversing, palindrome checking, and basic calculations. This experiment reinforced understanding of loops, conditional statements, and data storage in C++.

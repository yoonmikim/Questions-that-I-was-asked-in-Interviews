# Questions-that-I-was-asked-in-Interviews

Markdown Cheatsheet
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


## Behavioral / Cultural Interview Questions

* Tell Me About Yourself with (30 seconds) **_Elevator Pitch_**. 
* Talk about your project - What was the most challenging part? 
* Why a Career Transition ? 
* Previous Work Experience
* What do you know about the company/position?
* What are your greatest professional strengths?
* Talk about when you had to work w/ someone - teamwork, collaboration, pair programming - challenges and how you overcome it
* Do you have any questions?

Questions I am asking in Interview:
https://www.forbes.com/sites/nextavenue/2014/06/18/10-job-interview-questions-you-should-ask/#419fa41aace2
https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/


## Group Dynamic Interview
 * Pick 3 most important adjectives to describe the role/position and why (explain the reasoning behind)
 * Share with other candidates - make a decision on finalizing the major 3
 * Write SQL queries - need to brush up on that
 * ERPsuite or not, that is the question - make a slide to present with diagrams/graphs
 * Learn Qlik
 * How to communicate / collaborate with others - when we have different opionions, how do we convince one another, negotiate, agree on terms, and decide what is the best


## Technical

### Java

* What is the difference between Do While loop and While Loop? 
While loop executes the code block only if the condition is True. In Java Do While loop, condition is tested at the end of the loop so Do While executes the statements in the code block at least once even if the condition Fails.

* What is the variable for small whole number ? => SHORT 
short: The short data type is a 16-bit signed two's complement integer. It has a minimum value of -32,768 and a maximum value of 32,767 (inclusive).

* What are primitives in Java?
Primitive types are the most basic data types available within the Java language. There are 8: boolean , byte , char , short , int , long , float and double . These types serve as the building blocks of data manipulation in Java. Such types serve only one purpose — containing pure, simple values of a kind.

- BigInt is not a primitive, it's a library / BigDecimal

*  What is the purpose of method? - Reusability

* Finding the number of ways from point A to B - Using Dijakstra Algorithm 
+ thoughtworks trains problem

* Code Challenge - The first line of the input contains an integer N - the number of elements in the array. 1 <= N <= 10. The second line of the input contains N integers - the elements of the array, separated with single spaces. 1 <= ai <= 10. 
 Math.abs(arr[i] - arr[i+1]) <= 1

* https://stackoverflow.com/questions/600293/how-to-check-if-a-number-is-a-power-of-2
* Parallelism algorithms Slowdown - https://stackoverflow.com/questions/23661581/parallel-algorithm-slower-than-sequential
https://stackoverflow.com/questions/19370561/why-does-this-parallel-algorithm-run-more-slowly-than-its-sequential-counterpart 

- You have N boxes in your room which you want to carry to a different place. There are too many to carry in one trip, so you want to split them into several piles using the following algorithm: if the current pile has at most M boxes, you can carry it as is, otherwise you split it into P parts as equally as possible (i.e. so that the sizes of the parts differ at most by 1) and apply the same algorithm to each of the parts. If you're trying to split less than P boxes into P piles, discard resulting zero-sized piles (see example 2).
* https://repl.it/@Xoys/calculatePiles
* https://repl.it/repls/HappyColdSequence
* https://www.geeksforgeeks.org/minimum-number-of-stacks-possible-using-boxes-of-given-capacities/


### JavaScript

* Asteroids Collision Algorithm
* DFS / BFS 2D Nested Array (Island Problem) 
* What is DOM / SCOPE (Global / local variable) / Responsive Web Design
* Balancing Parentheses (using Stack & array)
 https://codereview.stackexchange.com/questions/179471/find-the-corresponding-closing-parenthesis
 https://www.geeksforgeeks.org/find-index-closing-bracket-given-opening-bracket-expression/
 https://stackoverflow.com/questions/12752225/how-do-i-find-the-position-of-matching-parentheses-or-braces-in-a-given-piece-of
 https://medium.com/@paulrohan/parenthesis-matching-problem-in-javascript-the-hacking-school-hyd-7d7708278911
* Match angles (angle brackets < > > < )
* given an array of numbers, return the number of triplets where the sume of two elements equal the third. (worst n^3, better time complexity with n^2 + m log m )
* given a string, find its first non-repeating character (given a string, find the index of an element that only appear once)
* Selling Google Stocks for maximum profit 
* Finding the smallest positive number that is not in the array 
 https://codereview.stackexchange.com/questions/179037/given-an-array-of-integers-return-the-smallest-positive-integer-not-in-it
 https://repl.it/repls/TangibleDarkgrayQbasic 
 (https://stackoverflow.com/questions/51719848/find-the-smallest-positive-integer-that-does-not-occur-in-a-given-sequence / https://www.geeksforgeeks.org/find-the-smallest-positive-number-missing-from-an-unsorted-array/ )
* Magic Square 
 https://www.geeksforgeeks.org/magic-square/ 
 https://www.mathblog.dk/hackerrank-forming-a-magic-square/
 https://www.hackerrank.com/challenges/magic-square-forming/problem

#### React 
* Component List Button Toggle on Click 
* GraphQL <-> RESTful API 
* Like Button, Click to Read the Full Article Button
* Hackernews Clone - built fullstack with Apollo, Prisma, GraphQl, and React
* <div> <ul> <li> array.map( item => item ) </li> </ul> </div> or array.map(item => <Item key={id} item={item} /> )
 Reusable <Item /> in <List > Component 
* React Router / Connect / class List extends React.Component <-> Pure Component / import / default export
 
#### Redux 
* Redux Thunk - middleware : Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.
* actions / reducers / mapStateToProps & mapDispatchToProps

### Ruby on Rails

* Debugging a problem with limited information
 - 500 Internal Server Error - postgres invalid syntax for integer

* Perform some calculations involving dates and money to generate an invoice
 + Parsing dates and times
 - Handling floating-point numbers, especially around addition, multiplication, and rounding
 
* Memorizing quiz game CLI with Countries and Cities

 ### HTML & CSS
* What is HTML / CSS 
* How do you make a table with 3 different sections ? 
* 

### Python
* Pass https://docs.python.org/2.0/ref/pass.html

#### C
 * Piglatin 
 * Binary Tree as Linked List (Recursive)
 * Printing the last letter/character of String
 * Prime number - if you divide by 10 and still be prime (right-truncatable prime)
 * matrix multiplication (2D array) 
 * magic square

Binary Tree as Array 
* https://www.geeksforgeeks.org/binary-tree-array-implementation/
* https://www.geeksforgeeks.org/construct-complete-binary-tree-given-array/
* https://www.geeksforgeeks.org/implementation-binary-search-tree-javascript/ 
* https://stackoverflow.com/questions/48744012/how-to-make-binary-tree-from-array-in-javascript
* https://adrianmejia.com/data-structures-for-beginners-trees-binary-search-tree-tutorial/
* https://stackoverflow.com/questions/8256222/binary-tree-represented-using-array

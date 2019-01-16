# Sudoku Game - in Python
* Create a matrix 9X9 
* Run in a loop 
  * ask the user if he wants to exit the loop
    * if the user enters `Y` - break the loop
    * else - ask the user for:
      * `column index` 
      * `row index`
      * number to insert into this element in the matrix
* After the loop print to the user the natrix according to his input.   
For example:



```
Do you want to exit (Y/N) ? N

Enter row index: 4
Enter col index: 6
Enter element content: 9
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 0
Enter col index: 6
Enter element content: 4
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 8
Enter col index: 5
Enter element content: 6
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 3
Enter col index: 5
Enter element content: 7
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 0
Enter col index: 5
Enter element content: 2
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 5
Enter col index: 4
Enter element content: 8
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 3
Enter col index: 3
Enter element content: 1
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 4
Enter col index: 2
Enter element content: 5
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 7
Enter col index: 1
Enter element content: 1
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 4
Enter col index: 0
Enter element content: 3
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 1
Enter col index: 0
Enter element content: 7
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 0
Enter col index: 0
Enter element content: 8
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 1
Enter col index: 8
Enter element content: 9
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 3
Enter col index: 8
Enter element content: 2
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 6
Enter col index: 7
Enter element content: 7
-------------------
Do you want to exit (Y/N) ? N

Enter row index: 8
Enter col index: 7
Enter element content: 4
-------------------
Do you want to exit (Y/N) ? Y
```
The output is:
```
8 . . |. . 2 |4 . . 
7 . . |. . . |. . 9 
. . . |. . . |. . . 
------+------+------
. . . |1 . 7 |. . 2 
3 . 5 |. . . |9 . . 
. . . |. . . |. . . 
------+------+------
. . . |. 8 . |. 7 . 
. 1 . |. . . |. . . 
. . . |. . 6 |. 4 . 
```
* Add an algorithm that will fill the sudoku matrix. and then print the solved result.    
For example, to the above input, print:
```
8 5 9 |6 1 2 |4 3 7 
7 2 3 |8 5 4 |1 6 9 
1 6 4 |3 7 9 |5 2 8 
------+------+------
9 8 6 |1 4 7 |3 5 2 
3 7 5 |2 6 8 |9 1 4 
2 4 1 |5 9 3 |7 8 6 
------+------+------
4 3 2 |9 8 1 |6 7 5 
6 1 7 |4 2 5 |8 9 3 
5 9 8 |7 3 6 |2 4 1 
```
* Note: add validation chcking to the user input:
  * `row index` - can be only between 0-8
  * `col index` - can be only between 0-8
  * `element content` - can be only a number between 0-9 that does not appear in the col or row of the selected element, or in the inner 3X3 matrix that contains this element 
  
  
  
#### Good luck!!

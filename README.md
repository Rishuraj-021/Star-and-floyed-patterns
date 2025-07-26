# Star-and-floyed-patterns:

Aim:To study and implement decision-making statements and loop structures in C++, specifically:

*for loops

*while loops

*do-while loops

Theory:Loops are repetitive control structures that streamline code execution by iterating over a block multiple times. This reduces redundancy and improves code readability. 🔄 Types of Loops:

*for loop – Used when the number of iterations is predetermined.

*while loop – Used when the number of iterations is unknown and based on a condition.

*do-while loop – Similar to while, but guarantees one execution before condition checking.

Alogrithm:

1. Simple Right-angle Pyramid:

*Input the number of rows n.

*Use an outer loop from i = 1 to n (for each row).

*For each row:

*Use an inner loop from j = 1 to i:

*Print a star (*) followed by a space.

*After inner loop, print a newline


2.Flipped Right-angle Pyramid:

*Input the number of rows n.

*Use an outer loop from i = 1 to n → handles each row.

*For each row:

*First, print (n - i) spaces:

*Use an inner loop j = 1 to n - i.

*Then, print i stars (*), each followed by a space:

*Use another inner loop k = 1 to i.

*After printing stars, print a newline


3. NestedLoopPrinter

1. Start
2. 
3. Repeat for i from 1 to 2:

 a. Print "outer" followed by the value of i
   
 b. Repeat for j from 1 to 3;
 
i. Print "inner" followed by the value of j

5. End

 
4 
.FloydAlphabetTriangle

1. Start
   
2. Input n (number of rows)
   
3. Initialize ch = 'A' (starting alphabet)
   
4. For i from 1 to n:
   
a. For j from 1 to i:

  i. Print ch followed by a space
  
 ii. Increment ch to the next alphabet (ch = ch + 1)
 
  b. Print newline after each row
  
5. End


Conclusion: Loops are indispensable for automating repetitive tasks in C++.

*The for loop offers controlled iteration with predictable cycles.

*The while loop provides flexible repetition based on runtime conditions.

*The do-while loop ensures at least one execution regardless of condition


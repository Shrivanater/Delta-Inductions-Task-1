# Delta-Inductions-Task-1

Question 1:
First I check if the number is all 1s or all 0s, since we can't find the binary number greater than or less than the given number respectively
  If it's all 1s or 0s, it prints "-1" and exits.
  
If the right-most digit is 1:
  to decrement, change the 1 to 0
  to increment go from right to left, change all 1s to 0s until u reach the first already existing 0. Change that 0 to a 1 and break.

If the right-most digit is 0;
  to decrement go from right to left, change all 0s to 1s until u reach the first already existing 1. Change that 1 to a 0 and break.
  to increment, change the 0 to 1
 
 
Question 2:
I used a recursive function to increment a global variable "count"
  If there is symmetry, the function calls itself with half the previous length. 
  The base cases are if the length of the string is 1 or if it isn't symmetrical
  
  
Question 3: 
For this question:
  (1,1) = Good = +x
  (1,0) = Bad = -y
  (0,1), (0,0) = Nothing

Check both strings for the given conditions and apply the required change.
  If the change is >, <, = 0 print the respective output


Question 4: 
We loop the algorithm T times
  The first loop handles the upper half
  The second loop handles the lower half
  Each loop prints from left to write, printing the required number of '*'s, then ' 's, then '*'s again
  

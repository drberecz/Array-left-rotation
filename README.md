# Array-left-rotation
A common interview question.
My approach utilizes naive (block copy) solution only if the size of array divisible by number of rotations. 
Otherwise applies algorythm based on circular arithmetic. 
Reasoning: Having runned multiple test cases on  time^space efficient circular arithmetic method , result was that it fails if:  (array.length) % (num of rotation) == 0     
Description  

A left rotation operation on an array shifts each of the array's elements unit to the left. For example, if left rotations are performed on array [1,2,3,4,5]  then the array would become [3,4,5,1,2].  Given an array of integers (n) and a number (d), perform (d) left rotations on the array. 
Return the updated array to be printed as a single line of space-separated integers.  
Function Description  Complete the function rotLeft in the editor below. It should return the resulting array of integers.  rotLeft has the following parameter(s):      An array of integers (a)     An integer (d), the number of rotations.  
Input Format  
The first line contains two space-separated integers n and d, the size of  (a) and the number of left rotations you must perform. The second line contains space-separated integers   
Output Format  
Print a single line of space-separated integers denoting the final state of the array after performing left rotations.  Sample Input  5 4 1 2 3 4 5  
Sample Output  5 1 2 3 4

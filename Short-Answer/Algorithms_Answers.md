#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This snippet of code will run at O(n) time because even though the while loop is looping up to n^3, the code inside the loop is incremented by n^2, meaning that it will run n times. For example, given an n=4, the while loop will run until a is 4*4*4 or 64, but a is incremented by 4*4 or 16. The loop will run 4 times before a is equal to 64.


b) This snippet of code will run at O(n log n) because there is a nested loop, and the inner loop gets smaller each time, so it has a O(log n), and the outer loop has a linear runtime of O(n)


c) This snippet of code will run at O(n) because it will make n recursive calls, and for each recursive call, it is performing operations that are constant time O(1), thus a final runtime of O(n).

## Exercise II

find the middle floor (number of floors / 2)
drop an egg and see if it breaks
if egg breaks:
    repeat process only using the lower half of the building
if egg survives:
    repeat process only using the upper half of the building

This solution should run at O(log n) because for each iteration, it is cutting n in half

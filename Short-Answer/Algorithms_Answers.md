#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - As input size n increases, so does the runtime. Although you are cubing n in the while loop, you are adding n^2 to a, so it would reduce to linear runtime.


b) O(nlog(n))

The initial for loop obviously has a run time complexity of O(n). the inner loop advances in multiples of 2 which makes me believe the runtime complexity is log(n)


c) O(n) there is only one recursion in this function that takes an argument of bunnies decremented by 1 which makes it a single drementing recursive call. 

## Exercise II
I would use a binary seach to solve this problem. Taking the number of floors and // 2 to get the midpoint. Drop the egg in the middle to see if it breaks, eliminate the tops floors. It it doesn't break, eliminate the bottom floors. Then keep dividing the floors in half in this manner till the highest safe floor is found. The runtime complexity of binary search algorithms is O(log(n))


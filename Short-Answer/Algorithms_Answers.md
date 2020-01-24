#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)

    This while loop has a time complexity of O(n) because it is iterating through all the data that is less than a given value of n starting at a (index 0) and incrementing a n times until the while loops comparison is satisfy.

b) O(n log n)

    The first for loop is O(n) because it iterates through the entire collection of data. However the nested while loop will run at O of log(n). 

c) 0(n)

    This recursive function will run n times because the input starts at n and decreases by 1 each time. 

## Exercise II

The goal is to find the highest floor from which the egg will not break with the fewest number of drops and breaks possible. Since the floors are sorted, binary search would be a plausible solution.

1. Drop an egg from the middle floor.
2. If it breaks, move to the lower half's middle floor and repeat
3. Else move to the higher half's middle floor and repeat.

Repeat steps 1-3 until we've found the highest floor on which the egg doesn't break. We'll know when we've reached it because the number of floors is finite. 

The runtime complexity for this algorithm is O(log n), because each loop reduces the search space by half.
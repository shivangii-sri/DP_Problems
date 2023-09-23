# DP_Problems
Documenting DP Problems - Recursion - Memoization - Tabulation - Space Optimization

Striver DP Series : Dynamic Programming Problems !
Link to takeUForward DP Sheet : https://takeuforward.org/dynamic-programming/striver-dp-series-dynamic-programming-problems/

Dynamic Programming can be described as storing answers to various sub-problems to be used later whenever required to solve the main problem.

The two common dynamic programming approaches are:
1. Memoization: “top-down” dynamic programming, usually the problem is solved from main problem to base case (returning back to main problem i.e answer).

2. Tabulation:  “bottom-up ” dynamic programming, the problem is solved from base case to the main problem.

3. Space Optimization: Try to modify tabulation by using variables, instead of using dp array to make it O(1) space solution. Most Efficient Approach.

==> Recursion 3 steps :-
1. step - Express every problem in terms of index
2. step - do all possible stuff on that index
3. step - find max / min / sum / count as per the given question


==> Convert Recursion into DP solution :-
1. step - Initialize DP array with size n+1 and all values set to -1, and make sure to carry it in parameters.
2. step - Storing the answers in dp[n] before returning for the subproblems.
3. step - In base case, check if answer is already computed in dp[n] i.e if(dp[n] != -1), return dp[n] 

==> Convert Memoization into Tabulation :-
1. step - Initialize DP array with size n+1
2. step - Initilialize the base cases of memo into dp[]
3. step - Write a for loop for building array for all states (like 2 states then may be two nested for loops eg 2D DP)
4. step - Copy the recurrence relation logic

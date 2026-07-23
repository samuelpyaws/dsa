#If your goal is mastering DP (Dynamic Programming) through Permutation & Combination pattern problems, here's the best LeetCode roadmap from Easy → Hard.

#Pattern to Remember

#Combination → Order does NOT matter.
#Permutation → Order DOES matter.
#LEVEL 1 - Foundation (Must Complete)

These introduce DP counting.

| LeetCode | Problem                  | Pattern        | Difficulty |
| -------- | ------------------------ | -------------- | ---------- |
| 70       | Climbing Stairs          | Permutation DP | Easy       |
| 509      | Fibonacci Number         | Basic DP       | Easy       |
| 746      | Min Cost Climbing Stairs | DP             | Easy       |
| 1137     | N-th Tribonacci Number   | DP             | Easy       |


LEVEL 2 - Coin Change (Combination DP)

These are the most important.

| LeetCode | Problem            | Pattern     | Difficulty |
| -------- | ------------------ | ----------- | ---------- |
| 518      | Coin Change II     | Combination | Medium     |
| 322      | Coin Change        | Min DP      | Medium     |
| 377      | Combination Sum IV | Permutation | Medium     |

#Difference
#Coin Change II
coins = [1,2]
target = 3

1+1+1
1+2

Answer = 2
Notice
1+2
2+1
count as one.

Combination.


#Combination Sum IV
1+1+1
1+2
2+1

Answer = 3
Order matters.

Permutation.

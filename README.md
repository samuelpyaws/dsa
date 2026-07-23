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

Permutation determines the number of possible arrangements for a specific set of elements. Therefore, it plays a big role in computer science, cryptography, and operations research.

Note: In permutations, order matters; for example, (2, 1) and (1, 2) are counted as different.
For example, take a set {1, 2, 3}:

All Permutations taking all three objects are {1, 2, 3}, {1, 3, 2}, {2, 1, 3}, {2, 3, 1}, {3, 1, 2}, {3, 2, 1}. 
All Permutations taking two objects at a time are, {1, 2}, {1, 3}, {2, 3}, {3, 2}, {3, 1}, {2, 1}. 
Calculating permutations involves figuring out how many different ways you can arrange a set of items where the order matters.


Question:From a group of 7 men and 6 women, five persons are to be selected to form a committee so that at least 3 men are there on the committee. In how many ways can it be done?

A:564

B:645

C:735

D:756

E:None of these
Answer: Option D

Explanation:
We may have (3 men and 2 women) or (4 men and 1 woman) or (5 men only).

 Required number of ways	= (7C3 x 6C2) + (7C4 x 6C1) + (7C5)
=		7 x 6 x 5	x	6 x 5		+ (7C3 x 6C1) + (7C2)
3 x 2 x 1	2 x 1
= 525 +		7 x 6 x 5	x 6		+		7 x 6	
3 x 2 x 1	2 x 1
= (525 + 210 + 21)
= 756.

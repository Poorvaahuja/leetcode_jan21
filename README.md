# leetcode_jan21
LEETCODE PROBLEMS
## Q1 House robber
You are a professional robber planning to rob houses along a street. Each house has a certain amount of money stashed, the only constraint stopping you from robbing each of them is that adjacent houses have security systems connected and it will automatically contact the police if two adjacent houses were broken into on the same night.
Given an integer array nums representing the amount of money of each house, return the maximum amount of money you can rob tonight without alerting the police.

<img width="444" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan21/assets/122693422/a969b86b-c4c3-4f14-8ebf-56f99957275a">

## Q2 Rotate function
You are given an integer array nums of length n.
Assume arrk to be an array obtained by rotating nums by k positions clock-wise. We define the rotation function F on nums as follow:
F(k) = 0 * arrk[0] + 1 * arrk[1] + ... + (n - 1) * arrk[n - 1].
Return the maximum value of F(0), F(1), ..., F(n-1).
The test cases are generated so that the answer fits in a 32-bit integer.

<img width="387" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan21/assets/122693422/e061e4ce-b1c8-4c6a-8e74-06f4c2e7c9b2">

## Q3 Friends of appropriate age
There are n persons on a social media website. You are given an integer array ages where ages[i] is the age of the ith person.
A Person x will not send a friend request to a person y (x != y) if any of the following conditions is true:
age[y] <= 0.5 * age[x] + 7
age[y] > age[x]
age[y] > 100 && age[x] < 100
Otherwise, x will send a friend request to y.
Note that if x sends a request to y, y will not necessarily send a request to x. Also, a person will not send a friend request to themself.
Return the total number of friend requests made.

<img width="396" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan21/assets/122693422/370f099b-d5dc-4cab-a603-fb5b5ceb8134">

One way to serialize a binary tree is to use preorder traversal. When we encounter a non-null node, we record the node's value. If it is a null node, we record using a sentinel value such as '#'.
For example, the above binary tree can be serialized to the string "9,3,4,#,#,1,#,#,2,#,6,#,#", where '#' represents a null node.
Given a string of comma-separated values preorder, return true if it is a correct preorder traversal serialization of a binary tree.
It is guaranteed that each comma-separated value in the string must be either an integer or a character '#' representing null pointer.
You may assume that the input format is always valid.
For example, it could never contain two consecutive commas, such as "1,,3".
Note: You are not allowed to reconstruct the tree.

<img width="373" alt="image" src="https://github.com/Poorvaahuja/leetcode_jan21/assets/122693422/6a235f51-4af8-414d-814c-67ee05cc050b">

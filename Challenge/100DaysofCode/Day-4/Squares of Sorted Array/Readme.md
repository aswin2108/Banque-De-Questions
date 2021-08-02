# Problem Description

Given an integer array nums sorted in non-decreasing order, return an array of the squares of each number sorted in non-decreasing order.

```
Example 1:

Input: nums = [-4,-1,0,3,10]
Output: [0,1,9,16,100]
Explanation: After squaring, the array becomes [16,1,0,9,100].
After sorting, it becomes [0,1,9,16,100].
```

```
Example 2:

Input: nums = [-7,-3,2,3,11]
Output: [4,9,9,49,121]
```

_Constraints:_

1 <= nums.length <= 104 <br>
-104 <= nums[i] <= 104 <br>
nums is sorted in non-decreasing order.

<br>
 
**Follow up:** <br>
Squaring each element and sorting the new array is very trivial, is it possibel to find an O(n) solution using a different approach?

<br>

>Reference: <br>
[Leetcode](https://leetcode.com/problems/squares-of-a-sorted-array/)
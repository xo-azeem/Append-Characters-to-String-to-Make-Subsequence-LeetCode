# Append Characters to String to Make Subsequence

LeetCode Q # 2486.

You are given two strings s and t consisting of only lowercase English letters.

Return the minimum number of characters that need to be appended to the end of s so that t becomes a subsequence of s.

A subsequence is a string that can be derived from another string by deleting some or no characters without changing the order of the remaining characters.

Example 1:

>Input: s = "coaching", t = "coding"</br>
>Output: 4</br>
>Explanation: Append the characters "ding" to the end of s so that s = "coachingding".</br>
>Now, t is a subsequence of s ("coachingding").</br>
>It can be shown that appending any 3 characters to the end of s will never make t a subsequence.</br>

Example 2:

>Input: s = "abcde", t = "a"</br>
>Output: 0</br>
>Explanation: t is already a subsequence of s ("abcde").

Example 3:

>Input: s = "z", t = "abcde"</br>
>Output: 5</br>
>Explanation: Append the characters "abcde" to the end of s so that s = "zabcde".</br>
>Now, t is a subsequence of s ("zabcde").</br>
>It can be shown that appending any 4 characters to the end of s will never make t a subsequence.

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Append-Characters-to-String-to-Make-Subsequence-LeetCode/assets/171427226/bf73791f-e053-4741-b0ac-66b2bdbb2f1f)

  Time complexity: O(min(sl, tl)).</br>Space complexity: O(1).
</div>

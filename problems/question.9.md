PALINDROME NUMBER

question-

Given an integer x, return true if x is a palindrome, and false otherwise.

 

Example 1:

Input: x = 121
Output: true
Explanation: 121 reads as 121 from left to right and from right to left.
Example 2:

Input: x = -121
Output: false
Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.



solution -

--------------- python3 ---------------

class Solution:
    def isPalindrome(self, x: int) -> bool:
        
        nums = str(x)
        reverse = nums[::-1]
        
        if (nums == reverse):
            return True
        else:
            return False



NUMBER OF COMMMON FACTORS

question-

Given two positive integers a and b, return the number of common factors of a and b.

An integer x is a common factor of a and b if x divides both a and b.

solution-

---------- python 3 ------------

class Solution:
    def commonFactors(self, a: int, b: int) -> int:
       cf = []
       
       for i in range (1,min(a,b)+1):
           if (a%i == 0) and (b%i == 0):
               cf.append(i)
       return len(cf)

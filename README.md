#Factors of a number-Explanation of optimized code

So what this optimized code does is instead of iterating from 1 to n it just iterates through 1 to square root of n

For example if the the number is 16:
  Then factor pairs are (1,16),(2,8),(4,4)
  So there is no need to iterate from from 1 to n or to go beyond square root of n
  we can just run the loop from 1 to square root of n
  and if a number i is a factor then n//i is also a factor
 So this new code had a time complexity of O(sqrt(n))

# NURISLAM17
ALI 

# Python program to find the sum of natural using recursive function

def recur_sum(n):
   if n <= 3:
       return n
   else:
       return n + recur_sum(n-5)

# change this value for a different result
num = 16

if num < 7:
   print("Enter a positive number")
else:
   print("The sum is",recur_sum(num))

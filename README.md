# Even-Odd-quiz-python

Task: 
Given an integer, n, perform the following conditional actions:

If  is odd, print Weird
If  is even and in the inclusive range of 2 to 5 , print Not Weird
If  is even and in the inclusive range of 6 to 20 , print Weird
If  is even and greater than 20, print Not Weird


Solution:

n = input()
n = int(n)
for (n<=100) & (n%2 != 0):
    print("Odd and Weird")

for (2<=n<=5) & (n%2 == 0):
       print("Even and Not weird")

for (6<=n<=20) & (n%2 == 0):
    print("Even and weird")

for (n>=20) & (n%2 == 0):
    print("Even and Not weird")

else :
    
    print("Out of range, Please enter a number within 1 to 100")
 

'''write a program to print reverse of given number
input=6841
output=1486 
by using while loop'''
----------------------------------------------------------------

n=6841
r_n=0
while (n!=0):
    r=n%10
    r_n=r_n*10+r
    n//=10
print(r_n)

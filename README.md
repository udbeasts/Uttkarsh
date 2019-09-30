# Uttkarsh
phython progress on 23 sept

#1)programme to all numbers between 2000 and 3200 which are divisible by 5 but are not multple of 5

a=2000
while(a<=3200):
    if(a%7==0 and a%5!=0):
       print(a)
    a+=1 
    
 #2)programme to create a factorial of a given no.

a=int(input("Enter a number to obtain factorial:"))
f=1
while(a!=0):
    f=f*a
    a-=1
     
print("Factorial of given number:",fact)     
     
#3)programme to print i,i*i with a given integral number

a=int(input("Enter a number:"))
n=1
while(n<=a):
    print(n,":",n*n)
    n+=1
    
#4)programme to print reverse of a number

n=int(input("Enter the number:"))
n2=0
r=0
while(n>0):
    r=n%10
    n2=(n2*10)+r
    n=int(n/10)
print("Reversed number is",n2)       

'''
#5)programme ton determine sum of n numbers whike n is entered  by the user

a=int(input("Enter a number:"))
n=0
k=0
while(n<a):
    k=k+n
    n=n+1
print("Sum of numbers till",a,"is :",n)    

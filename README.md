# Uttkarsh
phython progress on 23 sept

#1)programme to print all numbers between 2000 and 3200 which are divisible by 5 but are not multiple of 5

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

#6). program to print sum of n numbers(odd and even separately)

num=int(input("enter the number n : "))
k=0
odd=0 
even=0
while(k<=num):
    if(k%2==0):
        even+=k
    else:
        odd+=k
    k+=1
print("odd : ",odd )
print("even : ",even)


#7). program to print natural numbers in reverse

num=int(input("enter the number n : "))
while(num>0):
    print(num)
    num-=1


#8). program to print first and last digit of a number

num=int(input("enter number : "))
last=(num%10)
while(num>9):
    num=int(num/10)
print(num)
print(last)


#9). program to print product of first and last digit of a number

num=int(input("enter number : "))
last=(num%10)
while(num>9):
    num=int(num/10)
pro=int(last*num)
print("product : ",pro)


#10). program to print name of a single digit numbers
n=int(input("enter number of digits : "))
while(n>0):
    num=int(input("enter a single digit number : "))
    if(num==0):print(" ZERO ")
    if(num==1):print(" ONE ")
    if(num==2):print(" TWO ")
    if(num==3):print(" THREE ")
    if(num==4):print(" FOUR ")
    if(num==5):print(" FIVE ")
    if(num==6):print(" SIX ")
    if(num==7):print(" SEVEN ")
    if(num==8):print(" EIGHT ")
    if(num==9):print(" NINE ")
    n-=1

#11). program to print power of a number

num=int(input("enter a number : "))
power=int(input("enter the power : "))
num2=num
power2=power
while(power>1):
    num=num*num2
    power-=1
print(num2,"^",power2,"=",num)


#12). program to print if a number is prime or not

num=int(input("enter a number : "))
n=2
k=0
while(n<num):
    if(num%n==0):k=1
    n+=1
if(k==0):print(" PRIME ")
else:print(" NOT PRIME ")

    


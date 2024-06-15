# Python-week-1
Converting Input Strings
Write a program to convert strings to an integer and float and display its type.

Sample Input:

10
10.9

Code:

a=int(input())

b=float(input())

c=float(format(b,'.1f'))

print(a,',',type(a),sep="")

print(c,',',type(c),sep="") #Gross Salary

Ramesh’s basic salary is input through the keyboard. His dearness allowance is 40% of his basic salary, and his house rent allowance is 20% of his basic salary. Write a program to calculate his gross salary.

CODE:

s=int(input())

tot=s+(40/100s)+(20/100s)

print(int(tot)) #Square Root

Write a simple python program to find the square root of a given floating point number. The output should be displayed with 3 decimal places.

CODE:

a=float(input())

s=a**0.5

r=format(s,'.3f')

print(r)

#Gain percent

Alfred buys an old scooter for Rs. X and spends Rs. Y on its repairs. If he sells the scooter for Rs. Z (Z>X+Y). Write a program to help Alfred to find his gain percent. Get all the above-mentioned values through the keyboard and find the gain percent.

CODE:

x=int(input())

y=int(input())

z=int(input())

t=x+y

g=z-t

p=(g/t)*100

gp=format(p,'.2f')

print(gp,"is the gain percent.")

#Deposits

In many jurisdictions, a small deposit is added to drink containers to encourage people to recycle them. In one particular jurisdiction, drink containers holding one liter or less have a $0.10 deposit and drink containers holding more than one liter have a $0.25 deposit. Write a program that reads the number of containers of each size(less and more)  from the user. Your program should continue by computing and displaying the refund that will be received for returning those containers. Format the output so that it includes a dollar sign and always displays exactly two decimal places. CODE:

ns=int(input())

nl=int(input())

t=(ns0.10)+(nl0.25)

tot=format(t,'.2f')

print("Your total refund will be $",tot,".",sep="")

#Justin is a carpenter who works on an hourly basis. He works in a company where he is paid Rs 50 for an hour on weekdays and Rs 80 for an hour on weekends. He works 10 hrs more on weekdays than weekends. If the salary paid for him is given, write a program to find the number of hours he has worked on weekdays and weekends.

Hint:

If the final result(hrs) are in -ve convert that to +ve using abs() function

The abs() function returns the absolute value of the given number.

number = -20

OUTPUT:20

CODE:

sal=abs(int(input()))

ans=abs(sal-500)/130

k1=round(ans,2)

k2=round(ans,2)+10

print("weekdays",format(k2,'.2f'))

print("weekend",format(k1,'.2f'))

absolute_number = abs(number)

print(absolute_number)


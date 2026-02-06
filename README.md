# Assingment2
task3:
aim:to print given numbers is even or odd
description:
-take a number as input
-using if condtion statement check whether the number is even or not using formula:number%2==0
-if it is true then print given is number is even
-otherwise using else block if statement is false
-print as given number is odd
program:
n=int(input("enter number:"))
print("even") if n%2==0 else print("odd")
output:
enter number:6
even
enter number:5
odd
task4:
aim:to write a program on sum numbers using for loop
description:
-take total =0 at intial state
-using for loop print sum of numbers as: for i in range(1,51):
-add or total them using operation: total=toatal+i
-it will give sum of given numbers
-finally print sum of given numbers using print(toatal)
program:
total=0
for i in range(1,51):
    total=total+i
    print(total)

print(f"the sum of numbers from 1 to 50 is:{total}")
output:
the sum of numbers from 1 to 50 is:1275


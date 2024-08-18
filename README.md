#1 - Area of square
sideofsquare = int(input("Enter the side of a square: "))

area = sideofsquare*sideofsquare

print("Area of square: ", area)

#2 - Greater number true or false 
a = int(input("Enter a : "))
b = int(input("Enter b : "))

if(a >= b):
    print("True")
else:
    print("False")

#3 - Length of your name
name = input("Enter your name: ")
print("Length of your name is: ", len(name))

#4 - String count
str = "I bought $ is $$$ amount that you won't guess the $$$"
print(str.count("$"))

#5 - Even or Odd number 
num = int(input("Enter a number: "))
rem = num % 2
if(rem == 0):
     print("Even number")

else:
    print("Odd number")


#6 - Greatest number
num1 = int(input("Enter number 1 : "))
num2 = int(input("Enter number 2 : "))
num3 = int(input("Enter number 3 : "))

if(num1 > num2 & num1 > num3):
    print("num1 is greatest")
elif(num2 > num3):
    print("num2 is greatest")
else:
    print("num3 is greatest")


#6 - Multiple of 7 
num = int(input("Enter a number: "))
multiple = num % 7

if(multiple == 0):
    print("Multiple of 7")
else:
    print("Not a multiple of 7")


#7 - 
movies = []
mov1 = input(" Enter 1st movie: ")
mov2 = input(" Enter 2nd movie: ")
mov3 = input(" Enter 3rd movie: ")

movies.append(mov1)
movies.append(mov2)
movies.append(mov3)
print(movies)

#8 - Palindrome or not
list1 = [1,2,1]
list2 = [2,2,2]
list3 = ["m", "n", "a", "m"]

copy_list1 = list1.copy()
copy_list1.reverse()

if(copy_list1 == list1):
    print("Palindrome")
else:
    print("Not palindrome")

#9 - 

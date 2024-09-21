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

#9 - .count function
grade = ["C", "D", "A", "A", "B", "B", "A"]
print(" number of students that received A grade are:", grade.count("A"))

#10 - .sort() function
list = ["C", "D", "A", "A", "B", "B", "A"]
list.sort() # sorts the list in ascending order 
print(list)

#11 - 
English = {
    "Table" : {
        "Meaning 1" : "A piece of furniture",
        "Meaning 2" : "List of facts and figures"
    },
    "Cat" : "A small animal"
}

print(type(English))
print(English["Table"])
print(English["Cat"])


#12- length of the subjects 
subjects = { "Python", "Java", "C++", "Python", "Javascript", "Java", "Python", "Java", "C++", "C"}

print(len(subjects)) # Output will be 5 


#12 - 
marks = {}

x = int(input("Enter physics marks: "))
marks.update({"phy" : x})

x = int(input("Enter maths marks: "))
marks.update({"math": x})

x = int(input("Enter chemistry marks: "))
marks.update({"chem" : x})

print(marks)

#13 - sets
set = {9, "9.0"} #without using built-in data 
print(set)

set = {
    ("float", 9.0),
    ("int", 9)
}
print(set)

#14 - Print numbers from 1 to 100
i = 1
while i <= 100 :
    print(i)
    i += 1

#15 - Print numbers from 100 to 1
i = 100
while i >= 1 :
    print(i)
    i -= 1

#16- Print table 
table = int(input("Enter a number: "))
i = 1
while i <= 10 :
    print(i*table)
    i += 1

#17 - #Print the elements of the following list using a loop 
i = 1
while i <= 10:
    print(i*i)
    i += 1

num = [1,4,6,9,16,25,36,49,64,81,100]
idx = 0
while idx <= len(num):
    print(num[idx])
    idx += 1

#18- Print index 
num = [1,4,9,16,26,36,49,64,81,100]

x = 64
i = 0
while i < len(num):
    if(num[i] == x):
     print("Found at idx", i)
    i += 1
    
#19 - Print list
list = [1,4,9,16,25,36,49,64,81,100]

for num in list: 
    print(num)

#20 - Tuple
tup = (1,4,9,16,25,36,49,64,81,100)
x = 4

idx = 0
for ele in tup:
    if(ele == x):
        print("found at idx", idx)
        break 
    idx += 1

#21 - Printing numbers from 1-100 using ranges
for el in range(1,101):
    print(el)

#22 - Printing numbers in the reverse order that is from 100 to 1
for el in range (100, 0, -1):
    print(el)

#23 - Printing table of a number 
num = int(input("Enter a number: "))
for el in range(1,11):
    print(num * el)

#24- Sum of all the numbers 
sum = int(input("Enter a number: "))

add = 0
for i in range(1, sum+1):
    add +=i
   
print("Total sum = ",add)

#25 - Sum 
fact = int(input("Enter a number: "))
sum = 0
i = 1

while i <= fact:
    sum += i
    i += 1

print("Total sum = ", sum)

#26- 
num = int(input("Enter a number: "))
fact = 1

for i in range(1, num+1):
    fact *= i
print("Factorial = ", fact)

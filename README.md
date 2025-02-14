# python_assignment
python assignements
#Write a program to check if a given number is positive,negative, or zero.
number=int(input("enter any number:"))
print("*"*80)
print("\t \t \t using ifelse conditions")
print("*"*80)
if(number >0):
    print("{} number is postive number..? ".format(number))
    print("yes {} is postive number".format(number))
elif(number < 0):
    print("{} is negative number..? ".format(number))
    print("yes {} is negative number".format(number))


#Write a program to check if a given number is positive,negative, or zero.using functions
print("*"*80)
print("\t \t \t using function ")
print("*"*80)
def number():
    number = int(input("enter any number:"))
    if (number > 0):
        print("{} number is postive number..? ".format(number))
        print("yes {} is postive number".format(number))
    elif (number < 0):
        print("{} is negative number..? ".format(number))
        print("yes {} is negative number".format(number))
number()

#Write a program to check if a given number is positive,negative, or zero.using ternery operator
print("*"*80)
print("\t \t \t Ternery Operator")
print("*"*80)
number=int(input("enter any number:"))
result="postive number"if(number>0) else "negative number"
print("{} is {} ".format(number,result))
print("*"*80)


# output:
# -------------
# enter any number:12
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# 12 number is postive number..?
# yes 12 is postive number
# ********************************************************************************
#          using function
# ********************************************************************************
# enter any number:1
# 1 number is postive number..?
# yes 1 is postive number
# ********************************************************************************
#          Ternery Operator
# ********************************************************************************
# enter any number:-9
# -9 is negative number
# ********************************************************************************
# Determine if a number is odd or even.
number=int(input("enter a number to check given number is even or odd:"))
print("*"*80)
print("\t \t \t using ifelse conditions")
print("*"*80)
if(number%2==0):
    print("{} is even number".format(number))
elif(number%2!=0):
    print("{} is odd number".format(number))
print("*"*80)




# Determine if a number is odd or even.using functions
def even_odd():
    number = int(input("enter a number to check given number is even or odd:"))
    print("*" * 80)
    print("\t \t \t using functions")
    print("*" * 80)
    if (number % 2 == 0):
        print("{} is even number".format(number))
    elif (number % 2 != 0):
        print("{} is odd number".format(number))
even_odd()
print("*"*80)



#Write a program to check if a given number is positive,negative, or zero.using ternery operator
print("*"*80)
print("\t \t \t Ternery Operator")
print("*"*80)
number = int(input("enter a number to check given number is even or odd:"))
res="even_number"if(number%2==0)else"odd_number"
print("{} is {} ".format(number,res))
print("*"*80)




# output:-
# ---------
# enter a number to check given number is even or odd:5
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# 5 is odd number
# ********************************************************************************
# enter a number to check given number is even or odd:12
# ********************************************************************************
#          using functions
# ********************************************************************************
# 12 is even number
# ********************************************************************************
# ********************************************************************************
#          Ternery Operator
# ********************************************************************************
# enter a number to check given number is even or odd:96
# 96 is even_number
# ********************************************************************************

#Check if a person is eligible to vote (age >= 18).
print("*" * 80)
print("\t \t \t using ifelse conditions")
print("*" * 80)
person_age=int(input("enetr ur age:"))
if(person_age>18):
    print("{} u have eligible to caste ur vote".format(person_age))
    print("vote for trs")
elif(person_age<=18):
    print("{} u had not eligible to caste ur vote".format(person_age))
    print("better luck try get to nexttime")
print("*" * 80)



print("\t \t \t using functions")
print("*" * 80)
def vote():
    person_age = int(input("enetr ur age:"))
    if (person_age > 18):
        print("{} u have eligible to caste ur vote".format(person_age))
        print("vote for trs")
    elif (person_age <= 18):
        print("{} u had not eligible to caste ur vote".format(person_age))
        print("better luck try get to nexttime")
vote()


print("*"*80)
print("\t \t \t ternery operator")
print("*" * 80)
person_age=int(input("enetr ur age:"))
res=" u have eligible to caste ur vote"if(person_age>18)else" u had not eligible to caste ur vote"
print(res)
print("*"*80)


# output:-
# --------
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# enetr ur age:12
# 12 u had not eligible to caste ur vote
# better luck try get to nexttime
# ********************************************************************************
#          using functions
# ********************************************************************************
# enetr ur age:32
# 32 u have eligible to caste ur vote
# vote for trs
# ********************************************************************************
#          ternery operator
# ********************************************************************************
# enetr ur age:100
#  u have eligible to caste ur vote
# ********************************************************************************
# Write a program to find the greatest of two numbers.
print("*" * 80)
print("\t \t \t using ifelse conditions")
print("*" * 80)
teja_age = int(input("enter teja_age age:"))
sai_age  = int(input("enter sai_age age:"))
if (teja_age>sai_age):
    print("teja_age age is greatest")
elif (sai_age>teja_age):
    print("sai_age age is greatest")
elif (teja_age==sai_age):
    print("both ages are same ")
print("*" * 80)
print("\t \t \t using function")
print("*" * 80)
def greater():
    if (teja_age > sai_age):
        print("teja_age age is greatest")
    elif (sai_age > teja_age):
        print("sai_age age is greatest")
    elif (teja_age == sai_age):
        print("both ages are same ")
greater()


print("*" * 80)
print("\t \t \t ternery operator")
print("*" * 80)
str="teja_age age is greatest"if(sai_age>teja_age)else"sai_age age is greatest"
print(str)
print("*" * 80)

# output:
# -------
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# enter teja_age age:12
# enter sai_age age:34
# sai_age age is greatest
# ********************************************************************************
#          using function
# ********************************************************************************
# sai_age age is greatest
# ********************************************************************************
#          ternery operator
# ********************************************************************************
# teja_age age is greatest

# Print "Pass" if a student scores more than 40 marks;otherwise, print "Fail."
print("*" * 80)
print("\t \t \t using ifelse conditions")
print("*" * 80)
student_marks=int(input("enter student marks:"))
if(student_marks>40):
    print("u passed in all subjects with 1st class certified")
else:
    print("u failed in all subjects")
    print("wait for suppilmentery")


print("*" * 80)
print("\t \t \t using functions")
print("*" * 80)
def student():
    if (student_marks > 40):
        print("u passed in all subjects with 1st class certified")
    else:
        print("u failed in all subjects")
        print("wait for suppilmentery")
student()



print("*" * 80)
print("\t \t \t ternery")
print("*" * 80)
res="u passed in all subjects with 1st class certified"if(student_marks > 40) else"u failed in all subjects  wait for suppilmentery"
print(res)

# output:-
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# enter student marks:20
# u failed in all subjects
# wait for suppilmentery
# ********************************************************************************
#          using functions
# ********************************************************************************
# u failed in all subjects
# wait for suppilmentery
# ********************************************************************************
#          ternery
# ********************************************************************************
# u failed in all subjects  wait for suppilmentery

# Write a program to display the day of the week based on a number input (1 for Monday, 2 for Tuesday, etc.).
print("*" * 80)
print("\t \t \t using match_case conditions")
print("*" * 80)
day=input("enter which day u want:")
match day:
    case  "MONDAY"|"monday":
        print("{} is Return to 10k institute classes ".format(day))
    case "TUESDAY"|"tuesday":
        print("{} is to complete our mocks ".format(day))
    case "WEDNESDAY"|"wednesday":
        print("{} is to complete our projects ".format(day))
    case "THURSDAY"|"thursday":
        print("{} time to submit projects ".format(day))
    case "FRIDAY"|"friday":
        print("{} planning for weekoff".format(day))
    case "SATURDAY"|"saturday":
        print("{} planning for trip ".format(day))
    case "SUNDAY"|"sunday":
        print("{} is rest ".format(day))
    case _:
        print("please enter vaild day")



print("*" * 80)
print("\t \t \t using if_else conditions")
print("*" * 80)
day=input("enter which day u want:").lower()
if(day=="maonday"):
    print("{} is Return to 10k institute classes ".format(day))
elif(day=="tuesday"):
    print("{} is to complete our mocks ".format(day))
elif(day=="wednesday"):
    print("{} is to complete our projects ".format(day))
elif(day=="thursday"):
    print("{} time to submit projects ".format(day))
elif(day=="friday"):
    print("{} planning for weekoff".format(day))
elif(day=="saturday"):
    print("{} planning for trip ".format(day))
elif(day=="sunday"):
    print("{} is rest ".format(day))
else:
    print("please enter vaild day")



print("*" * 80)
print("\t \t \t using function")
print("*" * 80)
day=input("enter which day u want:").lower()
def days():
    if (day == "maonday"):
        print("{} is Return to 10k institute classes ".format(day))
    elif (day == "tuesday"):
        print("{} is to complete our mocks ".format(day))
    elif (day == "wednesday"):
        print("{} is to complete our projects ".format(day))
    elif (day == "thursday"):
        print("{} time to submit projects ".format(day))
    elif (day == "friday"):
        print("{} planning for weekoff".format(day))
    elif (day == "saturday"):
        print("{} planning for trip ".format(day))
    elif (day == "sunday"):
        print("{} is rest ".format(day))
    else:
        print("please enter vaild day")
days()


print("*" * 80)
print("\t \t \t ternery operator")
print("*" * 80)
day = input("Enter which day you want: ").lower()  # Only converting to lowercase

days = ("Return to 10k institute classes" if day == "tuesday" else
        "Complete our mocks" if day == "wednesday" else
        "Complete our projects" if day == "thursday" else
        "Time to submit projects" if day == "friday" else
        "Planning for weekoff" if day == "saturday" else
        "Is rest" if day == "sunday" else
        "Is rest" if day == "ahdfjkhdjfllksrhtuo" else
        "Please enter a valid day")

print(days)


# output:-
# --------
# ********************************************************************************
#          using match_case conditions
# ********************************************************************************
# enter which day u want:sunday
# sunday is rest
# ********************************************************************************
#          using if_else conditions
# ********************************************************************************
# enter which day u want:SUNday
# sunday is rest
# ********************************************************************************
#          using function
# ********************************************************************************
# enter which day u want:sunDAY
# sunday is rest
# ********************************************************************************
#          ternery operator
# ********************************************************************************
# Enter which day you want: SUNDAY
# Is rest










# Implement a simple calculator to perform addition,subtraction, multiplication, and division.
opetator=input("which operator u want to perform:").lower()
a=float(input("enter the value of a:"))
b=float(input("enter the value of b:"))
if(opetator=="add"):
    print("the sum of {} and {} ={}".format(a,b,a+b))
elif(opetator=="sub"):
    print("the sum of {} and {} ={}".format(a, b, a - b))
elif(opetator=="mul"):
    print("the sum of {} and {} ={}".format(a, b, a * b))
elif(opetator=="modulo"):
    print("the sum of {} and {} ={}".format(a, b, a % b))
elif(opetator=="div"):
    str="ZeroDivisionError"if(b==0)else(a/b)
    print(str)
else:
    print("invalid data")


# output:-
# --------
# which operator u want to perform:AdD
# enter the value of a:12
# enter the value of b:45
# the sum of 12.0 and 45.0 =57.0







#Write a program to display the name of a month based on the month number
# (1 for January, 2 for February, etc.).
month_name=int(input("enter with number u want:"))
print("*" * 80)
print("\t \t \t using ifelse conditions")
print("*" * 80)
if(month_name==1):
    print("{}-----------jan is the first month".format(month_name))
elif(month_name==2):
    print("{}-----------feb is the second month".format(month_name))
elif(month_name==3):
    print("{}-----------mar is the third month".format(month_name))
elif(month_name==4):
    print("{}-----------apr is the forth month".format(month_name))
elif(month_name==5):
    print("{}-----------may is the fivth month".format(month_name))
elif(month_name==6):
    print("{}-----------jun is the six month".format(month_name))
elif(month_name==7):
    print("{}-----------july is the seventh month".format(month_name))
elif(month_name==8):
    print("{}-----------agu is the eighth month".format(month_name))
elif(month_name==9):
    print("{}-----------sep is the ninth month".format(month_name))
elif(month_name==10):
    print("{}-----------oct is the tenth month".format(month_name))
elif(month_name==11):
    print("{}-----------nov is the eleventh month".format(month_name))
elif(month_name==12):
    print("{}-----------dec is the twelve month".format(month_name))
else:
    print("please enter vaild month")




print("*" * 80)
print("\t \t \t using function")
print("*" * 80)
def month():
    if (month_name == 1):
        print("{}-----------jan is the first month".format(month_name))
    elif (month_name == 2):
        print("{}-----------feb is the second month".format(month_name))
    elif (month_name == 3):
        print("{}-----------mar is the third month".format(month_name))
    elif (month_name == 4):
        print("{}-----------apr is the forth month".format(month_name))
    elif (month_name == 5):
        print("{}-----------may is the fivth month".format(month_name))
    elif (month_name == 6):
        print("{}-----------jun is the six month".format(month_name))
    elif (month_name == 7):
        print("{}-----------july is the seventh month".format(month_name))
    elif (month_name == 8):
        print("{}-----------agu is the eighth month".format(month_name))
    elif (month_name == 9):
        print("{}-----------sep is the ninth month".format(month_name))
    elif (month_name == 10):
        print("{}-----------oct is the tenth month".format(month_name))
    elif (month_name == 11):
        print("{}-----------nov is the eleventh month".format(month_name))
    elif (month_name == 12):
        print("{}-----------dec is the twelve month".format(month_name))
    else:
        print("please enter vaild month")
month()





print("*" * 80)
print("\t \t \t ternery op")
print("*" * 80)
month_name = int(input("Enter month number (1-12): "))

print(f"{month_name}-----------" + (
    "Jan is the first month" if month_name == 1 else
    "Feb is the second month" if month_name == 2 else
    "Mar is the third month" if month_name == 3 else
    "Apr is the fourth month" if month_name == 4 else
    "May is the fifth month" if month_name == 5 else
    "Jun is the sixth month" if month_name == 6 else
    "July is the seventh month" if month_name == 7 else
    "Aug is the eighth month" if month_name == 8 else
    "Sep is the ninth month" if month_name == 9 else
    "Oct is the tenth month" if month_name == 10 else
    "Nov is the eleventh month" if month_name == 11 else
    "Dec is the twelfth month" if month_name == 12 else
    "Please enter a valid month"
))
print("*" * 80)


# output:
# -------
#
# enter with number u want:11
# ********************************************************************************
#          using ifelse conditions
# ********************************************************************************
# 11-----------nov is the eleventh month
# ********************************************************************************
#          using function
# ********************************************************************************
# 11-----------nov is the eleventh month
# ********************************************************************************
#          ternery op
# ********************************************************************************
# Enter month number (1-12): 11
# 11-----------Nov is the eleventh month
# ********************************************************************************
#Write a program to find the greatest of three numbers.
print("*"*80)
print("\t \t \t ifelse condition")
print("*"*80)
a=int(input("eneter the value of a:"))
b=int(input("eneter the value of b:"))
c=int(input("eneter the value of c:"))
if(a>b and a>c):
    print("{} is greater".format(a))
elif(b>a and b>c):
    print("{} is greater".format(b))
elif(c>a and c>b):
    print("{} is greater".format(c))
else:
    print("flase")
print("*"*80)





print("\t \t \t functions ")
print("*"*80)
a=int(input("eneter the value of a:"))
b=int(input("eneter the value of b:"))
c=int(input("eneter the value of c:"))
def greater():
    if (a > b and a > c):
        return ("{} is greater".format(a))
    elif (b > a and b > c):
        return ("{} is greater".format(b))
    elif (c > a and c > b):
        return ("{} is greater".format(c))
    else:
        return ("flase")
print(greater())
print("*"*80)






print("\t \t \t ifelse condition")
print("*"*80)
a=int(input("eneter the value of a:"))
b=int(input("eneter the value of b:"))
c=int(input("eneter the value of c:"))
res = f"{a} is greatest" if (a > b and a > c) else f"{b} is greatest" if (b > a and b > c) else f"{c} is greatest" if (c > a and c > b) else "Values are equal or not distinct"
print(res)
print("*"*80)


# output:-
# -------
# ********************************************************************************
#          ifelse condition
# ********************************************************************************
# eneter the value of a:11
# eneter the value of b:11
# eneter the value of c:11
# flase
# ********************************************************************************
#          functions
# ********************************************************************************
# eneter the value of a:11
# eneter the value of b:11
# eneter the value of c:11
# flase
# ********************************************************************************
#          ifelse condition
# ********************************************************************************
# eneter the value of a:11
# eneter the value of b:11
# eneter the value of c:11
# Values are equal or not distinct

#Check if a year is a leap year.
year=int(input("Enter the year:"))
print("*"*80)
print("\t \t \t ifelse condition")
print("*"*80)
if(year%400==0)or(year%4==0 and year%100!=0):
    print(year," is laep year")
else:
    print(year, " is not laep year")



print("*"*80)
print("\t \t \t functions")
print("*"*80)
def leapyear():
    if(year%400==0)or(year%4==0 and year%100!=0):
        return year,"is leap year"
    return year,"is not a leap year"
print(leapyear())

print("*"*80)
print("\t \t \t tenery operator")
print("*"*80)
print(year,"is leap year")if(year%400==0)or(year%4==0 and year%100!=0)else print(year,"is not a leap year")
print("*"*80)


# output:-
# -------------
# Enter the year:2023
# ********************************************************************************
#          ifelse condition
# ********************************************************************************
# 2023  is not laep year
# ********************************************************************************
#          functions
# ********************************************************************************
# (2023, 'is not a leap year') output is tuple because arguments are their more than 1
# ********************************************************************************
#          tenery operator
# ********************************************************************************
# 2023 is not a leap year
# ********************************************************************************


#Calculate the grade of a student based on the marks they
# score:
# 1. 90-100: Grade A
# 2. 80-89: Grade B
# 3. 70-79: Grade C
# 4. <70: Fail.
print("*"*80)
print("\t \t \t ifelse condition")
print("*"*80)
student_grade=int(input("enter ur grade:"))
if(student_grade>=100):
    print("Grade-A")
elif(student_grade>90):
    print("Grade-B")
elif(student_grade>80):
    print("Grade-c")
elif(student_grade<70):
    print("Fail")
print("*"*80)
print("\t \t \t function ")
print("*"*80)
def student(student_grade):
    if (student_grade >= 100):
        return ("Grade-A")
    elif (student_grade > 90):
        return("Grade-B")
    elif (student_grade > 80):
        return("Grade-c")
    elif (student_grade < 70):
        return("Fail")
    print("*" * 80)
print(student(student_grade))


# output:-
# ---------
#
# ********************************************************************************
#          ifelse condition
# ********************************************************************************
# enter ur grade:100
# Grade-A
# ********************************************************************************
#          function
# ********************************************************************************
# Grade-A


# Write a program to check if three sides length form a valid triangle.
# condition  a+b>c and a=c>b and b+a>c
print("*"*80)
print("\t \t \t ifelse condition")
print("*"*80)
a=int(input("enter the triangle value of a:"))
b=int(input("enter the triangle value of b:"))
c=int(input("enter the triangle value of c:"))
if(a+b>c):
    print("valid triangle")
elif(a+c>b):
    print("valid triangle")
elif(b+c>a):
    print("valid triangle")
else:
    print("not_valid triangle")
print("*"*80)




print("*"*80)
print("\t \t \t using functions")
print("*"*80)
a=int(input("enter the triangle value of a:"))
b=int(input("enter the triangle value of b:"))
c=int(input("enter the triangle value of c:"))
def triangle():
    if (a + b > c):
        return ("valid triangle")
    elif (a + c > b):
       return ("valid triangle")
    elif (b + c > a):
        return("valid triangle")
    else:
        return("not_valid triangle")
print(triangle())
print("*"*80)





print("\t \t \t ternery op")
print("*"*80)
a=int(input("enter the triangle value of a:"))
b=int(input("enter the triangle value of b:"))
c=int(input("enter the triangle value of c:"))
res="valid triangle"if( a+b>c and a+c>b and b+a>c )else"not_vaild triangle"
print(res)
print("*"*80)



#Print all numbers from 1 to 100 using a for loop
print("*"*80)
print("\t \t using for_loop")
print("*"*80)
for i in range(1,101):
    print(i,end=" ")

#Write a program to print the sum of the first n natural numbers. (n*n+1/ 2)
number=int(input("enter ur numbers:"))
sum=0
for i in range(1,number+1):
    sum=(number*number+1)/2
print(sum,end=" ")


# Print all even numbers between 1 and 50 using a while loop.
number=int(input("enter u number:"))
while(number<=50):
    print(number,end=" ")
    number+=2

#
# output:-
# ---------
# enter u number:2
# 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30 32 34 36 38 40 42 44 46 48 50



# Write a program to display the multiplication table of a given number. First 20
num=int(input("enter which table u want:"))
print("*"*30)
for i in range(1,11):
    print("{} x {} ={}".format(num,i,num*i))
print("*"*30)

# Reverse a number using a while loop.
# Also can we get the sum of all the digits.
num=int(input("enter ur number:"))
sum=0
while(num>0):
    num -= 1
    sum+=num
print(sum,end=" ")



# output:-
# ----------
# enter ur number:10
# 9 8 7 6 5 4 3 2 1 0


# enter ur number:10
# 45

#Write a program to count the number of digits in a given ,number using a while loop.
num=[2,3,4,5,2,5,7,9,3,5,3,3]
op=num.count(3)
print(op)

# Write a program that keeps asking the user to enter numbers
# until they enter a negative number. Use a while loop.
# num=int(input("enter ur number:"))
# if(num<0):
#     print("please enter vaild number")
# while(num>0):
#     num = num + 2
#     print("{} u enter vaild number".format(num))



while(True):
    num = int(input("enter ur number:"))
    if (num <= 0):
        print("{} please enter vaild number".format(num))
        break
    else:
        print("{} u enter vaild number".format(num))
print("thnak you!")


# output:-
# ---------
# enter ur number:12
# 12 u enter vaild number
# enter ur number:10
# 10 u enter vaild number
# enter ur number:33
# 33 u enter vaild number
# enter ur number:56
# 56 u enter vaild number
# enter ur number:-9
# -9 please enter vaild number
# thnak you!

num=89
while(num>0):
    ip=int(input("enter a number:"))
    print(ip,"enter vaild number")


# Write a program to display the multiplication table of a given number. First 20
number=int(input("enter table from which number u do want:"))
end=int(input("enter up which table u want to stop:"))
for i in range(number,end+1):
    print("*"*10)
    print("table",i)
    print("*" * 10)
    for j in range(1,11):
        print("{} x {} ={}".format(i,j,i*j))


# Print all numbers from 1 to 100 that are divisible by 3 and 5
# using a for loop
for i in range(1,101):
    if(i%3==0 and i%5==0):
        print(i,end=" ")

# output:-
# ----------
# 15 30 45 60 75 90 


# implement a menu-driven program where the user can
# choose to:
# 1. Find the square of a number.
# 2. Find the cube of a number.
# 3. Exit
print("*"*80)
print("menu-driven")
print("*"*80)
print("\t \t find the square of number")
print("\t \t find the cube of number")
print("*"*80)
while(True):

    ch=int(input("enter u choice:"))
    if(ch==1):
        print("u enter the find the square of the number")
        num=int(input("enter ur number:"))
        print("square root of the number is {}={}".format(num,num**2))
        print("*" * 80)
    if(ch==2):
        print("u enter the find the cube of the number")
        num = int(input("enter ur number:"))
        print("cube root of the number is {}={}".format(num,num ** 3))
        print("*" * 80)

    if(ch==3):
        num=input("enter ur number:")
        print("please exist from this menu")
        print("*" * 80)

    else:
        print("thank vist again")
        print("*" * 80)











# implement a basic login system where the user has three
# attempts to enter the correct password using a loop
for i in range(1,4):
    user_password="Tarunsai@12345"
    password=input("enter password:")
    if(password==user_password):
        print(" ur password is matched")
        break
    else:
        print(" ur password is invaild please try again")





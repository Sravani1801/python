# python
A brief repo on python language
python is a user friendly language
some basic topics of python language
extension of python program file is .py


Basic hello world python program:
print("Hello World!)
OUTPUT:Hello World!


comments in python:
they do not appear in console
they are defined with '#'
example:
#it's just a comment
print("sravani")
OUTPUT: sravani


LIST:
char = ["john","peter"]
print(char[0])
OUTPUT: 'john'

TUPLE:
num = [1,2,3]
print(num[2])
OUTPUT: 3
tuples can't be modified, but lists can be modified

IF:
a=1
if a>0:
    print(a is a positive number)
elif a<0:
    print(a is a negative number)
else:
    print(a is a zero)
OUTPUT: a is a positive number

EXPONENT and FOR:
def power_of_num(base,power):
    result=1
    for index in range(power):
        result=result * base
    return result
print(power_of_num(2,4))
OUTPUT: 16


TWO DIMENSIONAL LIST AND NESTED FOR LOOP:
num_grid=[
      [1,2]
      [3,4]
]
for row in num_grid
    for col in row:
        print(col)
OUTPUT: 1
        2
        3
        4


BUILDING A TRANSLATOR:
def translate(phrase):
    translation=""
    for letter in phrase:
        if letter.lower in "aeiou":
            if letter.isupper():
                translation = translate + "S"
            else:
                translation = translate + "s"
        else:
            translation = translation + letter
     return translation
 print(translate("Endless Life"))
 OUTPUT: Sndlsss Lsfs
 
 
TRY EXCEPT:
#it catches errors
try:
    result = 7/0
    num = int(input("enter a number: "))
    print(num)
except dividedbyzeroerror:
    print("division by zero")
except ValueError:
    print("invalid input")
OUTPUT: division by zero


Reading files:
if there exists a seperate file called students_list from which we need information, format for opening and reading that file is :
open("students_list","r")


we can also write/append to files:
for appending:
list_of_students = open("students_list" , "a")
students_list.write("abhigna - ECE")
students_list.close()


we can also create new files:
list_of_students = open("styles.css" , "a")
styles.css.write("it's just styling the webpage")
styles.css.close()


MODULES:
we export other files where we can use functions from other files.
import user_list
print(user_list.branch)
user_list is a file



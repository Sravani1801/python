# python
A brief repo on python language
python is a user friendly language
some basic topics of python language
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



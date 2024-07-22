# Python-Data-Science

# Python 
Python is invented by Guido van Rossum in the year 1993.

- Python is the most powerful language and it is a high-level, general-purpose programming language. 

- Python is used for develop web applications.

#Basic Concepts

    - Data Types
    
    - Variables
    
    - Operators
    
    - Print Conditions
#Data Types

    - integer(int)

    - float(float)
    
    - string(str)

Interger-35->4 bytes ,1 byte=8 bits

Float-55.5->4 bytes

String-'roja->1 character=1byte

#Variables-Memory location used to store data types.

- String Version 1

    """Python"""

- String Version 2

    ""Python""

- String Version 3

     'Python'

#Rules to create a variable:

Rule 1 : Variable should not start with a number if you want to start please use underscore.

    Ex:- _9a=100

Rule 2 : Variable should be single word or a single character but not multiple words if you want please use underscore.

    Ex:- sai_kumar=800

Rule 3 : Python variables are commonly case sensitive 

    Ex:- city='hyd
       
         print(city)

Rule 4 : Please don't use below punctuations as a variable

   punctuations : !"#$%&'()*+, -./:;<=>?@[\]^_`{|}~

#Operators : Operators are used to perform operations on variables and values.

-> +.-,*,/,//,%,**,pow,>,<,>=,<=,=,==,!=,and,or

1. Addition(+):

        Ex:- a=10
             b=20
             print(a+b)

2. Substraction(-):

         Ex:- a=20
              b=10
              print(a-b)

3. Multiplication(*):
    
        Ex:- a=5
             b=6
            print(a*b)

4. Division(/):
 
        Ex:- a=20
             b=5
             print(a/b)
    
5. Floor Division(//):

        Ex:- a=20
             b=5
             print(a/b)
        
6. Modulo Division(%):

        Ex:- a=23
             b=4
             print(a%b)

7. Power(**):

        Ex:- a=2
             b=3
             print(a**b)

8. Power(Built_in_Function):

        Ex 1:- pow(2,5)

        Ex 2:- pow(4,3,5)
               ((4*4*4)%5)

9. Greater(>):

        Ex:- a=10
             b=5
             print(a>b)

10. Lesser(<):

        Ex:- a=10
             b=5
             print(a<b)

11. Greater than or equal to(>=):
  
        Ex:- a=10
             b=5
             print(a>=b)

12. Less than or equal to(<=):
 
        Ex:- a=10
             b=5
             print(a<=b)

13. Equals to(=):
 
        Ex:- a=10
             print(a)

14. Double equals to(==):
   
        Ex:- a=10
             b=10
             print(a==b)

15. Not equal(!=):
   
        Ex:- a=10
             b=5
             print(a!=b)

16. and operator:

    Conditions:

         t  t  ->  t
         f  f  ->  f
         t  f  ->  f
         f  t  ->  f
        Ex:- 10 >= 11 and 20 <= 32 

17. or opeartor:

    Conditions:
        
        t   t  ->  t
        f   f  ->  f
        t   f  ->  t
        f   t  ->  t 
        Ex:- 10 >= 11 or 20 <= 32

#Relation with print and variables:

1. Using ,(comma) we can add one data type inside the print with other data type and also comma will give one tab space. 

        Ex 1:- a = 27
               print('my age is',a)
    
    #I am at the age of',a,'staying in usa and earning 90.22 thousand dollars per year
        
        Ex 2:- a=45
            b='usa'
            c=90.22
            print('I am at the age of',a,'staying in usa and earning 90.22 thousand dollars per year')      

#Type Conversions:
    
    * int   -> float
    * float -> int
    * str   -> int
    * int   -> str
    * float -> str
    * str   -> float

2. Using + we can add string data type along with given variables  but make sure that variables are also string and + operator won't give tab space.
    
        Ex:- a=27
         print('my age is' +str(a))

3. Using Identifiers: %d -> int , %f -> float , %s -> str
        
         Ex:- a=21
         print('my age is %d' %(a)

4. Using { } anf f function.
        
        Ex:- a=21
         print(f'my age is {a}')
# Data Types

1.String

2.List

3.Tuple

4.set

5.Dictionary

# String
String is represented with ' ' or " " or """ """

    Ex:- 'Python is very powerful language'

1.Memory Allocation

2.Indexing

3.Slicing

4.Skipping

5.Mutable or Immutable

6.Built in Functions

## 1.Memory Allocation
Memory allocation can be defined as allocating a block of space in the computer memory to a program.

    Ex:-  a='data'

## 2.Indexing
Indexing is the process of accessing an element in a sequence using its position in the sequence (its index).

In Python, indexing starts from 0, which means the first element in a sequence is at position 0, the second element is at position 1, and so on.

It is having two indexing types.

1.Forward Indexing

2.Backward Indexing

    Ex:- a='data' 
* In data d having 0 th index , a having 1 st index and so on.(Forward Index)

*In data d having -4 th  index , a having -3 rd index and so on.(Backward Index)

## 3.Slicing
Access range of characters

Syntax:- Starting point : Ending point (n-1) logic

    Ex:- a='data science'
         print([2:8])
    o/p:- ta sci
## 4.Skipping
syntax:- Staring Point : Ending Point : Skipping value

* It counts Starting value also 
 
      Ex: a='data science'
          print(a[::2])
      o/p: dt cec
## 5.Mutable/Immutable
*Mutable means if user can Increase or decrease memory.

*Immutable means user can't Increase or decrease memory.
 
    Ex:- #Delete
    a='Kiran
    del a[2] # trying to delete character
    print(a)
    o/p:- Error-str object doesn't support item

    #Add character
    a='kiran'
    a[5]=j
    print(a)
    o/p:- Error
From the above outcomes we can say that String is Immmutable.

## 6.Built_in_functions
*Capitalize

*lower

*upper

*title

*islower

*isupper

*startswith

*endswith

*isalpha

*isnumeric

*isalnum

*count

*index

*replace

*len

*ascii

### Capitalize : It will capital the starting letter.
    Ex:- a='Python is very poweRfull language'
         a=a.capitalize()
         print(a)
    o/p:-Python is very powerful language

### title : It will capital each word starting letter into capital.
    Ex:- a='python is Easy language'
         a=a.title()
         print(a)
    o/p:- Python Is Easy Language
### lower : Convert capital letters into small letters
    Ex:- a='AmeriCA'
         a=a.lower()
         print(a)
    o/p:- america
### upper : Convert small letters into capital letters
    Ex:- a='AmeriCA'
         a=a.upper()
         print(a)
    o/p:- AMERICA
### islower : Checking whether it is small or not (Output as Boolean type)
    Ex:- a='AmeriCA'
         print(a.islower())
    o/p:- False
### isupper : Checking whether it is capital or not
    Ex:- a='AMERICA'
         print(a.isupper())
    o/p:- True
### is alpha : Checking all are alphabets or not
    Ex 1:- a='america123'
         print(a.isalpha())
    o/p:- False
    Ex 2:- a='america'
           print(a.isalpha())
    o/p:- True
### isnumeric : Checking all are numbers or not
    Ex:- a='Python123'
         print(a.isnumeric())
    o/p:- False
### isalnum : Anything like text or number
    Ex:- a='python'
         print(a.isalnum())
    o/p:- True
### startswith : Checking start with the particular character or not.
    Ex:- a='data science'
         print(a.startswith('d'))
    o/p:- True
### endswith : Checking end with the particular character or not
    Ex:- a='data science'
         print(a.endswith('E))
    o/p:- False
### replace : We can replace but we don't incrase/decreasein strings
    Ex:- a='kiran'
         print(a.replace('r','j'))
    o/p:- kijan
### count : used to count the number of times a given character repeating
    Ex:- a='data science'
         print(a.count('e'))
    o/p:- 2
### index : used to find the index of a given character
    Ex:- a='kiran'
         print(a.index('r'))
    o/p:- 2
### substring and string : 
    Ex:- a='python is very powerful language'
         print('is' in a)
    o/p:- True
### len : find length of the string
    Ex:- a='kiran'
         print(len(a))
    o/p:- 5
### Ascii-> American Standard Code for Information
    Ex:- python='ab'-> 97*98=9506
         java='CD'-> 67*68=4556
         print(python > java)
    o/p:- True
* ord gives ascii value for the particular character
    
      Ex:- ord('d')
      o/p:- 100

* chr gives character for the particular ascii value 
    
      Ex:-chr(70)
      o/p:- 'f'




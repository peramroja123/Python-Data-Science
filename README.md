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





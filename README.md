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

# List
*Python list is going to accept any data types like int, float, string, boolean.

*Python list is going to represent with [].

    Ex:- a=[10,55.55,'data']
          print(a)
    o/p:- [10,55.55,'data']

### 1.Memory Allocation
    Ex:- a=[10,20,30]
         print(a)
    o/p:-[10,20,30]
### 2.Indexing
    Ex:-a=[10,15,19,3,7,32,17]
        print(a[4])
    o/p:-7
### 3.Slicing
    Ex:-print(a[2:5])
    o/p:- [19,3,7]
### 4.Skipping
    Ex 1:-a=[10,15,19,3,7,32,17]
          print(a[::2])
    o/p:- [10,19,7,17]
    Ex 2:-a=[10,15,19,3,7,32,17]
          print(a[::-1])
    o/p:-[17,32,7,3,19,15,10]
### 5.Mutable/Immutable
list is mutable it can be modified the elements and also elements can be replaced.
#### add
    Ex:- a=[10,50,3,13]
         a[4]=500
         print(a)
    o/p:- [10,50,3,13,500]
### Built_in_Function
* append
* extend
* insert
* pop
* remove
* count
* index
* copy
* clear
* sort
* reverse
### append : It will take the single value from the user and will add the existing list only at the end.
    
    Ex:-a=[10,50,3,13]
        a.append(500)
        print(a)
    o/p:-[10,50,3,13,500]
### extend : It will take multiple values from the user and add to the excisting list only at the end.
    
    Ex:-a=[10,50,3,13]
        a.extend([1,2])
        print(a)
    o/p:-[10,50,3,13,1,2]
### insert : We can add values where ever we want.

    Ex:-a=[10,50,3,13]
        a.insert(2,300)
        print(a)
    o/p:-[10,50,300,3,13]
### pop : pop will remove last value defaulty but if we pass a number it wull treat like index.
  
    Ex:-a=[10,50,3,13]
        a.pop()
        print(a)
    o/p:-[10,50,3]
### remove : will takes value directly and remove the value

    Ex:-a=[10,50,3,13]
        a.reove(50)
        print(a)
    o/p:-[10,3,13]
### replace : replace the value

    Ex:-a=[10,50,3,13]
        a[1]=5
        print(a)
    o/p:-[10,5,3,13]
### count : used to count the values

    Ex:-a=[1,2,4,5,1,3,19,30,1]
        print(a.count())
    o/p:- 3
### index : used to find the index of a given value

    Ex:-a=[1,2,4,5,1,3,19,30,1]
        print(a.index())
    o/p:- 6
### clear : just delete the data in variable but variable will be alive in the memory

    Ex:-a=[1,2,4,5]
        a.clear()
        print(a)
    o/p:-[]
### copy -> There are 2 types of copy techniques
1) deep copy
2) shallow copy

#### 1.deep copy:
    Ex 1:-a=[10,20,50]
        b=a
        print(a)
        print(b)
    o/p:-[10,20,50]
         [10,20,50]
    
    Ex 2:-a=[10,20,50]
          b=a
          print(a)
          print(b)
          a.append(100)
          print(a)
          print(b)
    o/p:-[10,20,50]
         [10,20,50]
         [10,20,50,100]
         [10,20,50,100]
#### 2.shallow copy:
    Ex 1:-a=[10,20,50]
          b=a.copy()
          print(a)
          print(b)
          a.append(100)
          print(a)
          print(b)
    o/p:- [10,20,50]
          [10,20,50]
          [10,20,50,100]
          [10,20,50]
### sort : Ascending order and descending order
   *Ascending order:
      
    Ex:-a=[9,1,5,7,11,13,6,2,8]
        a.sort()
        print(a)
    o/p:- [1,2,5,6,7,8,9,11,13]
   
   *Descending order:
    
    Ex:-a=[9,1,5,7,11,13,6,2,8]
        a.sort(reverse = True)
        print(a)
    o/p:- [13,11,9,8,7,6,5,2,1]
### reverse : 
    Ex:-a=[10,20,30,40,50]
        a.reverse()
        print(a)
    o/p:-[50,40,30,20,10]
## Tuple
* User can pass anything inside the tuple.
* Tuple can be represented with paranthesis().
### Mewmory allocation:
   
    Ex:-a=(10,55.55,'data')
        print(type(a))
    o/p:-Tuple
### Indexing :

    Ex:-a=(10,4,17,9,21,36)
        print(a[2])
    o/p:-17
### Slicing:
   
    Ex:-a=(10,4,17,9,21,36)
        print(a[1:4])
    o/p:-(4,17,9)
### Skipping:

    Ex:-a=(10,4,17,9,21,36)
        print(a[::3])
    o/p:-(10,9)
#### add: 
    Ex:-a=(10,4,17,9,21,36)
        a[6]=500
        print(a)
    o/p:- It will show error
#### del:
    Ex:-a=(10,4,17,9,21,36)
        del(a[4])
        print(a)
    o/p:-It will show error
#### From the above sources we got to know that tuple is Immutable.
## Built_in_functions
*count

*index

### 1)count:
    Ex:-a=(10,4,17,9,21,36)
        print(a.count(4))
    o/p:-1
### 2)index:
    Ex:-a=(10,4,17,9,21,36)
        print(a.index(17))
    o/p:-2
# sets
Sets are represented with {}
and python sets are unordered pairs(which means there will be no index concept in sets and no slicing & skipping)

    Ex:- a={10,55.55,'data',(1,2,3)}
         print(a)
    o/p:- {'data',10,(1,2,3),55.55}
* python sets won't allow duplicate values.

      Ex:- a = {10,20,30,50,10,100,20,10}
            print(a)
        o/p :- {50,100,20,10,30}
* Python sets are mutable but they won't allow mutable types inside it.

      Ex:- a={10,55.55,'data',[1,2,3]}
           print(a)
      o/p:- It is showing error 

## Built-in-Functions
* add
* update
* pop
* discard
* remove
* clear
* copy
* union
* intersection
## add : Will take one input from the user and add to existing list randomly
    Ex:- a={10,5,6,20,98,45}
         print(f'Before adding:{a}')
         a.add(600)
         print(f'After adding:{a}')

    o/p:- Before adding: {98,20,5,6,10,45}
      After adding: {98,20,5,6,600,10,45}

## update : Will take multiple values from the user and add to the existing list randomly

    Ex:- a={10,5,6,20,98,45}
         print(f'Before:{a}')
         a.update([100,200,300])
         print(f'After:{a}')

    o/p:- Before : {98,20,5,6,10,45}
          After : {5,6,200,10,20,98,100,300,45}
        
## pop : will remove one value randomly
    Ex:- a={10,5,6,20,98,45}
         print(f'Before:{a}')
         a.pop()
         print(f'After:{a}')

    o/p:- Before : {98,20,5,6,10,45}
          After : {20,5,6,10,45}

## discard : Will take one value from the user and if the input is available it will remove or else it will be silent.

    Ex:- a={10,5,6,20,98,45}
         a.discard(98)
         print(a)

    o/p:- {20,5,6,10,45}
    
    Ex:- a={10,5,6,20,98,45}
         print(a.discard(980))

    o/p:- {98,20,5,6,10,45}

## remove : It takes one input from the user and if the input is available it will remove or else it will through error.

    Ex:- a={10,5,6,20,98,45}
         print(a.remove(98))

    o/p:- {20,5,6,10,45}

## copy
### Deep copy : Address same 
    Ex:- a={10,5,6,20,98,45}
         b=a
         print(a)
         print(b)
         print(id(a))
         print(id(b))

    o/p:- {98,20,5,6,10,45}
          {98,20,5,6,10,45}
          19860477454
          19860477454
### shallow copy : Address different
    Ex:- a={10,5,6,20,98,45}
         b=a
         print(a)
         print(b)
         print(id(a))
         print(id(b))

    o/p:- {98,20,5,6,10,45}
          {98,20,5,6,10,45}
          19860477454
          32647648237

# union : Combine all values in given sets

    Ex:- a={1,2,3,4,5,6}
         b={5,6,7,8,9,10}
         print(a.union(b))/print(b.union(a))

    o/p:- {1,2,3,4,5,6,7,8,9,10}

# intersection : Common values in both sets

    Ex:- a={1,2,3,4,5,6}
         b={5,6,7,8,9,10}
         print(a.intersection(b))

    o/p:- {5,6}

# clear 
    Ex:- a={1,10,15,19,25}
         a.clear()
         print(a)
    
    o/p:- set() ->empty set

# Dictionary
* Dictionary is used to prepare the structured data.
* Dictionary will be represented with {} even sets are also represented with {} but dictionary is represented with key value pair where key will be column name and value will be column values.

      Ex:- a={'Age':[30,40,50],'loc':['chennai','banglore','hyd'],'salary':[1200,1800,2200]}
           print(a)

      o/p:- {'Age':[30,40,50],'loc':['chennai','banglore','hyd'],'salary':[1200,1800,2200]}

* dictionary is mutable but it won't allow mutable types as a key.

## Built_in_functions

* get
* update
* pop
* popitem
* key
* value
* items
* clear
* copy

### get : used to call the required data from the existing dictionary
 
    Ex:- b={'apple':500,'carrot':100,'banana':500}
         print(b.get('carrot'))

    o/p:- 100

### update : used to add key value to the existing dictionary

    Ex:- b={'apple':500,'carrot':100,'banana':1000}
         b.update({'grapes':200})
         print(b)

    o/p:- {'apple':500,'carrot':100,'banana':1000,'grapes':200}

### pop : will take key from the user and will remove the key value.

    Ex:-  b={'apple':500,'carrot':100,'banana':1000}
          b.pop('carrot')
          print(b)
    
    o/p:- {'apple':500,'banana':1000}

### popitem : will remove last key value

    Ex:- b={'apple':500,'carrot':100,'banana':1000}
         b.popitem()
         print(b)
    
    o/p:- {'apple':500,'carrot':100}

### key 

    Ex:- b={'apple':500,'carrot':100,'banana':1000}
         print(b.keys())
    
    o/p:- dict_keys(['apple','carrot','banana'])

### values

    Ex:- b={'apple':500,'carrot':100,'banana':1000}
         print(b.values())
        
    o/p:- dict_values([500,100,1000])

### items
    EX:- b={'apple':500,'carrot':100,'banana':1000}
         print(b.items())

    o/p:- dict_items([('apple',500),('carrot',100),('banana',1000)])

### clear
    Ex:- b={'apple':500,'carrot':100,'banana':1000}
         b.clear()
         print(b)
    o/p:- {}

* Deep copy and shallow copy are same as in sets.

# Conditional and Control statements

## control Statements : 
   Control statements in Python are used to manage the flow of execution of a program based on certain conditions. 
   * For loop
   * While loop
   * break
   * continue

### For loop : A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

#### syntax : for [var] in range(s-p,e-p):
    Ex:- for i in range(11,21):
         print(i)

    o/p:- 11
          12 
          13
          14
          15
          16
          17
          18
          19
          20

    Ex:- for i in range(1,11):
         print(i,end='')
    o/p:- 1 2 3 4 5 6 7 8 9 10

### while loop : With the while loop we can execute a set of statements as long as a condition is true.

    Ex:- a=1
         while a <= 10:
             print(a)
             a=a+1

    o/p:- 1
          2
          3
          4
          5
          6
          7
          8
          9
          10

### break : With the break statement we can stop the loop even if the while condition is true

    Ex:- for i in range(11,21):
            print(i)
            if i == 17:
               break
    
    o/p:- 11
          12
          13
          14
          15
          16
          17

### continue : With the continue statement we can stop the current iteration, and continue with the next
    Ex:- for i in range(11,17):
           print(i)
           if i == 13:
             continue
    
    o/p:- 11
          12
          14
          15
          16

## Conditional Statements:
 
* Conditional Statements are statements in Python that provide a choice for the control flow based on a condition. It means that the control flow of the Python program will be decided based on the outcome of the condition. 

    * if
    * elif
    * else

### if : If the simple code of block is to be performed if the condition holds then the if statement is used.

    Ex:- money=20000
         iphone=50000
         if money > iphone:
            print('I will buy iphone')

    o/p:- 

### else : The else keyword catches anything which isn't caught by the preceding conditions.

    Ex:- money=20000
         iphone=50000
         if money > iphone:
            print('I will buy iphone')
         else:
            print('I dont have enough money')

    o/p:- I dont have enough money

### elif : The elif keyword is Python's way of saying "if the previous conditions were not true, then try this condition".

    Ex:- money=20000
         iphone=50000
         samsung=25000
         vivo=15000
         if money > iphone:
            print('I will buy iphone')
         elif money > samsung:
            print('I will buy samsung')
         elif money > vivo:
            print('I will buy vivo')
         else:
            print('I dont have enough money')

    o/p:- I will buy vivo


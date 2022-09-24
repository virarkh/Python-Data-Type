# Data Type in Python

## Python Introduction
Python is a widely-used general-purpose, high-level programming language. It was initially designed by Guido van Rossum in 1991 and developed by Python Software Foundation. It was mainly developed for emphasis on code readability, and its syntax allows programmers to express concepts in fewer lines of code.

### The advantages using python
- Free and Open Source
- Easy to code
- Easy to Read
- Object-Oriented Language
- GUI Programming Support
- Python is an Integrated language, and many other features

**C++ "Hello World"**
```
#include <iostream.h>
  main(){
    count << "Hello World";
  }
  return 0;
```

**Java "Hello World"**
```
class helloWorldApp
{
  public static void main(String[] arg)
  {
    System.out.println("Hello World");
  }
}
```

**Python "Hello World"**
```
print("Hello World")
```

## Python Built-In Data Type 
Python has 3 built-in data type which are **Number**, **String** and **Boolean**. To find out the type of data used in a variable, can use the *type()* function.

### Number
Number data type is a data type that contains numbers. Number has 3 types in Python, which are **integer**, **float** adn **complex**.
- **Integer**
  - Store a whole number, both positive or negative whole number
  - Indicator in Python, integer symbolized by **int**
  
- **Float**
  - Store decimal number, both positive or negative decimal number.
  - Store number up to 17 digits after comma (.)
  - Indicator in Python, float symbolized by **float**
  
- **Complex**
  - Store imaginary number
  - In python imaginary store with **j** character
  - Indicator in Python, complex symbolized by **complex**
  
### String
- String is a data type that stored a set of character
- String in python surrounded by either single quotation marks (' '), or double quotation marks (" ")
- The single and double quotation marks put at the beginning and the end set of character

### Boolean
- The boolean data type can only be filled with one of 2 values, namely **TRUE** or **FALSE**
- The boolean data type is mostly used to decide what to do when a condition occurs

## Python Data Type Advance
Python has 5 data type advance to store collection of data, there are **List**, **Tuple**, **Set**, **Dictionary** and **Slicing**.

### List
- List is a collection which is *ordered*, *changeable* and *allow duplicate* items
- List create with square brackets [ ]
- If items in the list is string, the items must to assign with *quotation marks*, either with single (' ') or double (" ") quotation marks. And if the items is number or boolean, no need to assign with quotation marks
- Each item *separated by a comma* (,)
```
this_list = ["Halo", "This is Github", 8888, False]
```

### Tuple
- Tuple is a collection which is *ordered* and *unchangeable* and *allows duplicate* items
- Tuple create with round brackets ( )
- If items in the tuple is string, the items must to assign with *quotation marks*, either with single (' ') or double (" ") quotation marks. And if the items is number or boolean, no need to assign with quotation marks
- Each item *separated by a comma* (,)
```
this_tuple = ("Halo", "This is Github", 8888, False)
```

### Set
- Set is a collection which is *unordered*, *unchangeable*, *unindexed* and *no duplicate* items
- Set create with curly brackets { }
- If items in the set is string, the items must to assign with *quotation marks*, either with single (' ') or double (" ") quotation marks. And if the items is number or boolean, no need to assign with quotation marks
- Each item *separated by a comma* (,)
```
this_set = {"Halo", "This is Github", 8888, False}
```

### Dictionary
- Dictionary is a collection which is *ordered*, *changeable* and *duplicate* items
- If key or value in the dictionary is string, they must to assign with *quotation marks*, either with single (' ') or double (" ") quotation marks. And if the key or value is number or boolean, no need to assign with quotation marks.
- Key and value *separated by colon* (,).
- Each item *separated by a comma* (,).
```
this_dict = {
  "brand": "Ford",
  "electric": False,
  "year": 1964,
  "colors": "red"
}
```

### Slicing String
- Slicing is used to retrieve items in a string. 
- Mutable (can be changed) if the entire data is changed, but immutable (cannot be changed) if only one of the string items
```
a = "Data Engineer"
print(a[5:12])
```

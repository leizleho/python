## Numbers

Number type:
	Integer, Floating-point number

#### Basic Arithmetic
```
# Addition
3+2
```
Output: 5

```
# Subtraction
3-2
```
Output: 1

```
# Multiplication
3*2
```
Output: 6

```
# Division
3/2
```
Output: 1

```
# Specifying one of the numbers as a float
3.0/2
# or 3/2.0
```
Output: 1.5

```
# Division in Python 3
3/2
```
Output: 1.5

```
# Division using float() function to cast integer as float
float(3)/2
```
Output: 1.5

```
# Powers
2**3
```
Output: 8

## Strings
String in Python is sequence of Unicode characters. We can use single quotes or double quotes to represent strings. Multi-line strings can be denoted using triple quotes, ''' or """. Since python is a sequence, we can use brackets [] after an object to call its index. Note that indexing starts at 0 for Python.

```
# Assign s as a string
s = 'Hello World'  
``` 

```
# Show first element
s[0] 
```
Output: 'H'

## Lists
List is an ordered sequence of items. All the items in a list do not need to be of the same type. To declare a list, separate items by commas and enclose within brackets [ ]. Lists are mutable, meaning, value of elements of a list can be altered.

```
n = [1, 2.3, 'hello']
```

## Tuples
Tuple is an ordered sequence of items same as list.The only difference is that tuples are immutable. Tuples once created cannot be modified. Tuples are used to write-protect data and are usually faster than list as it cannot change dynamically. It is defined within parentheses () where items are separated by commas. Slicing operators [] to extract items.

```
t = ('hello',1,2.3)
```

## Dictionaries
Dictionary is an unordered collection of key-value pairs.
It is generally used when there is a huge amount of data. Dictionaries are optimized for retrieving data. We must know the key to retrieve the value. Dictionaries are defined within braces {} with each item being a pair in the form key:value. Key and value can be of any type.

```
d = {1:'value','key':2}
```

## Sets
Set is an unordered collection of unique items. Set is defined by values separated by comma inside braces { }. Items in a set are not ordered. Since, set are unordered collection, indexing has no meaning. Slicing operator [] does not work in set.

```
a = {1,2,2,3,3,3}
a
```
Output: {1, 2, 3}







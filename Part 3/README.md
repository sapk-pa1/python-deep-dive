# Part 3 Dictionaries, Sets and JSON 

## why bother with dictionaries? 
Dictionaries are Everywhere in Python. The Following are Dictionaries in Python 
- Modulues 
- Classes 
- Objects(class instances)
- scopes 
- sets

> Dictionary is most important data structure in the Python 

# Associative Arrays 
An associative array is an abstract data structure that aossicates keys (keys are unique) to values. Also called as `maps` or  `dictionaries`
> We can think of it as a collection of (`key`, `value`) . 

They support 
- Adding/removing elements 
- Modifying an associated value 
- lookup a value via its key 

# Hash Maps (aka Hash table)
One common concrete implementation of an assoicative array(aka dictionary) is hash map. 

Suppose we have want to store the following maps. 

'john' -> John \
'eric' -> Eric \
'michael' -> Michael \
'graham' -> Graham 
> For this we will define a function that will return an integer value for all these string ('john', 'eric', ..) which will be unique for all these string

## Storing a key/value pair 
- Calculate h(key) which returns the idx(index)
- store value in the slot idx 

## Looking up a value by key 
- Calculate h(key) which returns the idx 
- return the value in the slot idx 

## Hash Functions 
A hash function is a function that maps from a set(domain) of arbitrary size (possibly infinite) to another (smaller) set of fixed size (range). \
When Creating a Hash Function if the function generates the same output for the different input we have a situation called as `Collision`. So there are various ways to deal with collision which are : 
- Probing (linear)

# Python Hash Function 
It returns the Int for the Given Immutatable Object. Hash is same for the given runtime and on the next runtime is might not return the same int. 

Contents
- [Dictionaries](Dictionaries/)
    - [Creating Dictionaries](Dictionaries/create_dict.ipynb)

    - [Coding Exercise](Dictionarie/Coding/ Exercises.ipynb)
 
# Refactoring #

- Scenario 1 : using the function to short the URL thats using tow function 'getLong ','makeShort'
- Scenario 2 :URLs are generated randomly. by using 'friendly-words' package thats make a randomly URL and save for the user

## Functional Programming ##
Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .


## What makes a function pure? ##
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

## Pure functions benefits ##
- The code’s definitely easier to test
- We don’t need to mock anything. So we can unit test pure functions with different contexts:
- Given a parameter A → expect the function to return value B
- Given a parameter C → expect the function to return value D

## Functions as first-class entities## 
Functions as first-class entities can:

- refer to it from constants and variables
- pass it as a parameter to other functions
- return it as result from other functions

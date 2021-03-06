# DATA STRUCTURE CHALLENGES
##TOC
- [Reverse an Array](#reverse_an_array)
- [Shift an Array](#shift_an_array_from_middle)
- [Binary Search in Array](#binary_search_in_array)
- [Stacks with Queues](#stacks_with_queues)
- [FIFO Animal Shelter](#fifo_animal_shelter)
- [Multibracket Validation](#multibracket_validation)
- [FizzBuzz Tree](#fizzbuzz_tree)
- [Binary Tree Find Max](#find_maximum_value_on_binary_tree )
- [Find First Repeated Word](#find_first_repeated_word)
- [Intenerary Validation](#itenerary_validation)
- [Left Join](#left_join)
- [Tree Intersection](#tree_intersections)

## Reverse_an_Array
Take an array and reverse the order of the elements without using built-in methods

#### Challenge
Given an input array, return an array with the elements in reverse order

#### Whiteboard
![whiteboard reverse array](../assets/01_array_reverse.jpg)

## Shift_an_Array_from_Middle
Insert a value in the middle of an array and shift the indeces.

#### Challenge
Given an input array and an item to insert, return an array where the item has been inserted into the middle of the array (rounding up for odd numbered arrays). The insertShiftArray method is arity of 2.

#### Whiteboard
![whiteboard shift array ](../assets/02_array_shift.jpg)

## Binary_Search_in_Array
Search a sorted array for target value and return its index

#### Challenge
Given a sorted input array and target value to search, return the index of the search value if it is found and if it is not in the array return -1. The binary version of this search utilizes finding the middle of the array and systematically discounting half the values with every operation.  

####Whiteboard
![whiteboard03a](../assets/03_array_binary_search_a.jpg)
![whiteboard03b](../assets/03_array_binary_search_b.jpg)

## Stacks_with_Queues
Create a queue by using stacks

#### Challenge
Make a data structure that is First in first out order (FIFO) with only access to last in first out order (LIFO) data structure. 

#### Solution
![whiteboard06](./assets/06_stacks_with_queues.jpg)

## FIFO_Animal_Shelter
An animal shelter takes in dogs and cats, and gives them to new owners.  If someone asks for a dog or cat they get the cat or dog that has been waiting the longest(First in First out - FIFO).

#### Challenge
The function animalShelter takes an optional input of a preference and returns a cat or dog.  If someone asks for a dog or cat from the animal shelter they get the cat or dog that has been waiting the longest.  If they ask for an animal without a preference they get whatever has been waiting the longest.

#### Whiteboard
![whiteboard07](../assets/07_fifo_animal_shelter.jpg)

## Multi_bracket_validation
Create a function to validate a strings balance for brackets.

#### Challenge
To take a string of whatever size and return true or false if brackets were balanced, meaning each bracket has open and close and can nest within each other while not overlapping.  It is not effected by any non-bracket characters.

Examples:
{} -> true
() -> true
[] -> true
[{}] -> true
[{]} -> false
[true] -> true

#### Whiteboard
![whiteboard08](../assets/multi_bracket_validation.jpg)

## FizzBuzz_Tree
Create a function to fizzbuzzify a tree

#### Challenge
Create a function which takes a binary search tree as an input.  It then replaces all nodes in the tree that are multiples of 3 to the string `fizz`, all multiples of 5 as `buzz`, and multiples of both as `fizzbuzz`.

#### Whiteboard
![whiteboard10 fizzbuzz tree](../assets/10_fizzbuzz_tree.jpg)

## Find_Maximum_Value_on_Binary_Tree
Create a function to find the max value of a binary tree

#### Challenge
Create a function which takes a binary tree as an input.  It then traverses the tree reassigning a max value variable when it encounters a higher value.  After traversal it returns a maximum value for the tree.

#### Whiteboard
![whiteboard find the max in binary tree](../assets/11_bt_find_max_val.jpg)

## Find_First_Repeated_Word
Find the first repeated word in a long string of words.

#### Challenge
Create a function which takes a long string of words and returns a string of the first word to repeat itself.  

#### Whiteboard
![whiteboard first repeated word](../assets/first_repeated_word.jpg)

## Itenerary_Validation
Given a list of flights  and chart of flights determine if they are valid and their cost

#### Challenge
Create a function which takes an array of places and a weighted graph.  Determine in order of the array whether the paths exist within the graph and return the cost of the total path or 0 if there is no complete path.

#### Whiteboard
![whiteboard itenerary validation](../assets/wg_itenerary_validation.jpg)

## Left_Join
Takes two adjascency lists and does a left join.

#### Challenge
Create a function that takes in two adjascency lists and adds values from one list to the other when keys in both lists collide.  This addition only goes one direction to the first list entered into the function.

## Tree_Intersections
Find the values that intersect between two binary trees

#### Challenge
Create a function which takes two binary trees and returns an array that includes values that are repeated between both trees.

#### Whiteboard
![whiteboard tree intersections](../assets/tree_intersection.jpg)
# Cracking the coding interview

Here you can find my solutions for the quizzes that you can find in the Cracking the coding interview Fourth Edition

![alt text](cover-book.png "Cracking the coding interview")

## Chapter 1 | Arrays and Strings

### 1.1

Implement an algorithm to determine if a string has all unique characters What if you can not use additional data structures?

### 1.2

Write code to reverse a C-Style String (C-String means that “abcd” is represented as five characters, including the null character)

### 1.3

Design an algorithm and write code to remove the duplicate characters in a string without using any additional buffer

> **NOTE**: One or two additional variables are fine An extra copy of the array is not
> 
> **FOLLOW UP**
> Write the test cases for this method

### 1.4

Write a method to decide if two strings are anagrams or not

### 1.5

Write a method to replace all spaces in a string with ‘%20’ 

### 1.6

Given an image represented by an NxN matrix, where each pixel in the image is 4 bytes, write a method to rotate the image by 90 degrees Can you do this in place?

### 1.7

Write an algorithm such that if an element in an MxN matrix is 0, its entire row and column is set to 0

### 1.8

Assume you have a method isSubstring which checks if one word is a substring of another Given two strings, s1 and s2, write code to check if s2 is a rotation of s1 using only one call to isSubstring (i e , “waterbottle” is a rotation of “erbottlewat”)

## Chapter 2 | Linked Lists

### 2.1 Write code to remove duplicates from an unsorted linked list

> **FOLLOW UP**: How would you solve this problem if a temporary buffer is not allowed?

### 2.2 Implement an algorithm to find the nth to last element of a singly linked list 

### 2.3 Implement an algorithm to delete a node in the middle of a single linked list, given only access to that node

> **EXAMPLE**
>
> *Input*: the node ‘c’ from the linked list a->b->c->d->e
>
> *Result*: nothing is returned, but the new linked list looks like a->b->d->e

### 2.4 You have two numbers represented by a linked list, where each node contains a sin- gle digit The digits are stored in reverse order, such that the 1’s digit is at the head of the list Write a function that adds the two numbers and returns the sum as a linked list

> **EXAMPLE**
>
> *Input*: (3 -> 1 -> 5) + (5 -> 9 -> 2)
>
> *Output*: 8 -> 0 -> 8

### 2.5 Given a circular linked list, implement an algorithm which returns node at the begin- ning of the loop

> **DEFINITION**: Circular linked list: A (corrupt) linked list in which a node’s next pointer points to an earlier > node, so as to make a loop in the linked list
> 
> **EXAMPLE**
>
> *Input*: A -> B -> C -> D -> E -> C [the same C as earlier]
>
> *Output*: C
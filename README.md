# Number Theory: Addition

In this lab you've learned the basics of number theory as it relates to addition.

## Rubric
 
| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Mika Calderon and Tim Palacios

## Lab Summary
In this lab, we learned how logic gates can be used to perform addition with binary
numbers. In an adder, an XOR gate produces the sum bit, while an AND gate produces 
the carry bit. This carry bit can be used in a full adder to add three bits together. 
By chaining multiple adders together with carry bits, we can add together larger 
binary numbers.

## Lab Questions

### 1 - How might you add more than two bits together?
We are able to add more than two bits together by using a full adder. The full adder 
takes two bits and a carry-in bit from the previous addition that was done. It outputs 
a sum bit and a carry-out bit, in case more bits need to be added.

### 2 - What is the importance of the XOR gate in an adder?
The XOR is important in an adder because it calculates the sum bit when adding binary 
numbers. The output is 0 when the two input bits are the same and 1 when they are different. 

### 3 - What is the largest number a two bit adder can handle? What happens when you go over?
The largest number a two bit adder can handle as an input is 3 (`11`). When the adder goes over 
3, it sets the carry-out bit as 1, and it is treated as a third bit. The carry-out can also be 
passed into another adder if used in a bigger circuit.
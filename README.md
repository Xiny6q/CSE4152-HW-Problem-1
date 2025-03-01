Download link :https://programming.engineering/product/cse4152-hw-problem-1/

# CSE4152-HW-Problem-1
CSE4152 HW Problem #1
Finding Celebrities

A celebrity is defined as a person who is known by everybody but does not know anyone. How can you find any celebrities among N people?

You can freely ask anyone as follows: “Hey, you know Mr. (or Ms.) X?” Suppose that there are N people. Design a method that

determines whether there is some celebrities among the people

if there is any celebrities, find them efficiently (minimizing the number of questions you make).

Minimum calculation

Imagine an electric calculator which has only two arithmetic operations, i.e., assignment operation(:=) and multiplication operation (x). We want to let this machine compute b = an for given numbers a and n. Design a method that produce a code for this machine, minimizing the number of multiplications.

 

Example when n = 16

 

x1 := a;

x2 := x1 ⅹ x1; // a2

x3 := x2 ⅹ x2; // a4

x4 := x3 ⅹ x3; // a8

x5 := x4 ⅹ x4; // a16

b:=x5

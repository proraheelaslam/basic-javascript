# Basic JavaScript

This repository include the basic concept of JavaScript
## Table of Contents
* [About javascript](https://github.com/proraheelaslam/basic-javascript/#about-javascript)
* [Logical Operator](https://github.com/proraheelaslam/basic-javascript/#logical-operator)
* [Ternary Operator](https://github.com/proraheelaslam/basic-javascript/#ternary-operator)
* [Comparison Operator](https://github.com/proraheelaslam/basic-javascript/#comparison-operator)
* [Assignment Operator](https://github.com/proraheelaslam/basic-javascript/#assignment-operator)

### About JavaScript
JavaScript is most popular  and widely used programming language in world,It’s growing faster than any other programming languages and big companies like Netflix, Walmart and paypal build entire applications in JavaScript.

Average salary of JavaScript in united states  $72000 a year, so it’s good opportunity to get great job to learning JavaScript can work as front end developer, back-end developer or full stack developer or who knows both front-end and back-end developer.

### Logical Operator

Logical operators(  (||)  ( &&)  (!)  ) are used with Boolean, when they are used with boolean to return boolean, if they used with non-boolean it's may return non-boolean.

if value can be converted into true is so called truly and if value can be converted into false so called falsy. 

Examples of expression that can converted into false are:
* null
* NAN
* 0
* empty string
* undefined

These are falsy values in JavaScript, anything that's not falsy is truly.

#### Short Circuit Evaluation 

Logical expression are evaluated from left to right, they are tested for "short circuit" evaluation for following rules:

* false && (anything) is short circuit evaluated to false.
* true || (anything) is short evaluated to true
#### Converting AND into OR
     
```
(bCondtion1  && bCondition2) 
```
#### Converting OR to AND

```
(bCondition1 || bCondition2)
```
is always equal to
```
!(!bCondition && !bCondition2)
```
### Ternary Operator

Ternary operator takes three operands and it's used as shortcut for if statement.
#####   syntax
```
condition ? expT : expF
```
### Comparison Operator

Comparison operator are binary operator that takes two operands and compare the values.
#### Relational Operator
     
| Operator        | Example          
| ------------- |:-------------: 
|        >      | x>y
|         <     | x<y       
|        <=     | x>=y
|        >=     | x<=y
#### Equality Operator
     
Two types of equality operator 

* Strict Equality Operator
=== is strict equality operator, it's compare both values and types.
* Lose Equality Operator
== is lose equality operator it's match only values.

### Assignment Operator




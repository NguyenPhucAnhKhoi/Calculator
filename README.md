# About Calculator
> It allow you computes an expression contained in a string.
# Expressions List
> • Summation: "number1 + number 2" ; Ex: "1 + 2" ➙ 3
> 
> • Subtraction: "number1 + number2" ; Ex: "5 - 3" ➙ 2
> 
> • Multiplication: "number1 * number2" ; Ex: "3 * 2" ➙ 6
> 
> • Division: "number 1 / number 2" ; Ex: "10 / 2" ➙ 5
> 
> • Division Remainder: "number1 % number2" ; Ex: "7 % 2" ➙ 1
> 
> • Exponential: "number^exponent" ; Ex: "2^3" ➙ 8
> 
> • Percent: "percent # number" ; Ex: 10 # 20 (10% of 20) ➙ 2
>
> • Square Root: "@{number}" ; Ex: "@{16}" ➙ 4
> 
# Advanced Expressions
> ➤ Priority Expression: exponential and square root go first; then miltiplication, division and division remainder; final summation and subtraction; Ex: "2 * 3 + 1" ➙ 7
> 
> ➤ Expressions Contains Bracket: "(number1 + number2) * number2" the expressions in bracket will go first then comes the general expression ; Ex: "(1 + 2) * 4" ➙ 12
>
# Hook into Calculator
[![](https://jitpack.io/v/NguyenPhucAnhKhoi/Calculator.svg)](https://jitpack.io/#NguyenPhucAnhKhoi/Calculator)
>
Maven:
```
<repository>
  <id>jitpack.io</id>
  <url>https://jitpack.io</url>
</repository>
```
>
```
<dependency>
  <groupId>com.github.NguyenPhucAnhKhoi</groupId>
  <artifactId>Calculator</artifactId>
  <version>Tag</version>
</dependency>
```

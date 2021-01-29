1. Line 11 will output `prices.length` to the console because `i` is a function-level variable (visible after the for loop since the for loop is a code block in the function).
2. Line 12 will output `price[prices.length-1] * (1 - discount)` to the console because `discountedPrice` is a function-level variable (visible inside the function since it was declared in a code block in the function).
3. Line 13 will output `Math.round(discountedPrice * 100) / 100` to the console because `finalPrice` is a function-level variable (visible inside the function since it was declared in the function).
4. `discountPrices([100,200,300],.5)` will return 50,100,150. The for loop calculates the final price of each price in the list prices and pushes the final price after discount and rounding to the list discount.
5. Line 11 will produce an error since the variable `i` is declared within the for loop and is considered a part of that code block, so it is not visible outside of the code block.
6. Line 12 will produce an error since the variable `discountedPrice` is declared within the for loop and is considered a part of that code block, so it is not visible outside of the code block.
7. Line 13 will output the rounded and discounted price of the last price in the list prices to the console because the variable `finalPrice` was declared within the function and not inside a code clock within the function.
8. `discountPrices([100,200,300],.5)` will return 50,100,150. The for loop calculates the final price of each price in the list prices and pushes the final price after discount and rounding to the list discount.
9. Line 11 will produce an error since the for loop tries to increment `i`, which is a constant variable.
10. Line 12 will produce an error since the for loop tries to update the value of `discountedPrice`, a constant variable, in each iteration.
11. Line 13 will produce an error since the for loop tries to update the value of `finalPrice`, a constant variable, in each iteration. 
12. `discountPrices([100,200,300],.5)` does not return anything since there are assignment to constant variable errors.
13. Data Types\
    A) student.name\
    B) student['Grad Year']\
    C) student.greeting\
    D) student['Favorite Teacher'].name\
    E) student.courseLoad[0]
14. Arithmetic\
    A) '32'\
    B) 1\
    C) 3\
    D) 3null\
    E) 4\
    F) 0\
    G) 3undefined\
    H) NaN
15. Comparison\
    A) true\
    B) false\
    C) true\
    D) false\
    E) false\
    F) true
16. == checks for equality with type conversion while === checks for equality without type conversion.
17. 'How are you?' gets printed because the first conditional statement is false while the second conditional statement of else if is true, i.e. a number by itself as the conditional statement is true.

19. The result will be 6,8,10. For each iteration in the for loop, we run doSomething which calculates `(array[i] + 2) * 2` and push that result to `newArr`. 
21. 1\
    4\
    3\
    2

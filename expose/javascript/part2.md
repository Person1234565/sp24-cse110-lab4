1. Line 12 will print out 3. This is because "i" is a function-scoped variable, so it is still accessible after the for loop ends. 
Since the for loop only ends when i >= discounts.length, and since the length of discount was 3, the code prints out 3. 

2. Line 13 will print out 150. This is because "discountedPrice" is a function-scoped variable, so it is still accessible outside of 
the for loop. Thus, it retains the last value that was assigned to it during the for loop, which in this case is 300*(1-0.5) = 150. 

3. Line 14 will print out 150. This is because "finalPrice" is a function-scoped variable, so it is still accessible outside of 
the for loop. Thus, it retains the last value that was assigned to it during the for loop, which in this case is Math.round(150*100)/100 = 150. 

4. The function returns [50, 100, 150]. This is because the code iterates through each price, multiplies the discount to the price, appends this price to 
the discounted array, and returns the discounted array. With the parameters given, this ends up multiplying 0.5 to each item, resulting in [50, 100, 150].

5. Line 12 will cause an error. This is because "i" is a block-scoped variable, so it cannot be accessed outside of the for loop it was declared from. 

6. Line 13 will cause an error. This is because "discountedPrice" is a block-scoped variable, so it cannot be acessed outside of the for loop it was declared from. 

7. Line 14 will print out 150. This is because "finalPrice" is a block-scoped variable, and Line 14 is within this block, so the variable can be accessed and retains its latest value, which would be 150. 

8. The function returns [50, 100, 150]. This is because the code iterates through each price, multiplies the discount to the price, appends this price to 
the discounted array, and returns the discounted array. With the parameters given, this ends up multiplying 0.5 to each item, resulting in [50, 100, 150].

9. Line 11 will cause an error. This is because "i" is a block-scoped variable, so it cannot b e accessed outside of the for loop it was instantiated in. 

10. Line 12 will print 3. This is because length is block-scoped and Line 12 lies in the same block as it, so it can be accessed. 
Since the length of the array prices is 3, and since length is a const that cannot be reassigned, its value remains 3. 

11. The function returns [50, 100, 150]. This is because the code iterates through each price, multiplies the discount to the price, appends this price to 
the discounted array, and returns the discounted array. With the parameters given, this ends up multiplying 0.5 to each item, resulting in [50, 100, 150].
 
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]

13. A. 32 since the number 2 is mapped to its string representation.
    B. 1 since the string "3" is converted to its numeric counterpart 3.
    C. 3 since null is converted to the number 0.
    D. 3null since null is converted to the string "null."
    E. 4 since true is converted to the number 1. 
    F. 0 since both false and null are converted to the number 0.
    G. 3undefined since undefiend is converted to the string "undefined."
    H. NaN since undefined is converted to NaN and operations on NaN are also NaN.

14. A. true since "3" is converted to its numeric counterpart 3, and 3 > 2. 
    B. false since the string "12" is lexicographically less than the string "2" as the starting character "1" is lexicographically less than the starting character "2."
    C. true since "2" is first converted to its numeric counterpart 2 and checked to be equal with 2, which they are equal. 
    D. false since strict equality does not perform type conversion, so it compares the string "2" with the number 2 and since they are different types they are not considered equal. 
    E. false since true is converted to its numeric counterpart 1, and 1 != 2. 
    F. true since Boolean(2) is true as 2 is a non-zero value.

15. While == performs type conversion before checking for equality, === does not perform any type conversion before checking for equality. From this, === between two operands of different types will always be false. 

16. In part2-question16.js

17. The function will return the array [2, 4, 6]. First, we pass in [1, 2, 3] and doSomething to the function modifyArray. In this function, modifyArray initializes a new array, and iterating through each element of array, it calls doSomething on the element and pushes the result to newArr. 
First, it calls doSomething(1) which returns 2 and pushes it to newArr. Then, it calls doSomething(2) which returns 4 and pushes it to newArr. Finally, it calls doSomething(3) which returns 6 and pushes it to newArr. newArr is then returned, with its contents being [2, 4, 6]. 

18. In part2-question18.js

19. 1 4 3 2, separated by newlines

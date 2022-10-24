1. 3 is printed because i = 3 when the for loop is exited. This value is remembered because i was declared with the var keyword, thus it has scope within the function.
2. 150 is printed because discountedPrice = 150 when the for loop is exited. This value is remembered because discountedPrice was declared with the var keyword, thus it has scope within the function.
3. 150 is printed because finalPrice = 150 when the for loop is exited. This value is remembered because finalPrice was declared with the var keyword, thus it has scope within the function.
4. This function returns the array discounted which contains all the prices with the discounts applied to them. To be specific: [50,100,150]. This variable has scope within the function.
5. The code returns a ReferenceError. This happened because i was declared inside a for loop block with the let keyword. Thus, the scope of result is within that block and cannot be accessed outside of the loop.
6. The code causes a ReferenceError because discountedPrice was declared inside a for loop with the let keyword. Thus, the scope of discountedPrice is within that block and cannot be accessed outside of the loop.
7. 150 is printed because finalPrice = 150 when the for loop is exited. This value is remembered because finalPrice has scope within the function.
8. This function returns the array discounted which contains all the prices with the discounts applied to them. To be specific: [50,100,150]. This variable has scope within the function.
9. The code causes a ReferenceError because i is not defined. This happens because i was declared with the let keyword, thus it has block scope which is only within the for loop.
10. 3 is printed because the variable length has scope within the function with the const declaration. This value is unchanged.
11. This function returns the array discounted which contains all the prices with the discounts applied to them. To be specific: [50,100,150]. This variable has scope within the function.
12. **A.** student.name; **B.** student['Grad Year']; **C.** student.greeting(); **D.** student['Favorite Teacher'].name; **E.** student.courseLoad[0];
13. **A.** "32" - The + symbol converted the result to a string **B.** 1 - The - symbol resulted in a number conversion **C.** 3 - The result is an integer since 3 is not a string **D.** "3null" - 3 is a string and the + symbol converted the result to a string **E.** 4 - true is mapped to the number 1 **F.** 0 - false is mapped to the number 0 **G.** "3undefined" - 3 is a string and the + symbol converted the result to a string **H.** NaN - In numeric conversion undefined becomes NaN
14. **A.** true - a numeric conversion is performed and 2 is greater than 1. **B.** false - string comparison is performed. in lexiographical order 12 is greater than 2. **C.** true - '2' becomes 2 and these numbers are the same **D.** false - the types are not the same **E.** false - true maps to 1 **F.** true - 2 is boolean converted to true and true === true
15. === checks the strict equality of types without any conversion being performed, whereas == can check equality between two different types and perform conversion.
16. [Here is the code](part2-question16.js)
17. The result is newArr: [2, 4, 6]. The doSomething function is passed in as a parameter to the modifyArray function, where the input array's elements are iterated and modified by calling the modifyArray function on each element. These modified elements (multiplied by 2) are pushed into the new array.
18. [Here is the code](part2-question18.js)
19. 1 3 2

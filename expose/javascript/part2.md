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

1. The output is 3 because console.log(i) accesses i, which is declared using var, so it remains accessible outside of the for loop.
2. The output is 150 because the output is discountedPrice, not i itself. 
3. The output is 150 because the value of 150 is pushed into an array, which is then outputted.
4. This function will return the discounted array, [50, 100, 150] though nothing will be printed since there is no console.log
5. This results in an error. Let does not allow i to be accessed outside the for loop, unlike var. THerefore nothing is outputted.
6. This results in an error. Since let is block-scoped it cannot be accessed outside of the for loop.
7. 150 is outputted because finalprice is declared outside of the for-loop using let, so it is still accessible.
8. This function returns the discounted array, [50, 100, 150]
9. This line causes an error because i is declared using let, and cannot be accessed outside of the for loop.
10. This line outputs 3, which is the length of our input array. It is a constant and cannot be changed. 
11. (3) [50, 100, 150] the function runs normally because all calculations were successful and correctly pushed into the result array.
12. A - student.name B - student["Grad Year"] C - student.greeting() D - student["Favorite Teacher"].name E - student.courseLoad[0]
13.
 A - '32' When using + with a string, js will convert the operands to strings and concatenate.
 B - 1, - operator forces all operands to be treated as numbers.
 C - 3 - null is converted to 0 in mathematical operations with numbers. 
 D - '3null' because '3' concatenates with 'null'
 E - 4 because true is treated as a 1
 F - 0 because both false and null are considered 0, resulting in 0. 
 G - '3undefined' because '3' + causes '3' to be concatenated with undefined, which is treated as a string. 
 H - Nan. This is because we try to subtract using '3' and undefined, which cannot be treated as a number or integer. Similar to division by 0
14. 
A - true, '2' is converted to a number and 2 > 1 is true.
B - false, both operands are strings, which are then compared in lexicographical order.
C - true, since == performs type coercion we get 2 == 2 which is true.
D - false, === does not perform type coercion.
E - false, since we use == true is treated as 1.
F - Both sides are equal to true, so the output is true.
15. == performs type coercion and === does not, so we cannot compare variables of different data types while using ===, but we can if we use ==
17. Final Result: [2, 4, 6] - Each element in the array [1, 2, 3] is passed into the doSomething function, which then doubles it. The modifyArray function collects these results into a new array and then returns it.
19. 1
    4
    3
    2

# CSE110 Lab 4 Part 2
1. Line 12 returns 3 because we are calling the variable i and it adds up the total number of items in the array that we passed into the function.
2. Line 13 returns 150 because in the for it's iterating through the array of prices and multiplying 0.5 (1-0.5) and storing into the variable called discountedPrice.
3. At line 14 it returns 150 because we are taking discountedPrice and multiplying 100 and also dividing 100. 
4. It returns the prices after being calculated with the discount into the array. 
5. It returns an error because we are calling i which is out of scope since we are using the keyword "let"
6. Line 13 causes an error we are calling discountedPrice outside its scope that it was declared in.
7. It returns 150 because we calculated "finalPrice" in the for loop and it's also not out of scope where it was defined in with using the keyword "let"
8. It returns the prices after being calculated with the discount into the array. 
9. It returns an error because i was defined in the for loop and we are calling it out of scope. 
10. It returns 3 because we are returning the length of the array that contains the prices and length is not out of scope because where we are calling is still in scope.
11. This function returns the array of the discounted prices after it's been calculated in the for loop.
12. Answers for #12 part A-E (numbered 1-5) down below:
    1. student.name; 
    2. student["grad year"];
    3. student.greeting;
    4. student['Favorite teacher'].name;
    5. student.courseLoad[0];
13. Answers for #13 part A-H (numbered 1-8) down below:
    1.  '3' + 2 = '32' since integers map to their exact string representation
    2.  ‘3’ - 2 = 1 since we are subtracting therefore the output is in an integer
    3.  3 + null = 3 since we are adding to null which is esentially adding to nothing
    4.  ‘3’ + null = '3null' because we are concatenating 
    5.  true + 3 = 4 since true is 1 therefore we are adding 1 and 3 together 
    6.  false + null = 0 since false is zero therefore we are adding zero and zero together
    7.  '3' + undefined = '3undefined' since we are concatenating 
    8.  '3' - undefined = NaN since we are subtracting a string and undefined so it cannot subtract those two together
14. Answers for #14 part A-H (numbered 1-6) down below:
    1.  '2’ > 1 = true since we are evaluating the expression and 1 is an integer
    2.  ‘2’ < ‘12’ = false since we are evaluating two strings instead of integers
    3.  2 == ‘2’ = true since 2 and '2' are equal to each other because they are the same value 
    4.  2 === ‘2’ = false since these two aren't the same type
    5.  true == 2 = false since they aren't the same value
    6.  true === Boolean(2) = true because Boolean(2) returns true and evaluate both to be the same type and value
15. The difference between == and === is where == check if both expressions are the same value and === checks if both expressions are the same type and value.
16. the answer is in part2-question16.js file 
17. In the function, it will return a new array called newArr which contains 2, 4, 6. The method modifyArray takes in two parameters array and callback and in line 2 there's a new array created called newArr. Then in the for loop it iterates through the the array and for each element it calls the callback function which takes us to line 9 and in the function doSomething it multiply the parameter by 2 and pushes the result of that function into the new array. Once the function is done then it returns the new array.
18. The answer is in part2-question18.js file
19. The output for the code is: 1 4 3 2 


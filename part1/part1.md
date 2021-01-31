1. It will log the length of the price array because i is incremented through the price array and can be accessed outside the loop due to it being declared as var.
2. It will log the discounted price of the last object in the prices array. Discounted price is a var and can be used outside the for loop. 
3. It will log the value of finalPrice which is the discounted price, but rounded to the 100th place. This is because finalPrice was created as a var, and it will store the last iteration of the loop and be accessed outside the loop block.
4. The result will be [50,100, 150]. The for loop will iterate through the inputted prices array. For each iteration, it will multiply the price by 0.5. The new discounted price times 100 will be rounded to the nearest integer, and then be divided by 100. This calculated value is now added to the discounted array. We do this for every element in the prices array, which results in our array also being an array.
5. This will return a reference error because "i" was defined as a let variable, and therefore cannot be accessed outside the code block. 
6. This will return a reference error because discoutnedPrice was defined as a let inside the for loop, and therefore cannot be accessed outside the code block.
7. This will return the finalPrice. This let can be accessed because the let was defined outside the for loop, which makes it in the same scope.
8. It will return the same answer [50,100,150] due to the same reasons as question four. The errors in the logs method does not change the functionality.
9. It will return a reference error because i is a let that is not defined in the same scope.
10. It will return a reference error because discountdPrice is a const that is defined within the loop, which makes it out of scope.
11. Assuming no errors are thrown, it will return 0 as finalPrice is a const.
12. As a whole, the function will return errors as it will be trying to reassign finalPrice which is a const. 
13. 
- A) student.name
- B) studnet['Grad Year']
- C) student.greeting()
- D) student['Favorite Teacher'].name
- E) student.courseLoad[0]
14. 
- A) '32' Since a number is being added to string, the number is converted to a string
- B) 1 The subtraction only works for number, therefore it changed the string '3' into a number
- C) 3 Since it starts with a number and addition, the null is convereted to a number which is 0. Thus, 3 + 0 = 3
- D) '3null' Since it is a string followed by addition, it converts null into a string.
- E) 4 Since true is equivalent to 1, true has been converted to 1 and then added to 3.
- F) 0 Since false is followed by a addition, it is converted to 0 which it is equivalent to. Then null is converted to 0 because it is being added to a number. 
- G) '3undefined' Since it is a string followed by addition, the undefined is converted into a string and concatenated to '3'. 
- H) Nan Since "3" is followed by subtraction, it is converted to number 3. Undefined is converted to Nan as it is a numeric operation. Nan is returned because it overpowers all numeric operations.
15. 
- A) true The string '2' is converted into number 2.
- B) false Since both are strings, it compares the first character '2' with '1' to see if it is less than. Therefore, it returns false.
- C) true Since they are different types, the '2' is converted to a number. 2 is equal to 2.
- D) false === makes it so that it checks without type conversion. Since there two are different types, it returns false.
- E) false Since true is equal to 1, the expression is 1 == 2 which is false.
- F) true Boolean(2) will return true for numbers that are nonzero. This the expression becomes true === true. Both the type and value are equal.
16. == only checks if the values are equal and will convert types while === will check if the type (without conversion) and value are both equal
17. Will return 'How are you?' because the 2 is converted to a boolean aka true.
18. Go to part1-question18.js
19. The result is [6,8,10]. We iterate through every element in the input array. For each iteration, we call doSomething(array[i], function(x)). Since doSomething callbacks to function(x), it returns function( array[i] + 2 ). This mean that during each iteration, the original element is being added by 2 and then multipled by 2 (Since function(x) returns x * 2). Thus, we get [6,8,10] from [1,2,3]. 
20. Go to part1-question20.js
21. The answer is 1432. The 1 gets printed first since there is no timer and is the first code to be executed. 4 is printed next since there is no timer. 3 is printed after 4 because setTimeout runs after other non timer methods despite having a delay of 0. Finally, 1 is printed as it has the highest delay.

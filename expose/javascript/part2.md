1. At line 12 the variable i from the loop is being outputted (in this case it's 3) because i is declared using var and therefore its scope is the entire function allowing the console.log statement to still access the variable i since it is within the function.
2. At line 13 the discountedPrice variable will be outputted (in this case it's 150) because it is declared using var and therefore its scope is the entire function allowing the console.log statement to still access the variable since it is within the function.
3. At line 14 the finalPrice variable will be outputted (in this case it's 150) because it is declared using var and therefore its scope is the entire function allowing the console.log statement to still access the variable since it is within the function.
4. This function will return an array of all of the prices after the discount has been applied to each of them (in this case it's [50, 100, 150])because the code iterates through the array of original prices and applies the discount to each of them and stores them in a new array that is returned at the end of the function.
5. Line 12 causes an error because i is declared using the let keyword so it only has a block scope so it is only accessible to the for loop block and the console.log statement is outside of that so it doesn't have access to it.
6. Line 13 causes an error because discountedPrice is declared using the let keyword so it only has a block scope so it is only accessible to the for loop block and the console.log statement is outside of that so it doesn't have access to it.
7. At line 14 the finalPrice variable will be outputted (in this case it's 150) because it is declared using let within the function so its scope is the entire function allowing the console.log statement to still access the variable since it is within the function.
8. This function will return an array of all of the prices after the discount has been applied to each of them (in this case it's [50, 100, 150])because the code iterates through the array of original prices and applies the discount to each of them and stores them in a new array that is returned at the end of the function. Even though the variables are declared with let they are all used properly within their respective scopes so the function operates as it should. 
9. Line 11 causes an error because i is declared using the let keyword so it only has a block scope so it is only accessible to the for loop block and the console.log statement is outside of that so it doesn't have access to it.
10. Line 12 will output the length of the prices array (in this case it's 3) because that is what it was initially initialized with when declared with the const keyword and it was never changed.
11. This function will return an array of all of the prices after the discount has been applied to each of them (in this case it's [50, 100, 150])because the code iterates through the array of original prices and applies the discount to each of them and stores them in a new array that is returned at the end of the function. Even though the variables are declared with const they are all used properly without them ever being reassigned, so the function operates as it should.
12. A. student.name;
    B. student['Grad Year'];
    C. student.greeting();
    D. student['Favorite Teacher'].name;
    E. student.courseLoad[0];
13. A. 32 because integers map to their exact string representation.
    B. 1 because the subtraction makes the 3 map to its integer value.
    C. 3 because null has the value of 0.
    D. 3null because 3 is a string so 'null' is concatenated. 
    E. 4 because true maps to 1.
    F. 0 because false and null have a value of 0.
    G. 3undefined because 3 is a string so 'undefined' is concatenated. 
    H. NaN because the undefined makes the entire math operation undefined. 
14. A. true because '2' mapped to its integer value and 2 is greater than 1.
    B. false because in terms of characters '2' is less than 12.
    C. true because the '2' mapped to its integer value and 2 equals 2.
    D. false because they are different types and === doesn't automatically convert them.
    E. false because true maps to 1 and 1 does not equal 2.
    F. true because the boolean object has a value of true
15. == automatically converts the variable types to the same type for the comparison whereas === does not do any type conversion to the variables. 
16. 
17. The result will be a new array that contains [2, 4, 6] since the function will call doSomething for each element in array and doSomething returns the value * 2 and modifyArray takes that value and adds it to the new array that will be returned.
18. 
19. 1
    4
    3
    2

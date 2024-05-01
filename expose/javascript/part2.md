1. It will print "3". This is because var is function scoped and not block scoped so it will allow users to access it within the same function. 
2. It will print "150". This is because var is function scoped and not block scoped so it will allow users to access it within the same function. 
3. It will print "150". This is because var is function scoped and not block scoped so it will allow users to access it within the same function. 
4. The function will return the list [50, 100, 150]. This is because var is function scoped and not block scoped so it will allow users to access it within the same function. Because of this condition, the function executes normally and calculates the prices discounts and returns such list as shown. 
5. It will return an error (ReferenceError) because i is not within the scope of the for loop (this is because we are currently using let which uses block scoping).
6.  It will return an error (ReferenceError) because discountedPrice is not within the scope of the for loop (this is because we are currently using let which uses block scoping).
7. It will print "150". This is because the print statement is within the scope of the function, so we are able to print the finalPrice of the last iteration. 
8. The function will return the list [50, 100, 150]. This because functions are declared and called within their scope, so this will result in no errors, and the discountedPrices is able to run as intended and return the desired list shown earlier. 
9. It will return an error (ReferenceError) because i is not within the scope of the for loop (this is because we are currently using let which uses block scoping).
10. It will print "3". Since we are not modifiying the const variable, and it is within scope, it will print the length of the input list prices.
11. The function will return the list [50, 100, 150]. This is because everything is scoped correctly so there are no ReferenceErrors, as well as the fact that we are not reassigning any const variables. Because of these conditions, the function will execute normally and calculates the price discounts and returns the resulting list. 
12. A: student.name; 
    B: student['Grad Year']; 
    C: student.greeting() 
    D: student['Favorite Teacher'].name; 
    E: student.courseLoad[0]
13. A: '32' , Because adding a string and a number concatenates it to the string
    B: 1 , Substracting a string number and a number allows for normal arithmatic operations
    C: 3 , adding null essentially acts as adding 0 within javascript
    D: '3null' , null is converted into a string and combined with the string number
    E: 4 , true is converted to 1 when doing arithmatic operations
    F: 0 , false is converted to 0 and null represents 0 when doing arithmatic operations
    G: '3undefined' , undefined is converted into a string and concatenated to 3
    H: NaN , undefined is converted/treated as NaN when converted to a number and any operation with NaN results in NaN
14. A: True , 2 is converted into an integer and the comparison is made
    B: True, since 12 is a greater string lexicographically
    C: True , the '2' is converted into a number before comparing
    D: False , since there are three '=' it checks for type as well in comparison
    E: False , since True is converted into 1 when comparing
    F: True , because boolean of any nonzero number is converted to true
15. The == operator is the equality operator and it compares two values to check if they are equal. It will convert both objects to a common type if they are not the same type to begin with. The '===' operator (also known as the strict equality operator) compares both the value and the type of the two objects. If the types do not match it is automatically declared as false. 
16. In part2-question16.js
17. The result will be [2,4,6] . This because the initial call brings us to the first function modify array. Here we create a const new Array where we will store the updated values. Then we go within the loop and call the function that is in the parameter for each indicies in the array. The function essentially takes the number stored in the array and multiplies it by 2. Once this is all finished, we return the new array. 
18. Answer in part2-question18.js
19. 1 4 3 2 , This is because 1 and 4 are printed immediately as there is no timeout. Since there is a setTimeout for 3 and 2, 3 has the smallest timeout, so 3 is printed next. Lastly 2 is printed since it has the longest timeout.
    
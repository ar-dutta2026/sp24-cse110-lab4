1. The code prints: "values added: 20"
2. The code prints: "final result: 20"
3. The code prints: "values added: 20"
4. This results in a error (particularly a ReferenceError). This is because result is declared inside the if statement block which means that it has block scope and is inaccessible outside of that if statementblock. Line 13 is attempting to access result outside of the if statement resulting in the error. 
5. This results in an error because we are attempting to reassign the const variable in line 7 after initially declaring it at line 5. This is not allowes as const variables cannot be reassigned after declaration. 
6. This would cause the same issue as question 5, because the const variable has been reassigned at line 7. 
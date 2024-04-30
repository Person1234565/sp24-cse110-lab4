1. Line 9 prints 20. 
2. Line 13 prints 20 as well. 
3. Line 9 prints 20. 
4. Line 13 does not print anything and instead errors since the variable "result" only has block scope, and line 13 tries to access it outside of this scope. 
5. Nothing is printed by line 9. The code returns an error before line 9 since result was attempted to be reassigned on line 7, which is not allowed for const variables. 
6. Nothing is printed by line 13. The code returns an error before line 13 since result was attempted to be reassigned on line 7, which is not allowed for const variables. 

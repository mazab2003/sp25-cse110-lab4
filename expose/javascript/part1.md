1. values added: 20
2. final result: 20
3. Because it is function-scoped, not block-scoped. This can lead to bugs as variables declared inside a block are still accessible outside it anywhere in the function.

4. values added:  20
5. ReferenceError: result is not defined; this is because 'result' was declared with 'let' inside a block, which is not accessible outside the block in line 13. 

6. TypeError: Assignment to constant variable; this is because line 7 is trying to reassign 'result' which is not possible as it was declared as a constant. 

7. ReferenceError: result is not defined; this is because 'result' was declared with 'const' inside a block, which gives the same scope as 'let,' thus, it is not accessible outside the block in line 13. 



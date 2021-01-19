# Debugging
- The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
- execution contexts: There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope. 
- two phases of activity :
1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined
2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements
- each execution context has its own va ri ables object.It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object. 
- exception:At that point, the interpreter stops and looks for exception-handl ing code. 
- Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
- ERROR OBJECTS CONTI NUED :
Syntax Error 
Ref erenceError 
Ev alError 
UR I Error 
- If you understand execution contexts (which have two stages) and stacks, you are more likely to find the errorin your code.
- Debugging is the process of finding errors. It involves aprocess of deduction.
- The console helps narrow down the area in which the error is located, so you can try to find the exact error.
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
- If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.Use them to give your users helpful feedback
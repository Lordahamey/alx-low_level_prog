A nested while loop is a while statement inside another while statement. In a nested while loop, one iteration of the outer loop is first executed, after which the inner loop is executed. The execution of the inner loop continues till the condition described in the inner loop is satisfied.
The C-function
A function is a group of statements that together perform a task. Every C program has at least one function, which is main(), and all the most trivial programs can define additional functions.

A function definition in C programming consists of a function header and a function body. Here are all the parts of a function −

Return Type − A function may return a value. The return_type is the data type of the value the function returns. Some functions perform the desired operations without returning a value. In this case, the return_type is the keyword void.

Function Name − This is the actual name of the function. The function name and the parameter list together constitute the function signature.

Parameters − A parameter is like a placeholder. When a function is invoked, you pass a value to the parameter. This value is referred to as actual parameter or argument. The parameter list refers to the type, order, and number of the parameters of a function. Parameters are optional; that is, a function may contain no parameters.

Function Body − The function body contains a collection of statements that define what the function does.

A FUNCTION PROTOTYPE
The Function prototype is necessary to serve the following purposes:

Function prototype tells the return type of the data that the function will return.
Function prototype tells the number of arguments passed to the function.
Function prototype tells the data types of each of the passed arguments.
Also, the function prototype tells the order in which the arguments are passed to the function.
Therefore essentially, the function prototype specifies the input/output interlace to the function i.e. what to give to the function and what to expect from the function.

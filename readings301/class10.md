# The Call Stack and Debugging #

## call stack ##
- A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
- A call stack is a mechanism for an interpreter  to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

## JavaScript call stack ##
- The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.
- Call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.
- LIFO: ( Last In, First Out) it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
- When the code is run, we get an error. A stack is printed showing how the functions are stack on top each other.
- Temporarily store: When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

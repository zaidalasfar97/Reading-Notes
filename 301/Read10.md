# A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.
# When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
# Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
# When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
# If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
# Understanding the JavaScript Call stack:
# At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
# LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
# Temporarily store: When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.
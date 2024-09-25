# Everything in JavaScript happens inside the Execution Context.

# Execution Context (Big Box)
The execution context has two main components:

1. Memory Component (Variable Environment):
This is where all the variables and functions are stored as key-value pairs. For example:

a: 2
fun: { ... }

3. Code Component (Thread of Execution):
This is responsible for executing the code, line by line. It's where JavaScript keeps track of which line of code is being run.

# Synchronous and Single-Threaded
Single-Threaded: JavaScript executes one command at a time, meaning it can only do one thing at a moment.

- Synchronous: Each line of code is executed in sequence. The next line of code is executed only after the current one has finished.
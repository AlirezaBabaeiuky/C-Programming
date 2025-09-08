# C-Programming
C projects (package)
scanf("%f %f %f", &L1, &L2, &L3); --- note not to use , comma in between the f meaning "%f, %f" is NOT correct 
break should always be used in for loop or switch.
return 0; is a language keyword that exits the current function. If it's in main(), it also triggers a proper program shutdown, including calling destructors for local objects.
exit(0); is a system call that forces immediate termination of the process from anywhere in the program, bypassing standard function exits and object cleanup
A variable declared in a block has a lifetime throughout this block, but disappears upon block exit.
The first character of an identifier must be a letter or an underscore
A variable in C is a named piece of memory which is used to store data and access it whenever required. It allows us to use the memory without having to memorize the exact memory address.
Your understanding is incorrect. The core difference is that defining a variable allocates memory, while declaring it does not. Initialization is a separate action where a value is assigned. 
Declaration: States a variable's name and type, telling the compiler it exists. An extern declaration is a classic example: extern int a;.
Definition: A declaration that also allocates storage for the variable. In C, a simple int a; statement inside a function is both a declaration and a definition.
Initialization: Assigning a value to a variable at the time of its definition, such as int a = 5;. 





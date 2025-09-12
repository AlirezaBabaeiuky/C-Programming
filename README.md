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
The key point in using a local to a function static variable is: its value is retained upon function exit. 
Recursive fibonacci shows one pitfall in using it versus an iterative calculation: That is function call is expensive in both time and space
Which keyword tells the compiler to look for a variable’s definition elsewhere? extern 
int a;
int main()
{
   int b;
   // ..
   // ..
}
int c;
answer: a
The values and variables used with operators are called operands.
pointer to int and pointer to double are different and this difference can affect both how much memory is pointed at – for example an int may be in 4 bytes and a double may be in 8 bytes;  and interpretation  -namely how the bits are interpreted.  
When using a reference declaration in a function header to simulate call-by-reference, it means the referenced variable in the calling environment can be changed
reason why we use & (ampersand) when getting an input from user is to store the value if the variable in the memory address. To store the input at the variable’s memory address.
Recap: all JUMP statements should be used within iterative (for) loop. break, continue, goto, return. --- break is a control statement that immediately jumps out of the loop (forces th eprogram to terminate the loop/iteration). continue is the opposite and it forces the program to do the next iteration inside the loop and skip whatever following the continue.
jump statements are all loop control statements. and except return, all jump statements need conditional statement as well the iterative loop. Function declaration VS definition: declaration tells the compiler about function name and return type. Definition tells the full code or logc in a function and includes the full implementation.     
Array declaration: When we declare an array in C, the compiler allocates the memory block of the specified size to the array name.
Recapp: format specifier for pointer is: p meaning: %p
We have to first dereference the pointer to access the value present at the memory address. This is done with the help of dereferencing operator(*) (same operator used in declaration). Yes, arrays are always passed to functions as pointers in C. The compiler automatically converts the array name arr into a pointer to its first element when the printArray(arr, n) function is called
scanf does not read the entire line, to do so use: fgets() with thi ssyntax: fgets(string_name, 20, stdin); 
Heap segment is where dynamic memory allocation takes place. Static variables can be used to count the number of times a function is called



 




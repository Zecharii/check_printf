## printf
The printf project is a collaboration between Zechariah Gaiya and Oji Benedict, students of Software Engineering at ALX, where a function named **_printf** imitates the actual **printf** command located in the **stdio.h** library. **_printf** is a function that performs formatted output conversion and prints data. It contains some of the basic features and functions found in manual 3 of **printf**.

The prototype:

	int _printf(const char *format, ...)

Where **format** contains the string that is printed. As _printf is variadic in function, it can receive n arguments that can be replaced by n tags written inside the string.

The **format** tag is:

	%[flags][length]specifier
	
If the program runs successfully, the **return value** is the amount of chars printed.
	
| Specifier | Output |
| ------------- | ------------- |
| c  | character  |
| d or i | signed decimal integer |
| s  | string of characters  |
| b  | signed binary  |
| o  | signed octal  |
| u  | unsigned integer  |
| x  | unsigned hexadecimal  |
| X  | unsigned hexadecimal (uppercase)  |
| p  | pointer address  |
| r  | reverse string of characters |
| R  | ROT13 translation of string |
| S  | string with special chars replaced by their ASCII value  |
| %  | character  |

| Flags | Description | Specifiers |
| ------------- | ------------- | ------------- | 
| +  | Prints a plus sign (+) when the argument is a positive number. Otherwise, a minus sign (-). | i, d |
| (space) | Prints a blank space if the argument is a positive number | i, d |
| #  | Prints 0, 0x and 0X for o, x and X specifiers, respectively. It doesn't print anything if the argument is zero | o, x, X |

| Length | Description | Specifiers |
| ------------- | ------------- | ------------- | 
| l | Prints a long int or unsigned long int | i, d, o, u, x and X |
| h | Prints a short int or unsigned short int | i, d, o, u, x and X |

------------

## File Functions

| File | Description |
| ------------- | ------------- |
| README.md | The file that contains a description of what the project is all about. |
| main.h | This file contains all the prototypes, flags, sizes, functions, and utils. |
| main.c | This file contains the main program of the **printf** project. |
| _printf.c | This is our own printf function that performs formatted output conversion and prints data. |
| flag.c | This file lists all the flag variables used in the project. |
| get_width.c | This file contains the code that calculates the width for printing. |
| handle_print.c | This file prints an argument based on its type. |
| handlers.c | This file contains the list of handlers that you compile together with the rest of the program. |
| precision.c | |
| print_functions.c | |
| print_functions1.c | |
| print_functions2.c | |
| size.c | |
| utils.c | |

------------

### Authors
Zechariah Gaiya
Oji Benedict

------------

### End
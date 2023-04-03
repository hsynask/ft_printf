# ft_printf Function
The ft_printf function is a custom implementation of the printf function in the C programming language. It takes a format string and a variable number of arguments, and prints the formatted output to the console.

## Description
The ft_printf function behaves like the printf function in most respects, but it is a custom implementation that you have written yourself. The function takes a format string, which can include placeholders for various types of data, and a variable number of arguments that correspond to the placeholders in the format string.

The key to a successful implementation of ft_printf is to handle a wide range of format strings and argument types, and to provide a flexible and extensible function that can be easily modified to support new placeholders and formatting options.

### Placeholders
The ft_printf function supports a wide range of placeholders, including:

%c for a single character
%s for a string
%d for a signed integer
%i for a signed integer (same as %d)
%u for an unsigned integer
%x for a hexadecimal integer (lowercase)
%X for a hexadecimal integer (uppercase)
%p for a pointer address
%f for a floating-point number
%e for a floating-point number in scientific notation (lowercase)
%E for a floating-point number in scientific notation (uppercase)

Each placeholder can be modified with various formatting options, such as field width, precision, and justification.

#### Usage 

To use the ft_printf function in your project, include the function prototype in your code
Then, call the ft_printf function with a format string and any necessary arguments, just like you would with the printf function.


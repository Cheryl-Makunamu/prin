#printf project

1. Function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
format is a character string. The format string is composed of zero or more directives.Handled the following conversion specifiers:
c
s
%

2. Handled the following conversion specifiers:
d
i

3. Handled the following conversion specifiers:
u
o
x
X

4. Used a local buffer of 1024 chars in order to call write as little as possible.

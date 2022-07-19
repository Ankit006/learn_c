# Input and output in C

We can output any data using printf function.
Now if want to print a text and in that text we need to have a variable value. Then we can use format specifier.(view code example)

## format specifer for variables
1. %d for int
2. %f for float 
3. %c for char
4. %lf for double
5. %hd for short int
6. %u for unsigned int
7. %ld, %li for long int
8. %lld,%lli for long long int
10. %lu for unsigned long int
11. %llu for unsigned long long int
12. %Lf for long double

## Get input using Scanf
To get user input we use scanf function. Scanf function take two argument. 
First is format specifier and second is a variable (in this variable input data will be stored). Also, append an ampercent sign (&) before the variable name. '&' symbol spcifie memory address of the variable. So, scanf funtion store data in memory using the memory address of the variable.
# Assignment One 

This assignment will allow you to get familar with the distribution and submission of assignments using GitHub and GitHub Classroom.  We will also do our first C program and look at the implementations of *functions, arrays, and strings* in C.  

## Problem
Write a C program (using the **longest.c** starter file) that will read lines of input from standard input (STDIN), compare each of the lines read from standard input and display the longest input line to standard output (STDOUT). Many of the utility programs in Linux and Unix function the same where they read from *STDIN* (No input prompt) and write to *STDOUT*.  These types of programs are called **filters**.  Your program's output should look like the following example:

### Sample Input

```
This is a test
This is a big test
That is all
```

### Test Program
Redirect a file to STDIN
```
./longest < input.txt
```

### Correct Output
```
This is a big test
```
A line from standard input ends with a *'\n'* newline character or *EOF* (End of File).  The **only functions from the standard C library that you can use** in your program are:
* **getchar()** - Reads a character from STDIN
* **putchar()** - Writes a character to STDOUT

Use the attached starter source file, *longest.c*.  Your program must have the following functions implemented in your code.
* **int getString(char str[], int maxlen)** This functions reads a line from standard input into *str* up to the *maxlen*. The function returns the length of the string (Not including the terminating null character, '\0').
* **void putString(char str[])** This functions writes the string, *str* to standard output.
* **void copyString(char src[], char dest[])** This function copys the string in *src* to *dest*.

### Remember: Strings in C are an array of characters terminated with a null character '\0'.   

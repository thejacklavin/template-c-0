# C Module 0: Introduction

## Exercise 0.1
> Use the editor below to write your first C program mimicking the one above, but with a more creative message.

```
#include <stdio.h>

int main ()
{
  printf ("Who let the dogs out?\n");
  for (int i=0; i<10; i++) {
    printf ("Who?  ");
  }
  printf ("Who?\n");
}
```

## Exercise 0.2
> Type up and compile the above program.
> What is the compiler error reported?

exit status 1
main.c:3:1: error: unknown type name 'Int'; did you mean 'int'?
 Int main ()
 ^~~
 int

## Exercise 0.3
> What is the error produced by compiling this program?

exit status 1
/usr/lib/x86_64-linux-gnu/crt1.o: In function `_start':
(.text+0x20): undefined reference to `main'
collect2: error: ld returned 1 exit status

## Exercise 0.4
> What is the error produced by compiling this program?

exit status 1
main.c: In function 'main':
main.c:5:3: warning: implicit declaration of function 'Printf'; did you mean 'printf'? [-Wimplicit-function-declaration]
   Printf ("Hello World!\n");
   ^~~~~~
   printf
/tmp/ccgupul3.o: In function `main':
main.c:(.text+0xf): undefined reference to `Printf'
collect2: error: ld returned 1 exit status

## Exercise 0.5
> What is the error produced by compiling this program?

exit status 1
main.c:4:1: error: expected declaration specifiers or '...' before '{' token
 {
 ^

## Exercise 0.6
> What is the error produced by compiling this program?

exit status 1
main.c: In function 'main':
main.c:5:11: warning: missing terminating " character
   printf ("Hello World!\n);
           ^
main.c:5:11: error: missing terminating " character
   printf ("Hello World!\n);
           ^~~~~~~~~~~~~~~~~
main.c:6:1: error: expected expression before '}' token
 }
 ^
main.c:5:11: error: expected ';' before '}' token
   printf ("Hello World!\n);
           ^
           ;
 }
 ~

## Exercise 0.7
> What is the error produced by compiling this program?

exit status 1
main.c: In function 'main':
main.c:5:28: error: expected ';' before '}' token
   printf ("Hello World!\n")
                            ^
                            ;
 }
 ~

## Exercise 0.8
> What is the error produced by compiling this program?

exit status 1
main.c: In function 'main':
main.c:5:3: error: expected declaration or statement at end ofinput
   printf ("Hello World!\n");
   ^~~~~~

## Exercise 0.9
> What is the error produced by compiling this program?

No errors, but a warning:

main.c:3:1: warning: return type defaults to 'int' [-Wimplicit-int]
     main ()
             ^~~~

## Exercise 0.10
> What kind of a compiler error do you get if you try to use a reserved word as an identifier? Use a reserved word to declare an integer identifier.

exit status 1
main.c:8:5: warning: 'printf' defined as variadic function without prototype
 int printf ()
     ^~~~~~
In file included from main.c:1:
/usr/include/stdio.h:364:12: note: previous declaration of 'printf' was here
 extern int printf (const char *__restrict __format, ...);
            ^~~~~~
main.c: In function 'printf':
main.c:9:1: error: number of arguments doesn't match prototype
 {
 ^
In file included from main.c:1:
/usr/include/stdio.h:364:12: error: prototype declaration
 extern int printf (const char *__restrict __format, ...);
            ^~~~~~

## Exercise 0.11
> What happens if you omit the "L" or "LLU" when declaring numStarsInUniverse and largestIntegerInC? What happens if you use `%d` for the largestIntegerInC print statement?

## Exercise 0.12
> Adjust the amount of space used in the printf call. What happens if x has more digits than are reserved? What happens if it has fewer digits?

## Exercise 0.13
> What print command would you use to print PI with a reserved width of 10 characters and only one digit after the decimal place? Does the reserved width include the decimal point and "e+" notation characters?

## Exercise 0.14
> It's a common error to mistype the format string. What happens when you reverse the `%d` and `%f` specifiers in the program above?

## Exercise 0.15
> What happens if you use double quotes when assigning a char? What happens if you put multiple letters within single quotes?

## Exercise 0.16
> Use the ASCII table above to assign `c1` and `c2` to numeric values that represent your initials. Then print them using both the `%d` and `%c` format specifiers.

## Exercise 0.17
> What is the program's output?

## Exercise 0.18
>  Put the following code into the editor below. What does it print out? What is its significance?

## Exercise 0.19
> What happens when you try to modify one of the `const` variables? Is this a compile-time or a run-time error?


## Exercise 0.20
> There is a bug in this code! Why won't it print "i is not 5" like the developer expected? Is this a compile-time or run-time error?


## Exercise 0.21
> Without running it, what is the error in the code?


## Exercise 0.22
> Use for-loops to print "hourglasses" of different sizes. Enter your code here:

```
// Paste your program here

```

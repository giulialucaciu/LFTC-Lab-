

THE PROBLEM:

#include<iostream> 
using namespace std; 
int main() {
int i, sum;
int v[3] = {1,2,3}; 
i = 0;
sum = 0;
if ( i >= 0 ) {
i = i + 1; 
while ( i <= v[3] ) {
sum = sum + v[i]; 
i = i + 1; }
} 
cout<<sum; 
return 0;
}

-------------------------

GIT LINK:
https://github.com/giulialucaciu/LFTC-Lab-

I uploaded two screenwhots of my result in the Temrinal.
          
-------------------------
          
# Lexical analyzer

## Problem statement

The scanner's input will be a text file containing the source program, and will produce as output the following:

- PIF - Program Internal Form

- ST  - Symbol Table

In addition, the program should be able to determine the lexical errors, specifying the location, and, if possible, the type of the error.

## User guide

The scanner uses the following commands:

```
lex lex-analizer.l
gcc lex.yy.c
./a.out greatest-common-divisor.txt
```

The first command generates the lex.yy.c file, while the second one generates the executable a.out.


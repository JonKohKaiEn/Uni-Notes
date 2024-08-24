Header File|Description
---|---
`stdio.h`|Input/Output
`math.h`|Math functions
`ctype.h`|Character handling
`stdlib.h`|Miscellaneous functions
`time.h`|Time functions

# stdio.h

```
printf();  // normal print
putchar();  // displays 1 character

scanf();  // normal input
getchar();  // get 1 character from input stream

fflush();  // flushes I/O buffer

Example
Input:
10
A

Wrong way
scanf("%d%c", &d, &c);  // d = 10, c = \n

Correct way
scanf("%d", &d);
fflush(stdin);  // clear the input buffer
scanf("%c", &c);

or

scanf("%d", &d);
getchar();  // get the next char but don't save it to a variable
scanf("%c", &c);

getchar() can also be used to pause the program until "Enter" is pressed
```

# math.h

## Common functions

Function|Description|Input|Output
---|---|---|---
`fabs(x)`|Absolute value of number|`int` or `float`|`float`
`sin(x)`, `cos(x)`, `tan(x)`|Trigonometric functions|`int` or `float`, in radians|`float`
`pow(x,y)`|x to the power of y|`float` or `double`|`double`
`sqrt(x)`|square root|`float` or `double`|`double`
`ceil(x)`|Round up|`double`|`double`
`floor(x)`|Round down|`double`|`double`

# ctype.h

```
isalpha()
isdigit()
isalnum()
islower()
isupper()

returns non-zero if true
returns zero if false

tolower()
toupper()
converts single character
```

# stdlib.h

```
abs(x)  // returns integer (different from fabs())

rand()  // generates random integer between 0 to 32767
srand()  // sets random number generator seed

Usage:
#include <stdlib.h>
#include <time.h>

int main(void)
{
	int random;
	srand((unsigned) time(NULL));
	random = rand();
}
```
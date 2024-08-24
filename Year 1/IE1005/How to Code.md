### General Structure
```
#include <stdio.h>

int main(void)
{
	// Declaration/Initialisation of variables

	// Logic/Calculation

	// Output

	return 0;
}
```

### Guidelines for variable names
- Do not use keywords (`int`, `case`, etc.)
- Do not use special characters (`/`, `-`)
- Make sure your variables explain what it represents

### Input / Output
```
int age;
printf("Please input your age: ")  // prints out a prompt
scanf("%d", &age)                  // waits for input
printf("Your age is: %d", age)     // Your age is <age>

float pi = 3.14159;
printf("%8.3f", pi);  // 3.142
printf("%8.5f", pi);  // 3.14159
printf("%3.5f", pi);  // 3.14159 (Since 3 is to small, ignores it)
printf("%.3e", pi);   // 3.142e+000

printf("This is a percent character: %%");
printf("This is a double-quote: \"");
printf("This is line 1\nThis is line 2");
printf("\t There is a tab here")
```

### Operators
```
int a, b, c;
float b_float,

// assignment
a = 7;
b = 2;
b_float = 2.0;

// operators
c = a + b;        // c = 9
c = a % b;        // c = 1
c = a / b;        // c = 3 (both are int, so result will be int)
c = a / b_float;  // c = 3 (since b_float is a float, result is float)
c = a / (float)b  // c = 3.5 (typecasting)
```

### If - else if - else
```
if (condition 1){
	// do something
} else if {
	// do something 2
} else {
	// do something 3
}
```

### Switch statement
```
switch (expression)  // can be integer or char
{
	case value1:
		// do something
		break;

	case value2:
		// do something 2
		break;

	default:
		// do something 3
}
```
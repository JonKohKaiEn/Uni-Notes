## How data is stored
- Data is stored in RAM as binary (1 or 0)
- When a new variable is created, a space in RAM is reserved for the variable

## Integer
- Only used for integer values
- Represented exactly by binary
- Space: 32 bits (4 bytes)
- Range: -2,147,483,648 to 2,147,483,647
- Declaration: `int`
- Conversion Specifier: `%d`
- Other datatypes for integers
	- `short`
	- `unsigned int`
	- `unsigned short`
- Overflow can occur if the number that you want to represent is greater than what the datatype can represent

## Character
- Used for individual characters (alphabets, symbols)
- Represented using integers (ASCII code)
	- For other languages, may need UNICODE
- Space: 8 bits (1 byte)
- Declaration: `char`
- Conversion Specifier: `%c`

## Float
- Mainly used for numbers with decimals
- Parts of a floating-point number
	- Sign bit (1 bit)
	- Exponent (8 bit)
	- Mantissa (23 bit)
- Only has 6-7 bits of precision (single precision)
- Declaration: `float`
- Conversion Specifier: `%f`, `%e`, `%E`
- Other datatypes for decimal numbers
	- `double` - 14-15 digits of precision (double precision)
	- `long double`

Datatype|Declaration|Range|Space
---|---|---|---
Integer|`int`|-2,147,483,648 ($-2^{31}$) to 2,147,483,647 ($2^{31}-1$)|32 bits (4 bytes)
Character|`char`|ASCII Table (-128 to 127)|8 bits (1 byte)
Float|`float`|1.2E-38 ($1.2\times10^{-38}$) to 3.4E38 ($3.4\times10^{38}$)|32 bits (4 bytes)







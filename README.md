# Ft Printf

This project consists of rewriting fews capabilities of the function printf.

The programm is able to reprodruce the following conversions: **cspdiuxX%**

| Flag  | Description														 |
|-------|--------------------------------------------------------------------|
| **-** | Left justify         |
| **0** | Field is padded with 0's instead of blanks |
| **+** | Sign of number always O/P |
| **#** | Prefix 0x to the output value when used with the hexadecimal conversion character x|

It is able to manage any combination of the following flags: **-0.\*** and minimum field
width with all conversions.

| Conversion | Description					|
|------------|------------------------------|
| **c**		 | Character	|
| **s**		 | String		|
| **p**		 | Pointer		|
| **d**		 | Decimal signed integer			|
| **i**		 | Decimal signed integer			|
| **x**		 | Hex integer (lowercase)	|
| **X**		 | Hex integer (uppercase)	|
| **%**		 |  %. No argument expected			|

## Compilation
`make`

## Linking
`gcc -L. -lftprintf main.c`

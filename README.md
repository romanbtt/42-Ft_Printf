# Ft Printf

This project consists of rewriting fews capabilities of the function printf.

The programm is able to reprodruce the following conversions: **cspdiuxX%**

| Flag  | Description														 |
|-------|--------------------------------------------------------------------|
| **-** | Left justify         |
| **0** | Field is padded with 0's instead of blanks             |
| **+** | Sign of number always O/P |
| **#** | Various uses: %#x (Hex)   0x prefix added to non-zero values.
	  %#X (Hex)   0X prefix added to non-zero values.                            |

It is able to manage any combination of the following flags: **-0.\*** and minimum field
width with all conversions.

## Compilation
`make`

## Linking
`gcc -L. -lftprintf main.c`

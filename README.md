# ALX Software Enginering Printf Team Project

#### This team project is a custom made printf function for the C programming language called _printf. It has been optimized to take various inputs and optional arguments based exactly on how the standard library function printf works. We submitted this as part of the ALX software engineering course requirement for grading.

The flag characters


## ( # ) 
For o conversions the first character of the output string is made zero (by prefixing a 0 if it was not zero already). For x and X conversions, a nonzero result has the string "0x" or "0X" respectively added.

## ( 0 )	
(Not implemented yet) The value should be zero padded. For d, i, o, u, x, and X the converted value is padded on the left with zeros. If the 0 and - flags both appear,the 0 flag is ignored. If a precision is given with a numeric conversion, the 0 flag is ignored.
## ( -	)
(Minus sign, not implemented yet) The converted value is to be left adjusted on the field boundary, (Default is right justification) and padded with blanks in the right rather than on the left with blanks or zeros. This flag overrides 0 if both are given.
## ( ' '	)
(Blank Space) The argument is padded with a single blank space before a positive number or empty string produced by a signed conversion.
## ( +	)
A sign (+ or -) should always be placed before a number produced with a signed conversion. By default, only negative numbers have this sign.
## d, i
The argument int is converted to a signed decimal notation. If precision is present,it gives the minimum number of digits that must appear; if the converted value requires fewer digits, then it is padded with zeros on the left. Default precision is 1.
## o, u, x, X
The argument is converted to unsigned octal (o), unsigned decimal (u), or unsigned hexamedical (x and X) notation. The letters abcdef are used for x conversion and the letters ABCDEF are used for X conversion. If precision is present, it will give the minimum number of digits that must appear; if the converted value requires fewer digits, then it will be padded with zeros. By default the precision is 1.
## Heba && Eslam

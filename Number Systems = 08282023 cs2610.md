Number Systems
- Used to count, measure, assign values
- most common systems:
	- decimal
	- binary
	- hexadecimal
	- octal

About number systems
- number systems have a base
	- decimal system has base 10
		- 0, 1, 2, 3, 4, 5, 6 9
	- unfinished*

Decimal system
- place value is greatest left to right
	- thousands, hundreds, tens, ones
	- increases by a factor of 10

binary systems
- uses 0 and 1
	- when a bit is "on" it is 1, "off" is 0
- place value in binary
	- left-most bit, most significant bit (MSB)
	- right-most bit, least-significant bit (lsb)
	- place value increases by a factor of 2

binary sample place value chart
128 = 2^7
64 = 2^6
32
16
8
4
2
1

the value of digit can either be 0 when "off" or 2^x when x is the place value on "on"

representing decimal numbers in binary
- decimal : 1, 2, 3, 4, 5, 6, 7, 8...
- binary; 01, 10, 11, 100, 101, 110, 111, 1000....

determining the base
- what is the base of 1101?
	- decimal or binary?
- this is why we note the base in the lower right corner of the number
	- 1101(down arrow 2) bs 1101 (down arrow)10
- notation is also accepted 
	- 5(down arrow 10)
	- 5(down arrow ten)

Converting binary to decimal

Example: 101(down arrow 2)
	 1(2^2) + 0(2^1) + 1(2^0)
	 1(4) + 0(2) + 1(1)
	 4 + 0 + 1 = 5(down arrow 10)

Example 1: 10101(down arrow 2)
	1(2^4) + 0(2^3) + 1(2^2) + 0(2^1) + 1(2^0)
	1(16) + 0(8) + 1(4) + 0(2) + 1(1)
	16 + 4 + 1
	= 21

- start from left to right, most sig to least sig

Example 2: 01101100(down arrow 2)
	0(2^7) + 1(2^6) + 1(2^5) + 0(2^4) + 1(2^3) + 1(2^2) + 0(2^1) + 0(2^0)
	= 0(128) + 1(64) + 1(32) + 0(16) + 1(8) + 1(4) + 0(2) + 0(1)
	= 0 + 64 + 32 + 0 + 8 + 4 + 0 + 0
	= 64 + 44
	= 108

Converting decimal to binary
- instead of multiplying, use division
	- the decimal number becomes the dividend , the divisor is alwayys 2
	- the quotient becomes the dividend and we divide all the way to 1
	- if the quotient has a remainder, mark the bit as 1
		- if no remainder, mark the bit as 0
	- dividing starts from LSB and ends at msb

Example:
5(down arrow ten)
5/2 = 2.5 - 1
2/2 = 1 - 0
1/2 = 0.5 - 1

Example 1: 109(down arrow 10)
109/2 = 54.5 - remainder 1 (lsb)
54/2 = 27 - 0
27/2 = 13.5 - 1
13/2 = 6.5 - 1
6/2 = 3 - 0
3/2 = 1.5 - 1
1/2 = 0.5 - 1 (msb)

Example 2: 100 (down arrow ten)
100/2 = 50 - remainder 0 (lsb)
50/2 = 25 - 0
25/2 = 12.5 - 1
12/2 = 6 - 0
6/2 = 3 - 0
3/2 = 1.5 - 1
1/2 = 0.5 - 1 (msb)

= 1100100(down arrow two)

Convert the following binary numbers to decimal:
- 10110010
	- 1(2^7) + 0(2^6) + 1(2^5) + 1(2^4) + 0(2^3) + 0(2^2) + 1(2^1) + 0(2^0)
	- 1(128) + 0(64) + 1(32) + 1(16) + 0(8) + 0(4) + 1(2) + 0(1)
	- 128 + 32 + 16 + 2
	- 178
- 01111000
	- 0(2^7) + 1(2^6) + 1(2^5) + 1(2^4) + 1(2^3) + 0(2^2) + 0(2^1) + 0(2^0)
	- 0(128) + 1(64) + 1(32) + 1(16) + 1(8) + 0(4) + 0(2) + 0(1)
	- 64 + 32 + 16 + 8
	- 120
- 01101110
	- 0(2^7) + 1(2^6) + 1(2^5) + 0(2^4) + 1(2^3) + 1(2^2) + 1(2^1) + 0(2^0)
	- 0(128) + 1(64) + 1(32) + 0(16) + 1(8) + 1(4) + 1(2) + 0(1)
	- 64 + 32 + 8 + 4 + 2
	- 106
- 10111111
	- 1(2^7) + 0(2^6) + 1(2^5) + 1(2^4) + 1(2^3) + 1(2^2) + 1(2^1) + 1(2^0)
	- 1(128) + 0(64) + 1(32) + 1(16) + 1(8) + 1(4) + 1(2) + 1(1)
	- 128 + 32 + 16 + 8 + 4 + 2 + 1
	- 191
- 01011010
	- 0(2^7) + 1(2^6) + 0(2^5) + 1(2^4) + 1(2^3) + 0(2^2) + 1(2^1) + 0(2^0)
	- 0(128) + 1(64) + 0(32) + 1(16) + 1(8) + 0(4) + 1(2) + 0(1)
	- 64 + 16 + 8 + 2
	- 90

Convert the following decimal numbers to binary:
- 72
	- 72/2 = 36 - remainder 0 (lsb)
	- 36/2 = 18 - 0
	- 18/2 = 9 - 0
	- 9/2 = 4.5 - 1
	- 4/2 = 2 - 0
	- 2/2 = 1 - 0
	- 1/2 = 0.5 - 1 (msb)
	- = 0001001(down arrow 2)
- 255
	- 255/2 = 127.5 - remainder 1(lsb)
	- 127/2 = 63.5 - 1
	- 63/2 - 31.5 - 1
	- 31/2 = 15.5 - 1
	- 15/2 = 7.5 - 1
	- 7/2 = 3.5 - 1
	- 3/2 = 1.5 - 1
	- 1/2 - 0.5 - 1 (msb)
	- = 11111111(down arrow 2)
- 64
	- 64/2 = 32 - remainder 0 (lsb)
	- 32/2 = 16 - 0
	- 16/2 = 8 - 0
	- 8/2 = 4 - 0
	- 4/2 = 2 - 0
	- 2/2 = 1 - 0
	- 1/2 = 0.5 - 1 (msb)
	- 0000001(down arrow 2)
- 104
	- 104/2 = 52 - remainder 0 (lsb)
	- 52/2 = 26 - 0
	- 26/2 = 13 - 0
	- 13/2 = 6.5 - 1
	- 6/2 = 3 - 0
	- 3/2 = 1.5 - 1
	- 1/2 = 0.5 - 1 (msb)
	- 0001011(down arrow 2)
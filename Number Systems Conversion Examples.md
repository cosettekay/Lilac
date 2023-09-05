Name: Cosette Tabucol

Convert the following Binary numbers to Decimal:
- 10110010
	- 1(2^7) + 0(2^6) + 1(2^5) + 1(2^4) + 0(2^3) + 0(2^2) + 1(2^1) + 0(2^0)
		- 128 + 32 + 16 + 2
		- **178**
- 01111000
	- 0(2^7) + 1(2^6) + 1(2^5) + 1(2^4) + 1(2^3) + 0(2^2) + 0(2^1) + 0(2^0)
	- 64 + 32 + 16 + 8
	- **120**
- 01101110
	- 0(2^7) + 1(2^6) + 1(2^5) + 0(2^4) + 1(2^3) + 1(2^2) + 1(2^1) + 0(2^0)
	- 64 + 32 + 8 + 4 + 2
	- **110**
- 10111111
	- 1(2^7) + 0(2^6) + 1(2^5) + 1(2^4) + 1(2^3) + 1(2^2) + 1(2^1) + 1(2^0)
	- 128 + 32 + 16 + 8 + 4 + 2 + 1
	- **191**
- 01011010
	- 0(2^7) + 1(2^6) + 0(2^5) + 1(2^4) + 1(2^3) + 0(2^2) + 1(2^1) + 0(2^0)
	- 64 + 16 + 8 + 2
	- **90**

Convert the following Decimal numbers to Binary:
- 72
	- 72/2 = 36 -> remainder = 0 (lsb)
	- 36/2 = 18 -> remainder = 0
	- 18/2 = 9 -> remainder = 0
	- 9/2 = 4.5 -> remainder = 1
	- 4/2 = 2 -> remainder = 0
	- 1/2 = 0.5 -> remainder = 1 (msb)
	- **00101000**
- 255
	- 255/2 = 127.5 -> remainder = 1 (lsb)
	- 127/2 = 63.5 -> remainder = 1
	- 63/2 = 31.5 -> remainder = 1
	- 31/2 = 15.5 -> remainder = 1
	- 15/2 = 7.5 -> remainder = 1
	- 7/2 = 3.5 -> remainder = 1
	- 3/2 = 1.5 -> remainder = 1
	- 1/2 = 0.5 -> remainder = 1 (msb)
	- **11111111**
- 64
	- 64/2 = 32 -> remainder = 0 (lsb)
	- 32/2 = 16 -> remainder = 0
	- 16/2 = 8 -> remainder = 0
	- 8/2 = 4 -> remainder = 0
	- 4/2 = 2 -> remainder = 0
	- 2/2 = 1 -> remainder = 0
	- 1/2 = 0.5 -> remainder = 1 (msb)
	- **01000000**
- 104
	- 104/2 = 52 -> remainder = 0 (lsb)
	- 52/2 = 26 -> remainder = 0
	- 26/2 = 13 -> remainder = 0
	- 13/2 = 6.5 -> remainder = 1
	- 6/2 = 3 -> remainder = 0
	- 3/2 = 1.5 -> remainder = 1
	- 1/2 = 0.5 -> remainder = 1 (msb)
	- **01101000**
- 12
	- 12/2 = 6 -> remainder = 0 (lsb)
	- 6/2 = 3 -> remainder = 0
	- 3/2 = 1.5 -> remainder = 1
	- 1/2 = 0.5 -> remainder = 1 (msb)
	- **00001100**

Convert the following decimal numbers to octal:
- 11
	- 1(8^1) + 1(8^0)
	- 8 + 1
	- **9**
- 42
	- 4(8^1) + 2(8^0)
	- 32 + 2
	- **34**
Convert the following octal numbers to decimal:
- 34
	- 34/8 = 4 -> remainder = 2 (lsb)
	- 4/16 = 0 -> remainder = 4 (msb)
	- **42**
- 77
	- 77/8 = 9 -> remainder = 5 (lsb)
	- 9/8 = 1 -> remainder = 1
	- 1/8 = 0 -> remainder = 1 (msb)
	- **115**

Convert the following decimal numbers to hex:
- 32
	- 32/16 = 2 -> remainder = 0 (lsb)
	- 2/16 = 0 -> remainder = 2 (msb)
	- **0x20**
- 249
	- 249/16  = 15 -> remainder = 9 (lsb)
	- 15/16 = 0 -> remainder = 1 (msb)
	- **0x19**

Convert the following hex numbers to decimal:
- 0xD7
	- D, 7 = 13, 7
	- 13(16^1) + 7(16^0)
	- 208 + 7
	- **215**
- 0x6A
	- 6, A = 6, 10
	- 6(16^1) + 10(16^0)
	- 96 + 10
	- **106**

Convert the following binary numbers to hex
- 10110110
	- 1011, 0110
	- B, 6
	- **0xB6**
- 01111010
	- 0111, 1010
	- 7, A
	- **0x7A**
- 10010101
	- 1001, 0101
	- 9, 5
	- **0x95**

Convert the following hex numbers to binary:
- 0xA1
	- 10, 1
	- 1010, 0001
	- **10100001**
- 0x9F
	- 9, F
	- 1001, 1111
	- **10011111**
- 0x42
	- 4, 2
	- 0100, 0010
	- **01000010**
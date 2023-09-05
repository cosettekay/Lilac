

## Section 2.1
 <u><font color = "#D2AFFF">Prove the following statement</font></u>

*If the square of an even number is divisible by 4*

	Let n be an integer and suppose that n is even.
	
	n = 2k for some integer k
	
	Squaring both sides, n^(2) = 4k^(2) for some integer k and 4k^(2) is divisible by 4
	
	therefore n^(2) is divisible by 4

 <u><font color = "#D2AFFF">Prove the following statement</font></u>

*The value A is the average of the n numbers 𝑥1, 𝑥2, … , 𝑥𝑛. Prove that at least one of 𝑥1, 𝑥2, … , 𝑥𝑛 is greater than or equal to A.*

	Proof by contradiction
	
	By definition of arithmetic mean, 
	
	A = (x1 + .... + xn) / n
	
	Since xi < A for all a <= i <= n
	
	A = (x1 + ... + xn)/n < (A + ... + A)/n
	
	= (nA)/n = A
	
	A < A is impossible 
	
	Therefore by contradiction, it must be that at least one xi is greater or equal to the arithmetic mean A

 <u><font color = "#D2AFFF">Prove or disprove the following statement</font></u>

*The sum of an integer and its cube is even*

	(n + n^(3)) = n(n+1)
	
	So if n is odd integer, then (n+1) is even
	
	n(n+1) is also even, as even numbers multiplied by any numbers is even
	
	n+n^(3) is even
	
	if n is even:
	
	n (n+1) is also even, as even numbers multiplied by a number is even
	
	n+n^(3) is even
	
	Therefore, n + n^(3) is always even for any integer n

 <u><font color = "#D2AFFF">Prove or disprove the following statement</font></u>

*For a positive integer n, n + (1/𝑛) ≥ 2*

	n + (1/n) - 2 = ((n^2) + 1 - 2n)/n = ((n-1)^2)/n >= 0
	
	so we have: n + (1/n) - 2 >= 0 or n + (1/n) >= 2

## Section 2.2

 <u><font color = "#D2AFFF">Use mathematical induction to prove that the statements are true for every positive integer 𝑛.</font></u>

*1+5 + 9 + ... + (4n-3) = n(2n-1)*

	P(n) : 1 + 5 + 9 + ... (4n-3) = 2n^(2) - n
	
	By mathematical induction: 
	
	P(1) = 1 = 2 * 1^(2) - 1
	          1 = 2 -1
	          1 = 1
	
	P(1) is true therefore P(k) is true
	P(k) is true : 1 + 5 + 9 + ...  (4k - 3) = 2k^(2) - k is true
	
	Introduction Hypothesis: prove P(k+1) is true
	
	n = k + 1 : 1 + 5 + 9 + ... (4k-3)  + ( 4(k+1) - 3) = 2(k+1)^(2) - (k+1)
	
	Replace 1 + 5 + 9 + ... (4k - 3) by 2k^(2) - k
	
	1 + 5 + 9 + ... (4k - 3) + (4(k+1) - 3) = 2k^(2) - k + (4(k+1) -3)
	
	= 2k^(2) - k + (4k + 4 -3)
	= 2k^(2) - k + 4k + 1
	= 2k^(2) + 4k + 1 - k
	= 2k^(2) + 4k + 1 - k (+ 1 - 1)
	= 2k^(2) + 4k + 2 - (k+1)
	= 2(k^(2) + 2k + 1) - (k+1)
	= 2(k+1) - (k+1)

	Proved that P(1) is true, assumed that P(k) is true and proved that P(k+1) is true
	
	Therefore 1 + 5 + 9 + ... (4n-3) = (2n)^(2) - n is true for all positive integer n

 <u><font color = "#D2AFFF">Use mathematical induction to prove that the statements are true for every positive integer 𝑛.</font></u>

*1 * 3 + 2 * 4 + 3 * 5 + ... + n(n+2) = [n(n+1)(2n+7)]/6*

	As n is positive integer: = {1, 2, ...}
	S(1) is at n = 1
	
	LHS = 1 * 3
	RHS = (1 * (1+1)(2 * 2 + 7))/6 = 3
	
	S(1) on RHS is also 3, so LHS = RHS at n = 1
	
	If S(k) is true, then S(k+1) is true:
	
	S(k) = 1 * 3 + 2 * 4 + 3 * 5 + ... + k(k+2) = (k(k+1)(2k+1))/6
	      = 1 * 3 + 2 * 4 + 3 * 5 + ... + k(k+2) + (k+1) * (k + 1 + 2)
	      = ((k+1)(k+1+1)(2(k+1)+1))/6
	      = ((k+1)(k+2)(2k+9))/6
	
	As nth term = n(n+2) so 
		(k+1)th term = (k+1)(k+1+2)
		= (k+1)(k+3)
	
	1 * 3 + 2 * 4 + 3 * 5 + ... + k(k+2) + (k+1)(k+3) = (k(k+1)(2k+7))/6 + (k+1)(k+3)
	
	RHS = (k(k+1)(2k+9))/6 + (k+1)(k+3)
	       = ((k)(k+1)(2k+9)+6(k+1)(k+3))/6
	       = ((k+1)(k(2k+9) + 6(k+3)))/6
	       = ((k+1)(2k^(2) + 7k + 6k + 18))/6
	       = ((k+1)(2k^(2)+13k+ 18))/6
	       = ((k+1)(2k^(2) + 9k + 4k + 18))/6
	       = ((k+1)(2k+9)(k+9))/6
	       =RHS of S(k+1)
    
 <u><font color = "#D2AFFF">Prove that any amount of postage greater than or equal to 64 cents can be built using only 5-cent and 17-cent stamps.</font></u>

	P(n): Assume for any n >= 64 there exists numbers 𝑥x and 𝑦y such that n = 17x + 5y
	
	By induction:
	
	**Base case:**
	
	For n = 64: 2 * 17c stamps and 6 * 5c stamps
	
	Hence, P(n) is satisified for the base case.
	
	**Inductive Hypothesis**: Assume that for any k <= n, the statement P(k) is true, i.e., k = 17x +5y for k >= 64 and k <= n.
	
	**Inductive Step**: Prove that P(n+1) is true as well.
	
	**Proof:**
	
	Assume that there must exist x′ and y′ such that:
	
	17x′ + 5y′ = n + 1
	
	using the hypothesis, n = 17x + 5y
	
	17x′ + 5y′ = 17x + 5y + 1
	
	17(x′−x) + 5(y′−y) = 1
	
	(x′ − x) = a and (y′− y) = b
	
	if there are a and b such that 17a + 5b = 1, than there will exist satisfying x′ and y′.
	
	a = −2, b = 7⟹ 17 * (−2) + 5 * (7) = −34 + 35 = 1
	
	Then, as we know x and y exists by hypothesis, for n+1, use x′= x − 2 and y′ = y + 7
## Section 3.1

 <u><font color = "#D2AFFF">Write the first five values in the sequence</font></u>

*A(1) = 2 and A(n) = 1/(A(n-1)), for n >= 2*

	A(2) = 1/(A(2-1)) = 1/(A(1)) = 1/2
	A(3) = 1/(A(3-1)) = 1/(A(2)) = 2
	A(4) = 1/(A(4-1)) = 1/(A(3)) = 1/2
	A(5) = 1/(A(5-1)) = 1/(A(4)) = 2
	A(6) = 1/(A(6-1)) = 1/(A(5)) = 1/2

 <u><font color = "#D2AFFF">Give a recursive definition for the set of all odd integers</font></u>

	The first odd positive integer is 1 and then every odd integer is the previous odd integer increased by 2
	ie. n + 2, n is the previous odd integer
	a(1) = 1 and then a(n) = n + 2

 <u><font color = "#D2AFFF">Write the body of a recursive function to compute S(n) for the given sequence S</font></u>

*S: 1, 3, 9 , 27, 81, ...*

	S(1) = 1
	S(2) = 3 * S(2-1) = 3 * S(1) = 3 * 1 = 3
	S(3) = 3 * S(3-1) = 3 * S(2) = 3 * 3 = 9
	S(4) = 3 * S(4-1) = 3 * S(3) = 3 * 1 = 27
	S(5) = 3 * S(5-1) = 3 * S(4) = 3 * 1 = 81
	
	function S(n)
		if n == 1:
			return 1
		else
			return 3*S(n-1)


 <u><font color = "#D2AFFF">Informally describe a recursive algorithm to reverse the entries in a list of items.</font></u>

	 Declare "table" as a table of characters
	 Set list likevalues of this table
	 Declare "table2" an other table with the same length
	 Declare i as an integer
	 Set i = 0
	 while (i <= table.length){
		 set table2[i] = table[table.length - i];
		 }
	Endwhile
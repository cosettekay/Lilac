## Section 4.4
 <u><font color = "#D2AFFF">In how many ways can first, second, and third prize in a pie-baking contest be given to 15 contestants?</font></u>

	15 x 14 x 13 = 2730

 <u><font color = "#D2AFFF">  In how many different ways can 11 men and 8 women be seated in a row if  the men all sit together and the women all sit together?</font></u>

	11! = number of ways 11 men can be seated together
	8! = number of ways 8 women can be seated together
	2! = two ways in they all sit together (men first or women first)
	11! x 8! (x 2!) = 3.2188908e+12

 <u><font color = "#D2AFFF">  Quality control wants to test 25 microprocessor chips from the 300 manufactured each day. How many different batches of test chips are possible?</font></u>

	nCr = (n!) / ( (r!)(n-r)! )
	nCr = (300!) / (300!)(275!)
	nCr = 1.953E+36

 <u><font color = "#D2AFFF">How many distinct permutations of the characters in the world HAWAIIAN are there? How many of the permutations begin with H?</font></u>

	n = 8
	"H" = 1
	"A" = 3
	"W" = 1
	"I" = 2
	"N" = 1
	nPr = (n!) / ( (n1)!(n2)!...(nk)! )
	nPr = (8!) / ( (1!)(3!)(1!)(2!)(1!) )
	nPr = (8*7*6*5*4*3*2*1) / (1*6*1*2*1)
	nPr = 40320 / 12
	nPr = 3360
	The number of distinct permutations of the characters is 3360
	
	(7!) / ( 3! * 2!) = 420 permutations which begin with H


## Section 4.5
 <u><font color = "#D2AFFF">Expand the expression (2𝑝 − 3𝑞)^4 using the binomial theorem</font></u>

	![[Pasted image 20230428220016.png | 500]]
## Section 5.1
 <u><font color = "#D2AFFF">Identify each relation on ℕ as one-to-one, one-to-many, many-to-one, or many-to-many</font></u>

a. 𝜌 = {(1, 2), (1, 4), (1, 6), (2, 3), (4, 3)}

	many to many
c. 𝜌 = {(12, 5), (8, 4), (6, 3), (7, 12)}

	one to one

 <u><font color = "#D2AFFF">Find the reflexive, symmetric, and transitive closure of each of the following relations</font></u>

a. 𝜌 = {(1, 3), (3, 3), (3, 1), (2, 2), (2, 3), (1, 1), (1, 2)}

	reflexive closure: { (1,3), (3,3), (3,1), (2,2), (2,3), (1,1), (1,2), (2,2), (3,3) }
	symmetric closure: { (1,3), (3,3), (3,1), (2,2), (2,3), (1,1), (1,2), (2,2), (3,3), (1,3), (1,2) }
	transitive closure: { (1,3), (3,3), (3,1), (2,2), (2,3), (1,1), (1,2), (2,2), (3,3), (1,3), (1,2), (2,1), (1,1), (2,3) }

c. 𝜌 = {(1, 1), (1, 2), (2, 3), (3, 1), (1, 3)}

	reflexive closure: { (1,1), (1,2), (2,3), (3,1), (1,3), (2,2), (3,3) }
	symmetric closure: { (1,1), (1,2), (2,3), (3,1), (1,3), (2,2), (3,3), (2,1), (3,2), (1,3) }
	transitive closure:  { (1,1), (1,2), (2,3), (3,1), (1,3), (2,2), (3,3), (2,1), (3,2), (1,3), (1,1), (3,1) }

## Section 5.4
 <u><font color = "#D2AFFF">Let 𝑆 = {0, 2, 4, 6} and 𝑇 = {1, 3, 5, 7}. Determine whether each of the following sets of ordered pairs is a function with domain S and codomain T. If so, is it one-to-one? Is it onto?</font></u>

a. { (0, 2), (2, 4), (4, 6), (6, 0) }

	![[Pasted image 20230427233033.png | 400]]
	
	It's not a function

c. { (2, 3), (4, 7), (0, 1), (6, 5) }

	![[Pasted image 20230427233420.png | 400]]
	
	This is a one-one and onto function 

 <u><font color = "#D2AFFF">Let 𝑓: ℕ → ℕ be defined by 𝑓(𝑥) = 𝑥 + 1. Let 𝑔: ℕ → ℕ be defined by 𝑔(𝑥) = 3𝑥. Calculate the value of the following expressions.</font></u>

a. (𝑔 ∘ 𝑓)(5)

	g ( f(x) ) = 3(x+1) = 3x + 3 = 3(5) + 3 = 18

b. (𝑓 ∘ 𝑔)(5)

	f ( g(x) ) = 3x + 1 = 3(5) + 1 = 16 
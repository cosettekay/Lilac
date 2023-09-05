## Section 4.1
<u><font color = "#D2AFFF">Describe the following set by listing its elements:</font></u>

*{𝑥|𝑥 ∈ ℕ 𝑎𝑛𝑑 𝑥 𝑖𝑠 𝑒𝑣𝑒𝑛 𝑎𝑛𝑑 2 < 𝑥 < 11}*

	{4, 6, 8, 10}

<u><font color = "#D2AFFF">What is the cardinality of each of the following sets?</font></u>

*b. 𝑆 = {{𝑎} , {{𝑎}}}  
d. 𝑆 = {𝑎, {∅} , ∅}*

	b. |S| = 2 or the cardinality of the set S is 2
	d. |S| = 3 or the cardinality of the set S is 3

<u><font color = "#D2AFFF">Let</font></u>

*𝑅 = {1 ,3, 𝜋, 4.1, 9, 10}  
𝑇 = {1 ,3, 𝜋}  
𝑆 = {{1}, 3, 9, 10}  
𝑈 = {{1,3, 𝜋}, 1}*

<u><font color = "#D2AFFF">Which of the following statements are true? For those that are not, why not?</font></u>

	a. 𝑆 ⊆ 𝑅    -> False; the set S contains the set {1}, which is not an element of the set R, therefore S is not a subset of R 
	b. 1 ∈ 𝑅    -> True
	c. 1 ∈ 𝑆    -> False; The element 1 is not an element of the set S, but the set {1} is an element of S
	d. 1 ⊆ 𝑈    -> False; 1 is an element, not a subset of U
	e. {1} ⊆ 𝑇   -> True
	f. {1} ⊆ 𝑆  -> False; {1} is an element of S, not a subset
	g. 𝑇 ⊂ 𝑅    -> True

<u><font color = "#D2AFFF">Find the power set ℘(𝑆) for 𝑆 = {1,2,3,4}. How many elements do you expect this set to have?</font></u>

	For a set with n elements, the power set has 2^(n) elements therefore: 2^(4) = 16

<u><font color = "#D2AFFF">Let</font></u>

𝐴 = {𝑝, 𝑞, 𝑟, 𝑠}  
𝐵 = {𝑟, 𝑡, 𝑣}  
𝐶 = {𝑝, 𝑠, 𝑡, 𝑢}

<u><font color = "#D2AFFF">be subsets of S = {p, q, r, s, t, u, v, w}. Find</font></u>

	a. 𝐵 − 𝐶 = {t}
	b. (𝐴 ∪ 𝐵)′  = {u, w}
	c. 𝐴 × 𝐵  = {(p,r), (p,t), (p,v), (q,r), (q,t), (q,v), (r,r), (r,t), (r,v), (s,r), (s,t), (s,v)}
	d. (𝐴 ∪ 𝐵) ∩ 𝐶' = {q, r, v}

## Section 4.2

<u><font color = "#D2AFFF">A user’s password to access a computer system consist of 3 letters followed by 2 digits. How many different passwords are possible?</font></u>

	26(26)(26)(10)(10) = 1757600 passwords

<u><font color = "#D2AFFF">𝐴, 𝐵, 𝐶, and 𝐷 are nodes on a computer network. There are 2 paths between  𝐴 and 𝐶, 2 between 𝐵 and 𝐷, 3 between 𝐴 and 𝐵, and 4 between 𝐶 and 𝐷. Along how many routes can a message from 𝐴 to 𝐷 be sent?</font></u>

	A -> D via B = 3(2) = 6
	A -> D via C = 2(4) = 8
	6 + 8 = 14 different routes

<u><font color = "#D2AFFF">In one state, automobile license plates must have two digits (no leading zeros) followed by one letter followed by a string of two to four digits (leading zeros are allowed). How many different plates are possible?</font></u>

	2 digits: 9(10)(26)(10)(10) = 234000
	3 digits: 9(10)(26)(10)(10)(10) = 2340000
	4 digits: 9(10)(26)(10)(10)(10)(10) = 23400000
	
	234000 + 2340000 + 23400000 = 25974000 plates

<u><font color = "#D2AFFF">Draw a decision tree to find the number of binary strings of length 4 that do not have consecutive 0s</font></u>

![[Pasted image 20230408062855.png]]
## Section 4.3

<u><font color = "#D2AFFF">After serving 137 customers, a cafeteria notes at the end of the day that 56 orders of green beans were sold, 38 orders of beets were sold, and 17 customers purchased both green beans and beets. How many customers bought neither beans nor beets?</font></u>

	(56 + 38) - 17 = 77 orders
	137 - 77 = 60 customers bought neither

<u><font color = "#D2AFFF">Quality control in a faculty pulls 40 parts with paint, packaging, or electronics defects from an assembly line. Of these, 28 had a paint defect, 17 had a packaging defect, 13 had an electronics defect, 6 had both paint and packaging defects, 7 had both packaging and electronics defects, and 10 had both paint and electronics defects. Did any part have all three types of defect?</font></u>

	∩(P ∪ C ∪ E) = ∩(P) + ∩(C) + ∩(E) - ∩(P ∩ E) - ∩(C ∩ E) - ∩(P ∩ C) + ∩(P ∩ C ∩ E)
	40 = 28 + 17 + 13 - 10 - 7 - 6 + ∩(P ∩ C ∩ E)
	40 = 35 + ∩(P ∩ C ∩ E)
	∩(P ∩ C ∩ E) = 5

<u><font color = "#D2AFFF">A computerized dating service has a list of 50 men and 50 women. Names are selected at random; how many names must be chosen to guarantee one name of each gender?</font></u>

	3 names
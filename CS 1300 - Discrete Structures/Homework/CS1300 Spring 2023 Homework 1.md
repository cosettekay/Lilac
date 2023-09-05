## Section 1.1

  <u><font color = "#D2AFFF">1. Several forms of negation are given for each of the following. Which are correct?</font></u>

**The carton is sealed or the milk is sour.

	The carton is not sealed and also the milk is not sour
			-> The negation of "A or B" is "not A and not B"

**Flowers will bloom only if it rains.

	The flowers will bloom but it will not rain
			-> The negation of "A only if B" is "A and not B."

**If you build it, they will come.

	You build it, but they don't come
			-> The negation of "If A, then B" is "A and not B"

<u><font color = "#D2AFFF">2. Let A, B, C, and D be the following statements: </font></u>

**A: The villain is French.
B: The hero is American.
C: The heroine is British
D: The movie is good.

<u><font color = "#D2AFFF">Translate the following compound statements into symbolic notation. </font></u>

**Although the villain is French, the movie is good

	A → D
			-> antecedent = "the villain is French"
			-> consequent = "the movie is good"
			-> → = "if-then"
**If the movie is good, then either the hero is American or the heroine is British.

	D → (B V C)
			-> antecedent = "the movie is good"
			-> consequent = "either the hero is American or the heroine is British"
			-> V = "or"
			-> "If D, then (B or C)" or "D implies (B or C)."

<u><font color = "#D2AFFF">3. Construct truth tables for the following wffs. Note any tautologies or contradictions. </font></u> 

**A → (B → A)
![[CS1300 HW1 N3Pa.excalidraw]]

<u><font color = '#d64d4d'>Since the wff A → (B → A) is true in all cases, that means it is a tautology</font color></u>

**A Λ B <-> B' V A'
![[CS 1300 HW1 N3Pb.excalidraw||800]]
<u><font color = '#d64d4d'>Since the wff A → (B → A) is false in all cases, that means it is a contradiction</font color></u>

## Section 1.2

<u><font color = "#D2AFFF">1. Justify each step in the proof sequence of</font></u>

**A' Λ B Λ [B → (A V C)] → C

1. A' <font color = "#sky blue">(given)</font>
2. B <font color = "#sky blue">(given)</font>
3. B → (A V C) <font color = "#sky blue">(given)</font>
4. A V C <font color = "#sky blue">(2, 3; mp - modus ponens)</font>
5. (A')' V C <font color = "#sky blue">(dn - double negation )</font>
6. A' → C  <font color = "#sky blue">(5; ds - disjunctive syllogism)</font>
7. C <font color = "#sky blue">(1, 6; mp - modus ponens)</font>

<u><font color = "#D2AFFF">2. Use propositional logic to prove that the following argument is valid.</font></u>

**[ A → (B → C) ] Λ ( A V D' ) Λ B → ( D→ C )

	1. [ A → (B → C) ] Λ ( A V D' ) : (hyp)
	2. A → (B → C) : (1; simplification)
	3. A V D' : (1; simplification)
	4. B → (D → C) : (1; simplification)
	5. B : (assumption)
	6. D : (assumption)
	7. A : (assumption)
	8. B → C (2; modus ponens)
	9. C : (assumption)
	10. D → C (5, modus ponens)
	11. B V D (5; addition)
	12. B V D → C (conditional proof)
	13. C : (12; modus ponens)
 
<u><font color = "#D2AFFF">Write the argument using propositional wffs (use the statement letters J, E, C). Then using propositional logic, including the rules in the Table below, prove that the argument is valid.</font></u>

**If Jane is more popular, then she will be elected. If Jane is more popular, then Craig will resign. Therefore, if Jane is more popular, she will be elected and Craig will resign.

	J: Jane is more popular
	E: Jane will be elected
	C: Craig will resign

	1. J → E       : (hyp)
	2. J → C       : (hyp)
	3. J           : (assumption)
	4. E           : (1; modus ponens)
	5. C           : (2; modus ponens)
	6. E Λ C       : (4, 5; conjunction)
	7. J → (E Λ C) : (3, 6; conditional derivation )

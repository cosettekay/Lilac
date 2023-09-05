## Section 1.3
<u><font color = "#D2AFFF">What is the truth value of each of the following wffs in the  interpretation where the domain consists of the integers, A(x) is “x<5” and B(x) is “x<7”?</font></u>

**a. (∃𝑥)𝐴(𝑥)  
b. (∃𝑥)[𝐴(𝑥)∧𝐵(𝑥)]  
c. (∀𝑥)[𝐴(𝑥)→𝐵(𝑥)]  
d. (∀𝑥)[𝐵(𝑥)→𝐴(𝑥)]

	a) (∃𝑥)𝐴(𝑥) : true
	b) (∃𝑥)[𝐴(𝑥)∧𝐵(𝑥)]  : true
	c) (∀𝑥)[𝐴(𝑥)→𝐵(𝑥)] : true
	d) (∀𝑥)[𝐵(𝑥)→𝐴(𝑥)] : false

<u><font color = "#D2AFFF">Identify the scope of each of the quantifiers in the following wffs and indicate any free variables.</font></u>

**c. (∃𝑥)[(∀𝑦)𝑃(𝑥,𝑦)∧Q(𝑥,𝑦)]  
d. (∃𝑥)(∃𝑦)[𝐴(𝑥,𝑦)∧B(y,z)→𝐴(𝑎,𝑧)]

	c.
		The scope of the existential quantifier (∃𝑥) is over the entire wff
		The scope of the universal quantifier (∀𝑦) is only bound to P(x,y)
		There are no free variables
	d. 
		The scope of both the existential quantifiers are over the entire wff
		The free variables are a and z

<u><font color = "#D2AFFF">Using the predicate symbols shown  
and appropriate quantifies, write each English language statement as a predicate wff. (The domain is the whole world.)</font></u>

**_B(x): x is a bee  
F(x): x is a flower  
L(x,y): x loves y

a. All bees love all flowers  
c. All bees love some flowers  
e. Only bees love flowers  
g. No bee loves only flowers  
i. Some bees love only flowers  
k. Every bee hates all flowers.

	a) (∀𝑥)(∀y)[𝐵(𝑥)∧F(y)→L(x,y)]
	c) (∀𝑥)(∃y)[B(x)∧(F(y)→L(x,y))]
	e) (∀𝑥)[(∃y)(F(y)∧L(x,y)→B(x)]
	g) [(∀𝑥)[(∀y)(L(x,y)→F(y))→B(x)']
	i) (∃x)[B(x)∧(∀y)(L(x,y)→F(y))]
	k) (∀𝑥)[B(x)→(∀y)F(y)→L(x,y))]

<u><font color = "#D2AFFF">Write the negation of each of the following statements. </font></u>
**b. Every Web site has both audio and video  
d. Some Web sites have neither audio nor video

	b) 
		English: Some  Web Sites does not have both audio and video
	d)
		English: Every Web Site has either audio or video

<u><font color = "#D2AFFF">Decide whether each of the following wffs is valid or invalid. Justify your answer. </font></u>

**a. (∃𝑥)𝐴(𝑥)↔((∀𝑥)[𝐴(𝑥)]′)′ 
b. (∀𝑥)𝑃(𝑥)∨ (∃𝑥)𝑄(𝑥)→(∀𝑥)[𝑃(𝑥)∨𝑄(𝑥)]

	a) valid
		1. (∃𝑥)𝐴(𝑥)       : hyp
		2. (∀𝑥)[𝐴(𝑥)]'    : 1, dn
		3. ((∀𝑥)[𝐴(𝑥)]')' : 2, dn
	b) invalid

## Section 1.4

<u><font color = "#D2AFFF">Justify each step in the following proof sequence of:</font></u>

**(∃𝑥)[𝑃(𝑥)→𝑄(𝑥)]→[(∀𝑥)𝑃(𝑥)→(∃𝑥)𝑄(𝑥)]

	1. (∃𝑥)[𝑃(𝑥)→𝑄(𝑥)] : hyp
	2. 𝑃(𝑎)→𝑄(𝑎)          : 1, ei
	3. (∀𝑥)𝑃(𝑥)             : hyp
	4. 𝑃(𝑎)                    : 3, ui
	5. 𝑄(𝑎)                    : 2, 4 mp
	6. (∃𝑥)𝑄(𝑥)              :  5, eg

<u><font color = "#D2AFFF">Either prove that the wff is a valid argument or give an interpretation in which it is false.</font></u>

(∀𝑥)[𝐴(𝑥)→𝐵(𝑥)]→[(∃𝑥)𝐴(𝑥)→(∃𝑥)𝐵(𝑥)]

	1. (∀𝑥)[𝐴(𝑥)→𝐵(𝑥)]      : hyp
	2. (∃𝑥)𝐴(𝑥)             : assumption
	3. 𝐴(a)                 : 2, ei
	4. 𝐴(a)→𝐵(a)            : 1, ui
	5. 𝐵(a)                 : 3, 4 mp
	6. (∃𝑥)B(𝑥)             : 5, eg
	7. (∃𝑥)𝐴(𝑥)→(∃𝑥)𝐵(𝑥)]    

<u><font color = "#D2AFFF">Either prove that the wff is a valid argument or give an interpretation in which it is false.</font></u>

(∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)]∧(∀𝑦)[𝑄(𝑦)→𝑅(𝑦)]→(∃𝑥)[𝑃(𝑥)∧𝑅(𝑥)]

	1.  (∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)]∧(∀𝑦)[𝑄(𝑦)→𝑅(𝑦)] : hypothesis
	2.  (∃𝑥)[𝑃(𝑥)∧𝑅(𝑥)]→(∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)] : logical equivalence
	3.  (∃𝑥)[𝑃(𝑥)∧𝑅(𝑥)]→(∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : commutativity of conjunction
	4.  ¬(∃𝑥)[𝑃(𝑥)∧𝑅(𝑥)]∨(∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : material implication
	5.  (∀𝑥)¬[𝑃(𝑥)∧𝑅(𝑥)]∨(∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : De Morgan's law
	6.  ¬[𝑃(𝑏)∧𝑅(𝑏)]∨(∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : universal instantiation
	7.  ¬𝑃(𝑏)∨¬𝑅(𝑏)∨(∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : De Morgan's law
	8.  𝑄(𝑐)→𝑅(𝑐) : (∀𝑦)[𝑄(𝑦)→𝑅(𝑦)]: universal instantiation
	9.  (∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)] : (∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)]∧(∀𝑦)[𝑄(𝑦)→𝑅(𝑦)]: simplification
	10.  𝑃(𝑑)∧𝑄(𝑑) : (∃𝑥)[𝑃(𝑥)∧𝑄(𝑥)]: existential instantiation
	11.  𝑄(𝑑) : 𝑃(𝑑)∧𝑄(𝑑): simplification
	12.  𝑅(𝑑) : 𝑄(𝑑)→𝑅(𝑑): 8, 11 modus ponens
	13.  (∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)] : 𝑅(𝑑)∧𝑃(𝑑), existential generalization
	14.  (∃𝑥)[𝑃(𝑥)∧𝑅(𝑥)] : (∃𝑥)[𝑅(𝑥)∧𝑃(𝑥)]: 3-13 proof by contradiction
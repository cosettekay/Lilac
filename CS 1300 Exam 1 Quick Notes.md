```toc
```
## Topic 1.1: Statements, Symbolic Representations and Tautologies
>[!Definition]
>Proposition = a statement or sentence that is either true or false, but not both

- Truth Value:  T(1) or F(0)
- Statement Variables: A, B,...
- Logical Connectives: Λ, V, ', <->, →


>[! Logical Connectives]
>- Conjunction / Λ  / "And"
>- Disjunction / V / "Or"
>- Negation / ' / ¬ / "Not"
>- Implication / → / "If, then"
>- Equivalence / <-> / "If and only if"

### Conjunction Λ
- A Λ B is only true when **both** A and B are true
- A Λ B is false when either A or B is false

| A | B | A Λ B |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | F |

### Disjunction V
- A V B are true when either A or B is true
- A V B is false when both A and B are false

| A | B | A V B |
|---|---|-------|
| T | T | T |
| T | F | T |
| F | T | T |
| F | F | F |

### Negation '
- If A is a statement variable, the negation of A is "not A" or A'
- It has the opposite truth value from A
	- If A is true, then A' is false and vice versa

| A | A' | 
|---|---|
| T | F |
| F | T |

### Implication →
- A → B : "If A, then B" or "A implies B"
- B → A : "If B, then A" or "B implies A"

| A | B | A → B |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |

> [!Important]
> A → B is equivalent to A' V B

	Example:
		If-then form: If you do not do your homework, then you will fail
		Or form: Either you do your homework or you will fail

| A | B | A → B |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |

| A | A'| B | A'V B |
|---|---|---|---|
| T | F | T | T |
| T | F | F | F |
| F | T | T | T |
| F | T | F | T |

### Equivalence <->
- A <-> B =  "A, if and only if, B"
- It is true if both A and B have the same truth vales
- It is false if A and B have oppositve values

| A | B | A <-> B |
|---|---|-------|
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | T |

- A <-> B is just a short form for (A → B) Λ (B → A)

### Common English Words Associated with Logical Connectives
![[Pasted image 20230307170424.png]]

### Order of Precedence of Connectives
- Parentheses
- Negation (')
- Conjunction, Disjunction
- Implication
- Equivalence

>[!Additional]
>The total number of rows in a truth table for n statement letters is 2^(n)

### Tautology
>[!Definition]
>Tautology - a wff that is intrinsically true/a statement that is always true, regardless of the truth values of its individual components or propositions.

Examples:
- "It will rain today or it will not rain today"
- ![[Pasted image 20230307174407.png]]

### Contradiction
>[!Definition]
>Contradiction - A wff that is intrinsically false/ a statement that is always false, regardless of the truth values of its individual components or propositions.

Examples:
- "It will rain today and it will not rain today"

### Tautological Equivalences

>[!Important]
>Two statements are called logically equivalent, if and only if, they have identical truth values for each possible substitution of statements for their statement variables

![[Pasted image 20230307191557.png]]
### Common Equivalences Rules
![[Pasted image 20230307185717.png]]
![[Pasted image 20230307212815.png]]
### De Morgan's Laws
![[Pasted image 20230307190845.png]]

- P: She **hates** butter **and likes** cream
- P': She **likes** butter **or hates** cream

### Methods
- Problem: Verify if the following three statements are logically equivalent or not?
	- Method 1: Use Truth Table
	- Method 2: Use examples
	- <font color = "#D2AFFF">Method 3: Use common equivalences</font>

## Topic 1.2: Propositional Logic

### Equivalence Rules
>[!Definition]
>Equivalence Rules state that certain paris of wffs are equivalent hence one can be substituted for the other with no change to truth values

#### Set of Equivalence Rules
![[Pasted image 20230307213111.png]]

### Inference Rules
>[!Definition]
>Inference Rules state that if one or more wffs that match the first part of the rule pattern are already part of the proof sequence, we can add to the proof sequence a new wff that matches the last part of the rule pattern

#### Set of Inference Rules
![[Pasted image 20230307213204.png]]

>[!Attention]
>* Inference rules DO NOT work in both directions, unlike equivalence rules
>* Inference rules are truth-preserving
>* Can only be applied when the wffs exactly match the pattern
>

### More Inference Rules
![[Pasted image 20230307214613.png]]

#### Example
![[Pasted image 20230307215137.png]]

## Topic 1.3: Quantifiers and Predicates

## Topic 1.4: Validity and Predicate Logic

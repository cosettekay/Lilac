<u><font color = "#D2AFFF">Overview</font></u>
1. Defining Structures
2. Size of Structures
3. Declaring a Structure
4. Accessing Members

<u><font color = "#D2AFFF">What is a structure?</font></u>
- A structure is one of the five data types in programming
	- A structure represents a "named" collection of related data
	- Is used to represent information about something more complicated than a single value (numbers, character or boolean) can do

<u><font color = "#D2AFFF">Defining Structures</font></u>

![[DS&A Section 2.2.1.png.png]]
- Group length & breadth together under one name and define it as a structure
	- If in your program you need something like a rectangle, you can define a structure for it
	- A rectangle is not defined by just _one_ value but by a <u>set of values</u>

---

<u><font color = "#D2AFFF">Size of Structures</font></u>

```C++
struct Rectangle{
	int length;
	int breadth;

	//definition of a structure
}
```

- int length; --> assume it takes 2 bytes of memory
- int breadth; --> assume it takes 2 bytes of memory
	- In total, the programy takes up 4 bytes of memory
- But right now, the structure is not consuming any memory since it is just a definition

>[!note] 
>The size of a structure is the total amount of memory consumed by all its members

---

<u><font color = "#D2AFFF">Declaring a Structure</font></u>

```C++
struct Rectangle{
	int length;
	int breadth;
}
int main(){
	struct Rectangle r;
	// declaration
	
	struct Rectangle r = {10,5};
	// declaration + initialization
}
```

- write struct as a keyword
	- then give name to variable
- r will occupy 4 (8 really) bytes total
	- r will have both length and breadth assigned

![[DS&A Section 2.2.1.excalidraw | 700]]

---

<u><font color = "#D2AFFF">Accessing Members of a Structure</font></u>

```C++
struct Rectangle{
	int length;
	int breadth;
}
int main(){
	struct Rectangle r;
	struct Rectangle r = {10,5};
	
	r.length = 15;
	r.breadth = 10;
	//assigns new values
	
	printf("Area of Rectangle is %d", r.length*r.breadth);
}
```

>[!note]
>To access the variables of structure, use dot operator

- The length and breadth of r will be multiplied together
	- 15 * 10 therefore the output will be 150
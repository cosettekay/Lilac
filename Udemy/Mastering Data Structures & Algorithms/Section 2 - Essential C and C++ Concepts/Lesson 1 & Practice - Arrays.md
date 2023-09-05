<u><font color = "#D2AFFF">Arrays</font></u>
- Arrays are defined as a collection of similar data elements
	- you can group a set of integers or floats under one name as an array

<u><font color = "#D2AFFF">Declaring an Array</font></u>

```C++
int A[5];
```
- 5 integers = 5 location = 5 spaces
- Array name - A
- Indices starting from 0 and ending at 4
![[DS&A Section 2.1.1.excalidraw]]

- Each location can be accessed with the help of index

```C++
A[0] = 27;
A[1] = 10;
```

![[DS&A Section 2.1.2.excalidraw]]

---

```C++
int main(){
	int A[5];
}
```

- When this program is running, it runs inside the main memory
	- Main memory is divided into 3 sections: code section, stack and heap

![[DS&A Section 2.1.3.excalidraw]]

---

<u><font color = "#D2AFFF">Declaration & Initialization of an Array</font></u>

```C++
int main(){
	int B[5] = {2,4,6,8,10};
}
```

- int B[5] --> declaration
- = {2,4,6,8,10} --> initialization

![[DS&A Section 2.1.4.excalidraw]]

---

<u><font color = "#D2AFFF">Accessing an Array</font></u>

- One method to access and print all the elements above is by using a _For Loop_
	- For Loop is used for scanning through the list of elements in an array

```C++
int main(){
	int B[5] = {2,4,6,8,10};
	int i;
for(i=0; i<5; i++)
	printf('%d', B[i]);
}
```

1. i = 0
	1. i < 5
		1. print B[0]
			1. i++ = 1
2. i = 1
	1. i < 5
		1. print B[1]
			1. i++ = 2

---

# Practice

```C++
#include<iostream>

using namespace std;

int main(){
	int A[5];
	A[0] = 12;
	A[1] = 15;
	A[2] = 25;

	cout<<sizeof(A);
 return 0;
}
```

1. Output
	1. 20
		1. Explanation = there are 5 integers total and the size of each integer takes 4 bytes


```C++
#include<iostream>

using namespace std;

int main(){
	int A[5];
	A[0] = 12;
	A[1] = 15;
	A[2] = 25;

	cout<<sizeof(A)<<endl;
	cout<<A[1]<<endl;
	
 return 0;
}
```
1. Output
	1. 20
	2. 15


```C++
#include<iostream> //for C++
#include<stdio.h>  //for C language
using namespace std;

int main(){
	int A[5];
	A[0] = 12;
	A[1] = 15;
	A[2] = 25;

	cout<<sizeof(A)<<endl;
	cout<<A[1]<<endl; //cout for C++
	printf("%d\n", A[2]); //printf for C language
	
 return 0;
}
```
1. Output
	1. 20
	2. 15
	3. 25


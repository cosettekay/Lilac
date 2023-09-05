```toc
```
# A Basic C++ Program
```C++
// sample C++ program
// A comment that is ignored by the compiler.
// This can be used to leave a note or explanation.

#include <iostream>       //preprocessor directive
using namespace std;      //the default namespace to use

int main(){               //beginning of function named main
 cout << "Hello C++";     //output statement shown in the console
 return 0;                //sent 0 exit code to the operating system
}                         //end of block for main
```
## Preprocessor Directives
### The # include directive
The most common preprocessor directive is the `#include` directive. It tells the [preprocessor](https://www.geeksforgeeks.org/cc-preprocessors/) to insert the contents of another code file into the current program. It is written at the beginning of any C++ program. These files are mainly imported from an outside source into the current program. The process of importing such files that might be system-defined or user-defined is known as **File Inclusion**. Here are the two types of file that can be included using #include:

**Header File or Standard files:**
	This is a file which contains C++ function declarations and macro definitions to be shared between several source
**User-defined files:**
	These files are header files that are written by a user itself. This saves the user from writing a particular function multiple times in different programs. Once a user-defined file is written, it can be imported by a program by using the `#include` preprocessor.


### Example
## hE;LLO
# This is my nexr code
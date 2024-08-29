# EXP 2

## Aim:
  Employing the sizeof operator allows us to showcase the memory sizes allocated to fundamental data types in C++. This exploration enhances our understanding of how memory is allocated for various data types within the language.

## Theory:
  
The sizeof operator in C++ is utilized to ascertain the size of data types in bytes. It helps programmers understand the memory allocation requirements of different data types within the language. By using sizeof, one can retrieve the exact amount of memory allocated to variables and data structures, aiding in efficient memory management and optimization of program performance. This operator is essential for ensuring that data is stored and manipulated efficiently, especially in scenarios where memory usage needs to be closely monitored and managed.

## Apparatus:
 VS Code, Github


## Code:
```
#include <iostream>
using namespace std;
int main(){
    cout<< "Size of intergers is "<< sizeof(int)<< " bytes"<< endl;
    cout<< "Size of float is "<< sizeof(float)<< " bytes"<< endl;
    cout<< "Size of strings is "<< sizeof(string)<< " bytes"<< endl;
    cout<< "Size of character is "<< sizeof(char)<< " bytes"<< endl;
    cout<< "Size of double is "<< sizeof(double)<< " bytes"<< endl;
    cout<< "Size of long is "<< sizeof(long)<< " bytes"<< endl;
    cout<< "Size of boolean is "<< sizeof(bool)<< " bytes"<< endl;
    return 0;
}
```


## Output:


## Conclusion: 

   This program demonstrates the use of the sizeof operator to determine the size of various data types in C++. Understanding the sizes of these data types helps us make better memory management decisions and optimize our programs.

# File System

**Objective**
Understand that the binary file can store any type of data, and how to read/write on it.

**Concepts**
This concept is covered the read/write operation on a binary file.
| Concept   |      Resources      |
|----------|:-------------:|
|Introduction to Binary File Handling| [C++ Binary File](https://www.youtube.com/watch?v=fCvJ9Rsfy6c) |



**Problem**
Create a binary file that contatins an integer value and read it.

**Implementation**
Store the following array of integer value in a binary file, and then close the file stream.
```
101, 102, 103, 104, 105
```

Print the value of the binary file on the console.

**OUTPUT**
```
101
102
103
104
105
```

```cpp
#include <iostream>
#include <fstream> // import the file stream library
using namespace std;

int main() {
    
    // Create a binary file

    // Write to the binary file, and close the file stream

    // Read from the binary file, and close the file stream
    
    return 0;
}
```
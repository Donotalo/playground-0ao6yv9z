# The Problem

Let's define what problem KMP algorithm addresses. Given two strings `S` and `W`, we'd like to know all occurrences of `W` within `S`. The brute force approach is to search for `W` starting from all indices in `S`. If `S` contains n characters and `W` contains m characters, then the brute force approach will have the complexity of `O(nm)`. The KMP algorithm solves the same problem in `O(n + m)` complexity.

```C++ runnable
#include <iostream>

using namespace std;

int main() 
{
    cout << "Hello, World!";
    return 0;
}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C++ template](https://tech.io/select-repo/598)

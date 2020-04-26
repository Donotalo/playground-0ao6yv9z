# The Problem

Let's define what problem KMP algorithm addresses. Given two strings `S` and `W`, we'd like to know all occurrences of `W` within `S`. The brute force approach is to search for `W` starting from all indices in `S`. If `S` contains n characters and `W` contains m characters, then the brute force approach will have the complexity of `O(nm)`. The KMP algorithm solves the same problem in `O(n + m)` complexity.

# KMP

From Wikipedia, as of this writing:

> The algorithm was conceived by James H. Morris and independently discovered by Donald Knuth "a few weeks later" from automata theory. Morris and Vaughan Pratt published a technical report in 1970. The three also published the algorithm jointly in 1977.
> This was the first linear-time algorithm for string matching.

# Constructing An Example

Let's take a look at how this algorithm works. Say,

```
S = ABC ABCDAB ABCDABCDABDE
W = ABCDABD
```

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

Markdown cheetsheet: https://tech.io/playgrounds/408/tech-io-documentation/markdown-cheatsheet

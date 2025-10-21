# flavortext
Generates flavortext.

## How to use
Example programm for using the flavortext generator
```cpp
#include "flavortext.h"
#include <stdio.h>
#include <stdlib.h>

int main()
{
    char* x = 0;
    for (int i = 0; i < 200; i++)
    {
        x = flavortext();
        printf("%s\n", x);
        free(x);
        x = 0;
    }
    return 0;
}
```

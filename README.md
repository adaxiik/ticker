# Ticker.hpp
Small Ticker class to simulate Mbed ticker

# Usage
```cpp
#include "Ticker.hpp"

void myFunction()
{
    // Do something
}
int main()
{
    Ticker ticker;
    ticker.attach(myFunction, 1000); // time in ms
    
    while(1){}; // to keep program running
    return 0;
}
```
## Notes
- May need to be compiled with `-pthread`

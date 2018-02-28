# Blinky

Both bins were compiled with the debug profile.
Please note that this is the blinky I used :
```C++
#include "mbed.h"

DigitalOut led1(LED1);
DigitalOut led2(LED2);
DigitalOut led3(LED3);

// main() runs in its own thread in the OS
int main() {
    while (true) {
        led1 = !led1;
        if (!led1) {
            led2 = !led2;
        }
        if (!led2) {
            led3 = !led3;
        }
        wait(0.5);
    }
}
```

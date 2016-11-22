#include "mbed.h"

DigitalOut myled1(PC_15);
DigitalOut myled2(PC_14);
DigitalOut myled3(PC_13);


int main() {
    while(1) {
        myled1 = 1;
        wait(0.2);
        myled1 = 0;
        myled2 = 1;
        wait(0.2);
        myled2 = 0;
        myled3 = 1;
        wait(0.2);
        myled3 = 0;
        myled2 = 1;
        wait(0.2);
        myled2 = 0;
    }
}

My work for the *Wireless Embedded Systems* course at UCSD. This is the firmware for a BLE device that detects when it is lost to beacon BLE signal to a smartphone, shows how long it has been lost, and automatically disconnects when it is moved (not lost).

What I did in this project:
- Part 1: Implement a driver for the LED and timer using interrupts and GPIOs.
- Part 2: Implement drivers for I2C and accelerometer (XL). Reading XL signal to detect movements.
- Part 3: Integrate BLE into the project using the provided library.
- Part 4: Optimize power usage by keeping the board in sleep mode while no interrupt fires.

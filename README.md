# Embedded-Systems

This project involved programming a CC320 Circuit Board. The project requirements were to create a thermostat that has a set temperature that controls a heater, which in this case would be represented as an LED.
If the current temperature fell below the set temperature, the LED should turn on, and if it was higher, the LED would turn off. Two buttons also were to be set up to increase or decrease the set temperature by one unit if pressed.
The current temperature was to be read by a temperature sensor on the circuit board.
The current temperature, set temperature, number indicating if the heater was on or off, 1 for on, 0 for off, and the seconds that the system has been running for were all to be reported repeatedly to a terminal.
The LED and buttons were controlled by a GPIO peripheral, an interrupt was used for the buttons, an I2C peripheral was used to read the current temperature from the temperature sensor, a timer and task scheduler was used for checking statuses and reporting to the terminal, and a UART was used for linking the circuit board to the terminal.

One thing that I think I did well was setting up the task manager. One thing that I might be able to improve are the in line comments.
One tool that I might be adding to my support network is the CCS IDE, before this course I did not know much about embedded systems, but once I learned how to navigate the CCS IDE, setting up embedded code seemed less confusing.
Some skills potentially gained or improved from working on this project like utilizing CCS to establish a connection to a circuit board as well as UART and GPIO could be applied to other embedded systems projects, trying to improve coding best practices could be applied to many other projects, even with different coding languages, and improvements in time management could be applied even to non coding projects.
I made this project maintainable, readable, and adaptable, by using best practices like creating in line comments explaining what sections of the code are doing, creating clear variable names that make sense, and separating sections of code into various functions.


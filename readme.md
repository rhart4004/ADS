Advanced Digital System Design (16.4xx)
========================================

Lab 1
-------

Using a mux, decoder and dual seven segment display, display 32. When you flip a switch have it change to 85.
After that is done, without changing the circuit, make it display 23 and 58.


Lab 2
-------------------------

###Counter with External Control

**Requirements:** Design, build (the hardware) and test a ircuit with the following features:
* If the even button is pressed, the display should count 0, 2, 4, 6
* If the odd button is pressed, the display should count 1, 3, 5, 7
* If both the odd and even button is pressed, the display should "freeze" on that digit

The circuit must be build using only NAND and NOT gates and flip-flops. 

**Our Implementation:** Used 74LS74 (dual D-Flip-Flop), 74LS00 (quad 2-input NAND), and 74LS04 (six 2-input NOT)

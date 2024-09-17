An automatic dialer w a keypad, display cct and tone generator made from 2 chips.

Takes number inputed from the keypad, stores them and recalls them. 

1/

68HC705C8 
   PIC 8 bit MicroController w Programmer(PROG05)
   8 KB EPROM for program storage,
   304 bytes of RAM for data storage,
   16 bit timer system,
   I/O ports,
   On-chip oscillator,
   Watchdog timer for crash reset,
   keyboard scanning logic
   
   
2/

MC34010
    graphic processor


Initialization routine(Assembler code PDF: p1 of 10) prepares the memory.   80 bytes reserved that provide 10  locations w 8 numbers.    Back in the 90s, most phone numbers were 8 digits memorized. LOL 😆 

https://github.com/mrmcompserv/MCS/tree/main

Flow chart that helps explain the code is in PDF -  Dialer telephone cct p3 of 3.

https://github.com/mrmcompserv/MCS/tree/main

Assembler code PDF describes how the code works. 

https://github.com/mrmcompserv/MCS/tree/main


https://github.com/mrmcompserv/MCS/tree/main


Several points of light:

1. Amount of memory reserved. LOL 😆 

2. Only 7 input ports available on the 68HC705C8

3. Chip label on the schematic

4. use of binary to BCD(Binary Coded Decimal)

5. keypad location

# Assignment \#02 - Questions
1. When the Pi is running, type the command: **cat /proc/cpuinfo**
Then make a screen shot that contains the output and your first name and name to add to your report.
![Q2.jpg](Q2.jpg)

2. Answer the following:
- - What is the SoC (Hardware) ????
- - How many processors does ARM have????
- - Are these processors running in 32 or 64 bit mode????
- - How do you know????

3.	Read the document “Basics of UART communication”. Suppose an UART is configured with a data frame of 8 bits, 1 parity bit and 2 stop bits. It needs to transmit the following 10110000 where 1 is the most significant bit. Complete the following table to show how the data packet will look like (Bit 0 = first bit to be sent):


    |Bit #|Value|Comment|
    |----|-----|-------|
    |0|??|Start Bit|
    |1|??|??|
    |2|??|??|
    |3|??|??|
    |4|??|??|
    |5|??|??|
    |6|??|??|
    |7|??|??|
    |8|??|??|
    |9|??|??|
    |10|??|??|
    |11|??|??|
    |12|??|??|

4. How to handle an error in the transmission? Actually UART uses some additional lines (in addition to TX and RX) such as DTR/DSR or RTS/CTS (the lines are also connected to the pins of the GPIO). Explain in one sentence the reason for these additional lines.
????

5.	How does the ARM processor know to start in 32 bit mode or 64 bit mode? 
????

6.	When the ARM starts, the code corresponding to the instructions in boot.s is executed.  The GPU (which boots first with a proprietary code so nobody knows exactly what it does) populates the registers r0, r1 and r2 of the ARM processor. With what values?
  -	- r0: ???
  - - r1: ???
  - - r2: ???

7.	Which instruction sets the stack pointer in boot.s ?

8.	We know that the code executed by boots.s is loaded at the address 0x8000 and up. Is not there a risk that the growing stack overlaps the code? Explain. 

    ?????

9.	Why do we need to zero the BSS before executing the kernel?

    ?????

10.	Run the make utility to create a kernel.img and a kernel.elf file. You should watch the “Hello World behind the curtain” if you did not do already (or may be watch it a second time…) and use your soon-to-be-favorite tools **readelf** and **objdump** to answer the following:

    | Question | Answer | How do you know ? |
    |----------|--------|-------------------|
    |At what address does the program start? | ??? | ??? |
    |What are the start and end address of the BSS section? | ??? | ??? |
    |Indicate one variable in the BSS section | ??? | ??? |
    |What are the start and end address of the rodata section?  | ??? | ??? | 
    |Indicate one variable in the rodata section | ??? | ??? |
    |What are the start and end address of the data section? | ??? | ??? |
    |Indicate one variable in the data section | ??? | ??? |
    |In which file are the symbols __data_start, _data_end defined? | ??? | ??? |

   
---

11.	Please rate this homework:
    - How many hours did you spend in total?
    - How much did you learn (0 = nothing to 3 = a lot)? 
    - How much did you like it (0 = not at all to 3 = a lot)? 
    - Any suggestion?

        
# data_generator_printer_in_c

Data Generation and Printer Module
This project simulates generating random data and managing it in a buffer. The program creates random bytes, stores them, and prints the data every 10 seconds if enough bytes are available.

 1.  What This Program Does
Generates random bytes (between 0 to 5 bytes every second).
Stores these bytes in a dynamic buffer (memory space that grows as more data comes in).
Every 10 seconds, it checks:
If there are 50 or more bytes, it prints the latest 50 bytes and removes them from the buffer.
If there are less than 50 bytes, it skips printing.
The program runs for 60 seconds and then stops automatically.


 2.   Assumptions Made
The program generates random data between 0 and 5 bytes per second.
It’s designed to run work well on online compilers.
Memory is managed dynamically adjusts as data is added or removed.
Added Debug messages to ensure that its being working properly (Commented)
The code checks for 10 Sec that the data is being reached to 50 Bytes if yes then it prints and delete the data if not it skipps printing and wait till it reaches to 50 bytes or more

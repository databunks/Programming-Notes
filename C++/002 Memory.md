- in C++ stuff is actually stored in ==virtual memory== which tricks your program into thinking its on your OS and has full access to all of the resources when in reality it just has its own finite space of memory

- Each program is abstracted into a process and each process has access to the memory range `0 -> 2^n (-1)` where n is dictated if you have a 64 bit or 32 bit machine

![[Pasted image 20220810013159.png]]

- When a program executes it goes through the compiler and then a part of the cpu called the memory management unit (mmu) which basically maps the values/addresses we have in the virtual memory to the real memory inside the RAM

![[Pasted image 20220811040900.png]]
- As we can see from this slide the MMU just translates the programs memory addresses and values onto the RAM

- The structure of your program is defined by your OS

Stack / heap diagram
![[Pasted image 20220811041620.png]]



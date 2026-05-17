# custom-8bit-RISC-cpu
To test this cpu first download the DIGITAL LOGIC SIM by sebastian lague. Extract the zip file and paste it in this address. 
" C:\Users\USERNAME\AppData\LocalLow\SebastianLague\Digital Logic Sim\V1\Projects ".
Instruction for this cpu are :-
0 add.
1 sub.
2 and.
3 or.  
4 nor.
5 xor.
6 increment reg A. 
7 decrement reg A.
8 write from port. 
9 jump if carry. 
10 load in memory.  
11 display output.     
12 jump if zero. 
13 jump if negative. 
14 jump.


Intruction set is divide in this form :- first four bits are opcode and 2 bit for REGISTER A and 2 bit for REGISTER B.
[ OPCODE | REG A | REG B ]
  4 bits   2 bits  2 bits .
like '00010101' will be sub , R1 to R2 , 
There 4 registers each for REGISTER A and REGISTER B.
LOCATION of these in memeory ar REGISTER A from (8-11) and for REGISTER B from (12-15) and to assces these for operation there addresses are (0-3) for each.
TO DISPLAY any memory can be accessed from (0-7)

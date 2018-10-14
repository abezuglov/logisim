# Simple As Possible computer (SAP-1)

The repository contains a couple implementations of Simple As Possible computer done in Logisim. 

* AB_SAP1.circ -- contains SAP-1 with a combinatory controller
* AB\_SAP\_ROM.circ -- SAP-1 with a ROM based controller

## System of commands

| LDA <addr> | 0000 <addr>
| ADD <addr> | 0001 <addr>
| SUB <addr> | 0010 <addr>
| MUL <addr> | 0011 <addr>
| DIV <addr> | 0100 <addr>
| STA <addr> | 0101 <addr>
| OUT | 1110 <addr>
| STOP | 1111 <addr>

## Test programs
### Multiply 2*3
The program will multiply two numbers, save the result in memory and output it. The operands located at addresses 5 and 6, the output is at address 7:

05 36 57 e0 f0 02 03 00

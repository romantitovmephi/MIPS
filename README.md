# MIPS PROCESSOR

In this section, we will assume that both instruction memory and data memory are external to the processor and connected to it via address and data buses. This is a more realistic scenario because most processors use external memory. This approach also demonstrates how the processor can interact with the outside world.
The processor consists of a data path and a control unit. The control device, in turn, consists of the main decoder and the ALU decoder.

Supported Instructions:

`add sub and or xor beq bne sll srl`

`addi andi ori xori lw sw`

`j jr jal`


## Structure


`./blocks` - the folder stores the instruction memory, data memory, and register file files. They can be used to examine the contents of the corresponding memory after the program has been executed.

`./src` - systemverilog-modules of the processor are stored in the folder

`./test` - the test module for the processor is stored in the folder



![Scheme1](/src/MIPS.png?raw=true)

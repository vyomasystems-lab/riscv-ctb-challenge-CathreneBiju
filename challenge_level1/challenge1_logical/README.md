logical errors

2 statements had error: illegal operands

1. and s7,ra,z4
   here, z4 for is not a register in rv32i isa. So, a valid register s4 was used.
   corrected instruction is and s7,ra,s4

2. andi s5,t1,s0
   here, andi is an immediate type instruction. So, one operand should be an immediate value. Here the operands given are both registers. 
   So an R type instruction is to be used. So, use and instruction.
   corrected instruction is and s5,t1,s0

# riscv_ctb_challenges

level1 challenges : logical, loop and illegal. The bugs in these test were captured and corrected.
In logical,illegal operands where used. The invalid register z4 is replaced by a valid register s4. I type instruction used for 2 register operands is replaced by R type instruction.
In loop, the test entered an infinite loop while summing. The comparing condition was modified to bnz to avoid infinite loop.
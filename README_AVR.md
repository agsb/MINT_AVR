# What is MINT ?

MINT is a tiny, stack based language based on Forth. On the Z80 it can be implemented in fewer than 2048 bytes of machine code - and it is relatively quick compared to other interpreted languages.

It uses reverse Polish notation (RPN) so you have to put the operands before the operator. It's just like the old HP calculators from 50 years ago.

If you want to add two numbers you just type:

123 456 + .

When you hit return the result will be displayed thus

00579

    This is the cursor / prompt that confirms that the code has been executed and control has been passed back to the User.

# MINT on AVRs

  That is a port of MINT_Z80 for microprocessors AVR, basics for Atmega8.
  
  This version 0.1, is just a translation of registers and instructions, as is, without any optimization.
  
  

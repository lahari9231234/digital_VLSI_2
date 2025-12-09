A barrel shifter is a combinational circuit that shifts data in one step, without using multiple clock cycles.

 Shifts any number of bits in ONE operation
 No clock needed (pure combinational logic)
 Used in ALU, processors (ARM), DSP, multipliers, etc.

 For an N-bit barrel shifter, the shift amount usually needs log₂(N) stages.

Example: for a 8-bit barrel shifter
log₂(8) = 3
Stages for shifts: 1-bit, 2-bit, 4-bit

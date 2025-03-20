# N_bit_fulladder_using_mux
To design an N-bit binary adder using multiplexers (MUX) instead of conventional logic gates. The design will:

Use multiplexers to implement the full adder logic.
Support an N-bit binary addition with carry propagation.
Be scalable for different bit sizes.

Approch:-
Full Adder Using Multiplexers:

1)A full adder has three inputs: A, B, and Cin (carry-in).
It produces two outputs: Sum and Cout (carry-out).
The Sum and Carry logic can be implemented using a 4:1 MUX.
N-bit Adder:

2)Connect multiple MUX-based full adders in a ripple carry manner.
The least significant bit (LSB) gets an external carry-in (Cin).
The most significant bit (MSB) produces the final carry-out (Cout).

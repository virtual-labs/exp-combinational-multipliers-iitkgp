### Objective of 4 bit carry lookahead adder:

To show that it is possible to construct a 4x4 combinational multiplier from an array of AND gates, half-adders and full-adders.

1. understanding behaviour of combinational multiplier from module designed by the student as part of the experiment

2. understanding the scheme implemented for the multiplication which is as follows (along with the logic diagram bellow):
    - it can be designed by unrolling the multiplier loop
    - instead of handling the carry out of partial product summation bit,the carry out can be sent to the next bit of the next step
    - this scheme of handling the carry is called carry save addition

3. The multiplier will multiply two 4 bit numbers
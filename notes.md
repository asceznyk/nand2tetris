# NAND2Tetris notes
All the notes and important points.


## Module 1
1. We can compose a desired logic gate by ORing all the conditions for all the 1s in its truth table.
2. Any boolean function can be constructed with AND and NOT. The NAND gate is a combination of the former two so it can construct any function.
3. Gate implementation is described by any HDL in the following way `GATE(a=.., b=.., out=..)`. This the `GATE` itself is the boolean function.
4. Use the NAND2Tetris hardware simulator.
5. For each chip (gate), the system architect creates a chip API, a test script and a compare file.


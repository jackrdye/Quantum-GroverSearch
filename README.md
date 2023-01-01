# Quantum-GroverSearch
Implementation of Grover's search algorithm to accelerate unsorted search.

Question 1 (25 Points): Qiskit implementation of multi-target
Grover (O3)
Implementation of Grover’s algorithm with Qiskit. You can download the codes of oracles and QRAM
for the following questions here. The initial state of your circuit should always be |0i
⊗n, i.e., please don’t
use the method “initialize” in Qiskit. Please write a short report containing your source codes, results
and a brief description on how your programs work. For submission, just attach your report (in .pdf
format) to your solutions to the other questions of Assignment 3. (Put everything in a single PDF.)
a) (10 Points) Search for the target item with the given oracle 1. The input data ranges from 0 to
7, and there is only one target.
b) (5 Points) Search for all target items with the given oracle 2. Again, the input data ranges from
0 to 7, but there are two targets.
c) (10 Points) Find all indices of 5 in the list [5, 2, 4, 5, 3, 7, 6, 1] using the given QRAM and oracle c.
The index begins with 0 from the left of the list, e.g., the index of the first 5 is 0, and the index of 2 is 1.
[Hint: you may want to restore the state of data register back to |0is after calling the oracle. Your search
circuit (the 2
nd reflection) could be applied to the address register, not the data.]

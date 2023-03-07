# QOSF_Mentoring_Cohort_7

After studying the research paper at https://ieeexplore.ieee.org/document/4433341 & especially https://arxiv.org/pdf/2005.08950.pdf, I was inspired to adopt their approach. However, I eventually came up with a novel concept that I believed was unique to my work.

Task 1 -> To Find the largest number

You have two integers, either positive or negative, and the challenge is to generate a quantum algorithm that returns which is the larger number. Consider an appropriate number of qubits and explain why your proposal is valid for all kinds of numbers in case 


def find_the_largest_number (int:number_1, int ,number_2):
     “””
 number_1 : integer value that is the first parameter to the function,
number_2 : integer value that is the second parameter to the function.
Return the largest number between number_1 and number_2
     “””

     # use a framework that works with quantum circuits, qiskit, cirq, pennylane, etc. 

      # consider print your quantum circuit,


Example:

A = find_the_largest_number(5,-6)
print(A)

“5”

References:

[1] Deutsch, David, and Richard Jozsa. "Rapid solution of problems by quantum computation." Proceedings of the Royal Society of London. Series A: Mathematical and Physical Sciences 439.1907 (1992): 553-558.

[2] Bernstein, Ethan, and Umesh Vazirani. "Quantum complexity theory." SIAM Journal on computing 26.5 (1997): 1411-1473.

[3] Grover, Lov K. , "A fast quantum mechanical algorithm for database search", Proceedings of the 28th Annual ACM Symposium on the Theory of Computing (1996), arXiv:quant-ph/9605043

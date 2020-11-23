# Trace distance as an informative measure of quantum circuit Overhead at constant number of Qubits

It is known that quantum circuit overhead is proportional to the number of gates times the number of quibits, and it is usually used to compare the recources usage of different circuits. Here, I am inrtroducing an informative measure (return a number) for circuits with same number of quibits, that does not only convey the number of gates but also how much it is effective in the circuit. for example, circuit composed of 6 identities is not the same as a circuit contains 6 pauli gates.

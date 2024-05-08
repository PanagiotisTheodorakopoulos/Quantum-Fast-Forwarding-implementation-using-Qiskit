# Quantum Fast-Forwarding implementation in Qiskit
The implementation took place according to this paper: https://arxiv.org/abs/1804.02321 
The algorithm is adapted in order to manipulate qubits, and is capable of
simulating a classical walk given a reversible Markov Chain of arbitrary size, using arbitrary number of steps. Due to the fact that the implementation of custom controlled operations in Qiskit is not optimized, there must be a good balance between the number of steps and the size of the Markov Chain.

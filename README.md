# VQE-Harmonic-Oscillator
This is a simple proof of concept of using Qiskit's VQE and Wolfram Mathematica to find the ground eigenvalue of a Quantum Harmoinc Oscillator. I have done runs using the state_vector simulator with simulated noise and on a real device.
# Steps
1. Load the Mathematica notebook H_QHO to create the Hamiltonian.
2. Load the Mathematica notebook Pauli_decomp to decompose the Hamiltonian to a Pauli tensor product.
3. Load the output file paulis_QHO into Qiskit via the jupyter notebook VQE_QHO.

Files are located in the proper folders with an example Hamiltonian and its decomposition.

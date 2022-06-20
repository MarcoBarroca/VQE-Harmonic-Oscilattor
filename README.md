# VQE-Harmonic-Oscillator
This is a simple proof of concept of using Qiskit's VQE to find the ground eigenvalue of a Quantum Harmoinc Oscillator and small cubic and quartic  perturbations of an Harmonic Oscillator. I have done runs using the Aer simulator with and without simulated noise and on a real device (IBMQ_Manila).

Note that we utilize a discrete version of the Hamiltonian, which means eigenvalues won't agree for the entire spectrum. Fortunately they do agree at the ground state.

I also included a powerpount presentation and handouts for this project.

# **DEPRECATED** Steps (Old files in Archive folder)
The previous method required the use of Wolfram Mathematica to crete and decompose the HAmiltionian into Pauli matrix sums.

1. Load the Mathematica notebook H_QHO to create the Hamiltonian.
2. Load the Mathematica notebook Pauli_decomp to decompose the Hamiltonian to a Pauli tensor product.
3. Load the output file paulis_QHO into Qiskit via the jupyter notebook VQE_QHO.

Files are located in the proper folders inside Archive with an example Hamiltonian and its decomposition.

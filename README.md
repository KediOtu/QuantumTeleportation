# Quantum Teleportation

Quantum teleportation is a technique for transferring quantum information from a sender at one location to a receiver some distance away. I wanted to share a simple example for it with quantum computing.
I have uploaded Jupyter Notebook file and also a Python file. You can see the circuit and the histogram on Jupyter Notebook.

## Description

We have a quantum circuit and 3 qubits on it; q0, q1 and q2. If you are familiar with the basic principles of quantum physics such as superposition, until measuring we don't know the state of a qubit. Whatever the state of q0 will come out, we want to teleport its state to q2. This is simply quantum teleportation. To understand that if our circuit works well or not, I added a 'not' gate to q0 at the very begining. So we expect as a result that q2 is gonna be 1 in all the states that we will gonna observe.

## For More Information about Quantum Teleportation [click_here](https://qiskit.org/textbook/ch-algorithms/teleportation.html)

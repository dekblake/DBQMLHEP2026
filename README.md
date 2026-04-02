# QMLHEP

Task I: Quantum Computing Part 
1) implement a simple quantum operation with Cirq or Pennylane
a) With 5 qubits 
b) Apply Hadamard operation on every qubit 
c) Apply CNOT operation on (0, 1), (1,2), (2,3), (3,4) 
d) SWAP (0, 4) 
e) Rotate X with pi/2 on any qubit 
f) Plot the circuit 
2) Implement a second circuit with a framework of your choice:
Apply a Hadmard gate to the first qubit
rotate the second qubit by pi/3 around X
Apply Hadamard gate to the third and fourth qubit
Perform a swap test between the states of the first and second qubit |q1 q2> and the third and fourth qubit |q3 q4>

Task XI: 
In this task, you should implement a simple embedding task with few Linear Layers and Parameterized Quantum Circuit(PQC). We recommend using 2-3 Layers of Linear, 4-5 qubits.
Generate Normally Distributed Data: Sample input data from a normal distribution.
Designing a Neural Network (MLP): Use a neural network to estimate PQC parameters from normally distributed data.
Quantum State Preparation: Generate a quantum state using the estimated parameters.
Training: use MSE Loss

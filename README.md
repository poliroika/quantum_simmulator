# Quantum_simmulator
Quantum simulator on Python
Quantum simulator on python, presented in two types. Implementation of some quantum algorithms on each of them. Since this is a personal project, for your own convenience, each of them is registered independently without calling functions from other programs
# Branches:

1. On tensor transformations (One of the most common types of simulators, as it can be accelerated using TPU or using special packages. The main idea is to consider changes in the state vector of a qubit as a vector product per step of a quantum circuit, where the step is the tensor product of its gates [if there is no gate on one of its branches, it is considered as an identical transformation I])
2. Through the sum of binary coefficients(A faster way than the first one, if you do not use some tensor accelerations. The main idea is the expression of each amplitude of the qubit state vector in terms of the sum of the products of the initial vector on the impacting gate. Examples of formulas for one and two-qubit operation:)
![image](https://user-images.githubusercontent.com/91738038/229704156-f47e0dad-f5dd-4fee-b765-1e085f318e66.png)

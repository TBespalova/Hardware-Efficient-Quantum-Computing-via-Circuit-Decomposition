# Hardware-Efficient-Quantum-Computing-via-Circuit-Decomposition

Quantum computing is a promising technology for various applications like quantum optimization, quantum machine learning, and quantum chemistry. However, with the limited number of qubits, the limited depth of circuit, and high error rate in the two-qubit gate, near-term quantum circuits can be challenging to maintain the resultant quantum state. Such limitations severely hinders the practical applications and commercialization of quantum technology. Therefore, it's ideal to reduce the number of qubits requirement for quantum algorithms to run on the near term quantum device. In this project, we apply the quantum circuit decomposition in IBM Q Experience to demonstrate the idea of reducing the qubit number requirement for realizing the quantum optimization with VQE solver. With max-cut problem to solve, we successfully run the VQE solver on a 3 qubits IBM chip that, in essence, requires 4 qubits. And we further run a 6 qubits solver on a 5 qubit simulator. Our circuit decomposition method is general, not bounded by the algorithms to run or number of qubits. In particular, when applied to the near-term quantum device, it may empower the quantum technology.

## How to run the code
open Circuit Decomposition for Hardware-Efficient VQE-2020-02-02.ipynb and run the code

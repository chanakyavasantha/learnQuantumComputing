# LEARN QUANTUM COMPUTING:
## Syllabus

- **Representing Computation with Basic Linear Algebra**
- *Qubits, Superposition, and Quantum Logic Gates*
- The Simplest Problem Where a Quantum Computer Beats a Classical Computer
- **Quantum Entanglement and Teleportation**

### Representing Computation with Basic Linear Algebra:
![Screenshot from 2023-07-06 17-42-25](https://github.com/chanakyavasantha/learnQuantumComputing/assets/93817654/fc43a298-ec11-4529-889c-7955781a26ca)



### Operations on one classical bit
![Screenshot from 2023-07-06 17-43-24](https://github.com/chanakyavasantha/learnQuantumComputing/assets/93817654/8846bc70-f7ca-4521-bc7b-f0584bb73041)
**Exercise:** Try to find Respective Matrices for constan-0 and constant-1 operations  

### Reversible Computing in Quantum Computing

Reversible computing is a fundamental concept in quantum computing that distinguishes it from classical computing. Unlike classical computing, which is based on irreversible operations, quantum computing operates with reversible operations at its core. Reversible computing plays a crucial role in ensuring the conservation of information and maintaining coherence in quantum systems.

### Why Reversible Computing?

In classical computing, irreversible operations, such as the erasure of information, lead to information loss and generate heat, contributing to a loss of energy. However, in quantum computing, the principle of reversibility is adhered to, allowing for information conservation and avoiding the generation of unnecessary heat.

### Reversible Quantum Gates

In quantum computing, reversible quantum gates are used to manipulate quantum states without losing any information. These gates, such as the Hadamard gate, Pauli-X gate, and Controlled-NOT gate, can be applied to qubits and perform reversible transformations on quantum states.

### Quantum Circuits and Reversible Computation

Quantum circuits in quantum computing are designed to be reversible, ensuring that the transformation of quantum states can be traced back to the initial state. By constructing circuits composed of reversible gates, quantum algorithms can be implemented efficiently, taking advantage of the inherent reversibility of quantum operations.

### Advantages of Reversible Computing in Quantum Computing

Reversible computing offers several advantages in the context of quantum computing:

- **Conservation of Information:** Reversible operations prevent information loss and enable the recovery of the initial state from the final state of a quantum computation.

- **Reduced Energy Consumption:** By avoiding irreversible operations, reversible computing in quantum systems helps reduce energy dissipation, making quantum computations more efficient.

- **Error Correction and Fault Tolerance:** Reversibility is crucial for error correction techniques, as it allows for the correction of errors without compromising the integrity of the computation.
### infact all quantum operators are their own inverses:
![Screenshot from 2023-07-06 18-06-50](https://github.com/chanakyavasantha/learnQuantumComputing/assets/93817654/36a1c996-b9c3-4b3b-be8f-536697373290)

### Tensor Porduct of vectors & Representation of multiple qbits:
![Screenshot from 2023-07-06 19-43-15](https://github.com/chanakyavasantha/learnQuantumComputing/assets/93817654/ba715d1c-8be3-422a-903b-f8ea0147a82f)
- in the above example tensor product of two tensors is performed : [ x0, y0 ] ⊗ [ x1, y1 ]
- representing multiple cbits as |01> means |0> ⊗ |1>
- this tensored represntation is called the product state
- a product state can be factored back into the individual state representation
- The product state of n bits is a vector of size $2^n$

### Operations on multiple Cbits:
### **CNOT GATE**:
- C-Not gate operates on pair of bits one of which is `control bit` and other is `target bit`
- if the `control bit` is 1 , the target is flipped, else it stays the same.
- The most significant bit is the control bit & the least significant bit is the target bit
- The control bit is always un-changed
- Here is a demonstration of C-Not Gate:
![Screenshot from 2023-07-06 20-16-42](https://github.com/chanakyavasantha/learnQuantumComputing/assets/93817654/b510512f-b54a-4269-bce9-2a00ed6bc1f1)
- CNOT GATE Example:

### Qbits and Superposition:
- A qbit is represented by (a b) where a and b are just complex numbers and $|a|^2$ + $|b|^2$ = 1
- cbits are a special case of qbits
- Qbits examples:

### Operations on qbits:
- operations on qbits are sames as operations on matrices
- All the matrix opertions we've seen also work on qbits (bit flip, CNOT, etc.)

### **HADAMARD GATE**:
- The hadamard gate takes a 0 or 1-bit and puts it into exactly equal superposition
- **EXAMPLE**:
- 


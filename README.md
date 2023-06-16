# QuantumProject
Completed in the Honors Accelerated Calculus series at UW, taken with Ebru Bekyel. The project introduces readers to basic principles of quantum computing, and how it compares to classical computing. Takes a Linear Algebra approach to quantum, representing the state of qubits as a vector in a two-dimensional vector space.

# Introduction

Classical computing, also known as binary computing, utilizes transistors and bits to store and transmit information. A bit in classical computing has state that is either 1 (signal) or 0 (no signal). A transistor, acting like a switch, represents a bit by being on (1) or off (0). At any single point in time, a set of n transistors can only represent one state (each transistor has two possible states, so there exist 2^n possible states).  

The computing power of a classical computer grows linearly with number of transistors used, and therefore with the size of the computer. In order to speed up a process, one must increase the number of transistors running parallel to each other. 

Finally, classical gates implemented with transistors (such as the well-known NOT, AND, OR gates) are not reversible.
 
Unlike classical computing, quantum computing uses quantum bits, also known as qubits. Each qubit's state is in a superposition (or more simply, combination) of the "0" state and "1" state. This does not mean that the qubit is a "mix" of 0 and 1, or "in-between" 0 and 1. In fact, the true value of the qubit is unknown until we measure it, and there is a certain probability of it being 0 or 1. A quantum computer utilizes quantum bits rather than transistors. Thus, since each qubit represents "both 1 and 0", a set of n qubits represents a superposition of all of the 2^n possible states. So, in theory, we can use the same amount of particles as in a classical computer to store much more information. Note, however, that only one state can be extracted from our set of n qubits. 

Quantum gates applied to qubits are reversible. Therefore, we can apply some transformation to our set of qubits, and later undo it, allowing us to see past results.

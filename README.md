# CovalentChalleng_FallFestQiskit
Covalent is an open source tool for managing and parallelizing workflows that are hardware
hybrid and distributed. Quantum support vector machines are inherently embarrassingly parallel algorithms.

##### Challenge:


 1) Using Covalent + PennyLane (with Qiskit backend), construct a simple QSVM workflow that is geared towards classically simulating the quantum kernel
    entries. 

 2) Using Covalent, construct quantum SVM workflows that use Covalent to make asynchronous computations of each individual component to massively parallelize
    the quantum SVM kernel computation using an IBM-Q device

 3) Make a better randomized selection of the QPU for each individual kernel entry to further optimize the queue time in the same workflow.

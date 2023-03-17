File "NoiseModelCustom - Comparison.ipynb" contains the results of
running the Quantum Phase Estimation circuit in an ideal quantum computer,
and with injected noise models meant to emulate 4 types of quantum computers:

 - Superconducting Qubits
 - Trapped Ion Qubits
 - Quantum Dot Qubits
 - Colour Center Qubits

This file can be run by itself to show the results.


File "NoiseModelFunctionListQiskit.ipynb" contains functions that give noise models
corresponding to emulating each of the above quantum computers. Note that this
file is meant to be used as a tool to quickly call the noise models into other
python files running quantum computing code with Qiskit libraries. It doesn't do much
by itself.
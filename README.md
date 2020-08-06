# NTU Quantum Computing Summer School 2020
National Taiwan University (NTU) provides a three-day summer school on Quantum compuing. The courses start from Aug. 04 to Aus. 06 in 2020 summer. In the summer school, we cover both theory and demos based IBM Quantum Computers. In this repository, we provide the materials, including codes, lecture notes, and supplementary information for your reference.

The summer school consists of theory lectures (in the mornings) and demonstrations (in the afternoons).


# Qiskit
Qiskit (Quantum Information Software Kit) is an open source released by IBM Quantum Team based on Python, and can be used in programming quantum computing experiments and computations. We will teach the participants from the installation to conducting your first quantum program.

## Installation
- macOS
- Windows
- Linux

We recommend you using Anaconda. The simple procedures are:
1. Open Anaconda prompt, and run
```javascript
create -n IBMQ python=3 jupyter
```
This helps you create an environment that will be used to install the `qiskit` package.

2. Next, go to the new environment
```javascript
conda activate IBMQ
```
3. Now we need to install the required packages with
```javascript
pip install qiskit matplotlib
```
4. Done!

The detail is [here](https://github.com/ycldingo/IBMQ/blob/master/README.md).
After installation, open jupyter notebook by
```javascript
jupyter notebook
```


# Outline

## Day 1
Morning: lectures

Afternoon: [lectures](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day1/Intro_Day_1.pdf) & demos
- Wrapup for morning lecture
- Installation
  - Check the version by [this](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day1/check_version.ipynb), and see if you have successfully install the packages.
- Qiskit elements
  - Terra 
  - Aer
  - Ignis
  - Aqua
- [IBM Quantum Experience](https://quantum-computing.ibm.com/)
  - Account
  - Api token
- Qubits, operations, measurements
  - Quantum gates
  - Programming examples

## Day 2
Morning: lectures

Afternoon: [lectures](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day2/Real_QuantumMachine_upload.pdf) & demos
- Takeaways from previous lectures
  - From bits to qubits
  - Bloch sphere
  - Dirac notation & Quantum states
- Superconducting qubits
  - Duffing oscillators
  - Architecture
  - Coupling map and the restrictions
  - Demo: [Transpiler](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day2/transpiler.ipynb)
- Quantum errors
  - Types of error
  - Demo: [Decoherence time of qubits](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day2/coherence_time.ipynb)
  - Demo: [Noise model](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day2/noise_model.ipynb) (noisy simulator)
- Error correction
  - Repetition code
  - Surface code
  - Demo: [Repetition code](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day2/repetition_code.ipynb)


## Day 3
Morning: lectures
- [Optimization in quantum domain](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/Qiskit-optimization_short_course.pdf)
- [Variational quantum eigensolver](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/Variational_quantum_eigensolver_short_course.pdf)
- [Quantum machine learning](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/Intro_Q_Machine_Learning_summer_short_course_2020_08_06.pdf)

Afternoon: lectures & demos
- [Variational quantum eigensolver](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/Intro_Day_3.pdf)
  - VQE 1234
  - Without `VQE` package
  - [Measurement & Expectation values](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/expectation.pdf)
  - Demo: [Expectation value, optimization](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/VQE%20example.ipynb)
  - Demo: [Find eigenvalues of a given matrix](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/VQE_0806.ipynb)
- [Hybrid quantum-classical neural networks](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day3/Hybrid%20quantum-classical%20Neural%20Networks%20with%20PyTorch%20and%20Qiskit.pdf)

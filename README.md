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
1. Open Anaconda pump, and run
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
Afternoon: [lectures](https://github.com/ycldingo/QuantumComputing_2020Summer/blob/master/Day1/Intro_Day_1.pdf) & demos
- Wrapup for morning lecture
- Installation
- Qiskit elements
  - Terra 
  - Aer
  - Ignis
  - Aqua
- IBM Quantum Experience
  - account
  - api token
- Qubits, operations, measurements
  - quantum gates
  - programming

## Day 2
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

# py-quantum-project-2
# Qiskit Gate Simulator

This repository contains a Python program using Qiskit to simulate AND, OR, XOR, and NAND gates. Each gate is implemented as a separate function, and each function provides all possible combinations of inputs and outputs for the selected gate. The program allows users to choose the inputs, and it will display the counts and the corresponding quantum circuits.

## Functions

### 1. AND Gate

Function: `and_gate(input1, input2)`

Description: This function simulates the AND gate and takes two binary inputs (0 or 1)  and  using Qiskit Simulator returns the output along with the corresponding quantum circuit.

Example:

```python
output, circuit = and_gate(input1, input2)
print("AND output:", output)
print("AND quantum circuit:")
print(circuit)
```

### 2. OR Gate

Function: `or_gate(input1, input2)`

Description: This function simulates the OR gate and takes two binary inputs (0 or 1) and  using Qiskit Simulator  returns the output along with the corresponding quantum circuit.

Example:

```python
output, circuit = or_gate(input1, input2)
print("OR output:", output)
print("OR quantum circuit:")
print(circuit)
```

### 3. XOR Gate

Function: `xor_gate(input1, input2)`

Description: This function simulates the XOR gate and takes two binary inputs (0 or 1) and  using Qiskit Simulator  returns the output along with the corresponding quantum circuit.

Example:

```python
output, circuit = xor_gate(input1, input2)
print("XOR output:", output)
print("XOR quantum circuit:")
print(circuit)
```

### 4. NAND Gate

Function: `nand_gate(input1, input2)`

Description: This function simulates the NAND gate and takes two binary inputs (0 or 1) and  using Qiskit Simulator returns the output along with the corresponding quantum circuit.

Example:

```python
output, circuit = nand_gate(input1, input2)
print("NAND output:", output)
print("NAND quantum circuit:")
print(circuit)
```

## How to Use

1. Clone this repository or download the code files.

2. Import the functions in your Python code:

```python
from gates_simulator import and_gate, or_gate, xor_gate, nand_gate
```

3. Call the desired gate function with your input values:

```python
input1 = #input from the user 
input2 = #input from the user 

output_and, circuit_and = and_gate(input1, input2)
output_or, circuit_or = or_gate(input1, input2)
output_xor, circuit_xor = xor_gate(input1, input2)
output_nand, circuit_nand = nand_gate(input1, input2)

print("AND output:", output_and)
print("AND quantum circuit:")
print(circuit_and)
print("OR output:", output_or)
print("OR quantum circuit:")
print(circuit_or)
print("XOR output:", output_xor)
print("XOR quantum circuit:")
print(circuit_xor)
print("NAND output:", output_nand)
print("NAND quantum circuit:")
print(circuit_nand)
```

4. The program will display the output for the selected gate along with the corresponding quantum circuit. The quantum circuit will be represented using Qiskit's built-in functionality for circuit visualization.

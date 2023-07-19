# py-quantum-project-2
---
# Qiskit Gate Simulator

This repository contains a Python program using Qiskit to simulate AND, OR, XOR, and NAND gates. Each gate is implemented as a separate function, and each function provides all possible combinations of inputs and outputs for the selected gate. The program allows users to choose the inputs, and it will display the counts and the corresponding quantum circuits.

## Functions

### 1. AND Gate

Function: `and_gate()`

Description: This function simulates the AND gate and takes all the possible inputs (0 , 1)  and  using Qiskit Simulator returns the output for each caes along with it's own corresponding quantum circuit.

Example:

```python
output, circuit = and_gate()
print("AND Gate : " )
print(f"Inputs: {inputs} -> Output: {result[output]}")
print("AND quantum circuit:")
print(circuit)
```

### 2. OR Gate

Function: `or_gate()`

Description: This function simulates the OR gate and takes all the possible inputs (0 , 1)  and  using Qiskit Simulator returns the output for each caes along with it's own corresponding quantum circuit.
Example:

```python
output, circuit = or_gate()
print("OR Gate : " )
print(f"Inputs: {inputs} -> Output: {result[output]}")
print("OR quantum circuit:")
print(circuit)
```

### 3. XOR Gate

Function: `xor_gate()`

Description: This function simulates the XOR gate and takes all the possible inputs (0 , 1)  and  using Qiskit Simulator returns the output for each caes along with it's own corresponding quantum circuit.
Example:

```python
output, circuit = xor_gate()
print("XOR Gate : " )
print(f"Inputs: {inputs} -> Output: {result[output]}")
print("XOR quantum circuit:")
print(circuit)
```

### 4. NAND Gate

Function: `nand_gate(input1, input2)`

Description: This function simulates the NAND gate and takes all the possible inputs (0 , 1)  and  using Qiskit Simulator returns the output for each caes along with it's own corresponding quantum circuit.
Example:

```python
output, circuit = nand_gate()
print("NAND Gate : " )
print(f"Inputs: {inputs} -> Output: {result[output]}")
print("NAND quantum circuit:")
print(circuit)
```

3. Call the desired gate function with your input values:

```python


output_and, circuit_and = and_gate()
output_or, circuit_or = or_gate()
output_xor, circuit_xor = xor_gate()
output_nand, circuit_nand = nand_gate()

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

> **Note**
> The code provided in the examples is for illustration purposes only and may not be complete or fully functional. It is intended to demonstrate how to use the `and_gate`, `or_gate`, `xor_gate`, and `nand_gate` functions and their respective quantum circuits. However, the actual implementation of these functions and their  quantum circuits may require additional code and considerations.
 Please ensure that you thoroughly review and modify the code according to your specific requirements before using it in any production or critical environment. Additionally, make sure to validate and test the functionality of the code to ensure its correctness and suitability for your use case.

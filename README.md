# -Single-Layer-Perceptron-for-Logic-Gate-Simulation

## Single-Layer Perceptron for Logic Gate Simulation
This project implements a Single-Layer Perceptron in Python to perform binary classification and simulate logic gates using a step activation function. The perceptron is first tested on a simple classification problem and then extended to model basic and complex logic gates, such as AND, OR, NOT, NAND, NOR, XOR, and XNOR.


### 📌 Objectives
Implement a Single-Layer Perceptron with a step activation function.

Train and test the model on simple binary classification tasks.

Simulate basic logic gates: AND, OR, NOT.

Simulate complex logic gates: NAND, NOR, XOR, XNOR.

### 🛠️ Technologies Used
Python 3.x
NumPy
Matplotlib (optional for plotting results)

###1. Perceptron Implementation
Accepts binary inputs.

Uses a step activation function:

arduino
Copy
Edit
f(x) = 1 if x >= threshold else 0
Updates weights using the Perceptron Learning Rule.

2. Basic Logic Gates
Trained with fixed inputs and outputs.

Uses appropriate weights and thresholds:

AND: Output = 1 only if both inputs are 1

OR: Output = 1 if at least one input is 1

NOT: Single input, inverse output

3. Complex Logic Gates
NAND, NOR: Inverted versions of AND/OR

XOR, XNOR: Non-linearly separable gates (cannot be solved with a single-layer perceptron alone, but implemented here with conditions or workarounds)

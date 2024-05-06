## **Artificial Neural Network (ANN) for Logic Gates Using NumPy**

---

### Overview:
This project implements an Artificial Neural Network (ANN) from scratch using NumPy to simulate logic gates. The implemented logic gates include AND, OR, NOT NAND, XOR, NOR and XNOR gates.

### Project Structure:
- **`ANN_for_Gates.ipynb`**: Python script containing the ANN implementation.
- **README.md**: Provides an overview of the project, its structure, and instructions for running the code.
- **requirements.txt**: Lists Python dependencies required for the project.

### Dependencies:
Ensure you have Python installed on your system. You can install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Usage:
1. Clone this repository to your local machine:

```bash
git clone https://github.com/muhammadumair862/ANN-for-Logic-Gates-from-Scratch.git
```

2. Navigate to the project directory:

```bash
cd ANN-FOR-LOGIC-GATES-FROM-SCRATCH
```

3. Open and run the `ANN_for_Gates.ipynb` to train the ANN and simulate logic gates.

### Logic Gates Implemented:
- **AND Gate**: Returns true only if both inputs are true.
- **OR Gate**: Returns true if either of the inputs is true.
- **NOT Gate**: Returns the opposite of the input.
- **NAND Gate**: Returns false only if both inputs are true.
- **XOR Gate**: Returns true if inputs are different.
- **NOR Gate**: Returns true only if both inputs are false.
- **XNOR Gate**: Returns true if both inputs are the same.

### Implementation Details:
- The ANN architecture consists of an input layer, hidden layer (if applicable), and output layer.
- Activation function: Sigmoid function.
- Loss function: Mean Squared Error (MSE).
- Training algorithm: Gradient Descent.

### Results:
- The ANN is trained to simulate the behavior of logic gates based on provided input patterns.
- Performance metrics such as accuracy and loss can be evaluated to assess the model's effectiveness in simulating logic gates.

---

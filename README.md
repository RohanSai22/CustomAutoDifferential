
# Custom Auto-Differentiation Library

This project is a lightweight implementation of an automatic differentiation library using Python and NumPy. It provides basic functionalities for building computational graphs, performing backpropagation, and training simple machine learning models.

## Features

- **Custom Tensor Class:**
  - Supports basic arithmetic operations with gradient tracking.
  - Enables backpropagation to compute gradients.
  - Includes utility functions like `relu`, `exp`, `log`, `mean`, and `sum`.

- **Visualization:**
  - Generates computational graphs for tensors using NetworkX and Matplotlib.

- **Custom Layers:**
  - Implements a fully connected linear layer.

- **Loss Functions:**
  - Mean Squared Error (MSE)
  - Cross-Entropy Loss
  - L1 Loss
  - Binary Cross-Entropy Loss

- **Gradient Operations:**
  - Gradient clipping and zeroing.
  - Gradient accumulation for large batch simulations.

- **Training Example:**
  - A simple linear regression task demonstrating the usage of the library.

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/RohanSai22/CustomAutoDifferential
```

Install the required Python libraries:

```bash
pip install numpy matplotlib networkx
```

Sample Output :

![image](https://github.com/user-attachments/assets/59bbdeef-7eb4-4d0f-b18e-75018c62a51e)

Computational graph visualization will display a directed acyclic graph of operations.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## Acknowledgments

- Inspired by PyTorch's autograd module.
- Uses NetworkX for computational graph visualization.

## Try it on Google Colab

You can also try this project directly on Google Colab:

[Open the Colab Notebook](https://colab.research.google.com/drive/1FUl4ixJUDEJVMJSypOKOwq83VijQy6GN)
```

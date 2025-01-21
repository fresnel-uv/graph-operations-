
# Graph Operations Manager

This Python script allows users to perform various graph operations using **NetworkX** and visualize the results. It supports both unary and binary operations on graphs with automatic graph generation and plotting capabilities.

## Features

- **Unary Operations**: Shadow, Splitting, Total, and Middle operations on a single graph.
- **Binary Operations**: Complement, Line Graph, k-th Power, Lexicographic Product, Tensor Product, Corona Product, Strong Product, and Modular Product of two graphs.
- **Automatic Graph Generation**: Predefined graphs such as Cycle (C5), Complete Graph (K5), and Path Graph (P3) are supported.
- **Graph Visualization**: Automatically generates and displays graphs using **matplotlib**.

## Usage

1. Choose the type of operation (Unary or Binary).
2. Provide the names of the graphs involved.
3. Select the operation and, if necessary, specify the parameter `k` for operations like k-th Power.
4. The result will be computed and plotted automatically.

### Example Operations

- Unary: Shadow, Splitting, Total, Middle of graph `C5`.
- Binary: Complement of graph `C5`, Line Graph of graphs `C5` and `K5`.

## Requirements

- `networkx`
- `matplotlib`

Install them using:

```bash
pip install networkx matplotlib
```

## License

This project is licensed under the MIT License.

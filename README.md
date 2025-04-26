# Complex Visualizer and Linear Algebra (CVLA) Interactive AI Lab

<p align="center">
  <img src="assets/cvla_logo.png" alt="CVLA Logo" width="200"/>
  <br>
  <em>Revolutionizing mathematical visualization through interactive AI</em>
</p>

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/streamlit-1.32.0-FF4B4B.svg)](https://streamlit.io)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

## Overview

CVLA Interactive AI Lab is an advanced educational platform for exploring Complex Variables and Linear Algebra through interactive visualizations and AI-powered tools.

## Key Features

### Complex Mapping & Function Visualization
- Interactive domain coloring for complex functions
- Contour integration with animated paths
- Conformal mapping visualizations
- Harmonic flow prediction

### Matrixland & Vector Playground
- Matrix transformation visualization in 2D/3D
- Subspace exploration (column space, null space)
- Basis classification and analysis
- Matrix inversion animations

### Eigen Exploratorium
- Eigenvalue and eigenvector visualization
- Matrix equation solving with step-by-step guidance
- Cayley-Hamilton theorem verification
- Principal Component Analysis (PCA) explorer

### Inner Product Lab
- Interactive inner product visualizations
- Gram-Schmidt process animator
- Orthonormal basis generation
- Embedding comparison tools

## Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/google-research/cvla-interactive-lab.git

# Navigate to project directory
cd cvla-interactive-lab

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
```

### Docker Installation (Alternative)

```bash
# Build the Docker image
docker build -t cvla-interactive-lab .

# Run the container
docker run -p 8501:8501 cvla-interactive-lab
```

## Usage Guide

### Complex Mapping

The Complex Mapping basket allows you to visualize complex functions and their properties:

1. Navigate to the "Complex Mapping" basket in the sidebar
2. Choose between "Complex Visualizer" or "Complex Integration"
3. Select or input a complex function (e.g., `z**2`, `1/(z-1)`)
4. Adjust parameters using the interactive sliders
5. Observe the visualization and explore the mathematical properties

### Matrixland

The Matrixland basket provides tools for exploring linear transformations and vector spaces:

1. Navigate to the "Matrixland" basket in the sidebar
2. Select a model (Matrix Transformation, Basis Classifier, Subspace Explorer, etc.)
3. Input matrix values or use example matrices
4. Visualize transformations, subspaces, and other properties
5. Interact with the visualizations to deepen understanding

### Eigen Exploratorium

The Eigen Exploratorium basket focuses on eigenvalues, eigenvectors, and matrix properties:

1. Navigate to the "Eigen Exploratorium" basket
2. Input a square matrix or select an example
3. Observe eigenvalues, eigenvectors, and related visualizations
4. Explore matrix powers, diagonalization, and other eigen-related concepts

### Inner Product Lab

The Inner Product Lab basket explores inner products and orthogonalization:

1. Navigate to the "Inner Product Lab" basket
2. Input vectors or select examples
3. Visualize inner products, projections, and angles
4. Explore orthogonalization processes like Gram-Schmidt

## Architecture

CVLA Interactive AI Lab follows a modular architecture:

- `app.py`: Main application entry point
- `baskets/`: Module containers for each mathematical domain
- `models/`: Mathematical computation and visualization components
- `utils/`: Shared utility functions and helpers
- `assets/`: Static resources and images

## Contributing

We welcome contributions to CVLA Interactive AI Lab! Please see our [Contributing Guide](CONTRIBUTING.md) for details on how to get started.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Research Mathematical Visualization Team
- The Streamlit team for their excellent framework
- NumPy, SciPy, and Matplotlib projects for scientific computing
- Our educational partners for valuable feedback

## Contact

For questions or support:
- GitHub Issues: [Report Issues](https://github.com/google-research/cvla-interactive-lab/issues)
- Email: cvla-support@google.com

## Citation

If you use this project in your research, please cite:

```bibtex
@software{cvla_interactive_lab_2024,
  author = {Google Research},
  title = {CVLA Interactive AI Lab},
  year = {2024},
  publisher = {GitHub},
  url = {https://github.com/google-research/cvla-interactive-lab}
}
```

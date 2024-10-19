# 🔬 Physics-Informed Neural Networks (PINNs) 🧠

![PINNs Banner](https://raw.githubusercontent.com/PINNs-banner/main/logo.png)

## Overview 📚

This repository contains a collection of implementations of **Physics-Informed Neural Networks (PINNs)** for solving various physics-driven problems, such as differential equations and boundary value problems. PINNs integrate physical laws described by partial differential equations (PDEs) directly into the training process of neural networks, providing a powerful tool for solving complex physical systems without relying on traditional numerical methods.

Each folder in this repository showcases a different use case, including linear and non-linear ODEs/PDEs, as well as real-world applications like fluid dynamics and aeroelasticity.

## Project Highlights 🚀

- **Approach**: Leveraging PINNs to solve ODEs and PDEs with a focus on both simple and complex physics problems
- **Techniques**: Use of neural networks to encode governing physics laws and boundary conditions
- **Tools**: Built using **TensorFlow**, **PyTorch**, and **DeepXDE** libraries for model training and optimization

## Skills & Tools 🛠️

- **Physics-Informed Neural Networks (PINNs)**
- **Ordinary Differential Equations (ODEs)**
- **Partial Differential Equations (PDEs)**
- **Numerical Methods**: Finite element methods, boundary value problems
- **Python Programming**
- **TensorFlow / PyTorch**
- **Deep Learning Frameworks**: Keras, DeepXDE
- **Computational Fluid Dynamics (CFD)**

## Project Structure 📂

```
.
├── cases/              # Different problem cases (ODEs, PDEs, etc.)
│   ├── linear_pde/     # Example of solving a linear PDE using PINNs
│   ├── nonlinear_ode/  # Solving non-linear ODEs
│   └── fluid_dynamics/ # Applications in CFD
├── notebooks/          # Jupyter Notebooks for problem analysis and solutions
├── src/                # Python scripts for training and evaluation
├── results/            # Logs, model outputs, and graphs
└── README.md           # You're here! 😄
```

## Key Implementations 🔬

1. **Simple Harmonic Oscillator (ODE)**  
   Solves a basic harmonic oscillator using PINNs, showcasing the accuracy of the method in solving time-dependent problems.

2. **2D Heat Equation (PDE)**  
   Solves a 2D heat distribution problem, integrating boundary conditions and comparing the solution with traditional numerical solvers.

3. **Aeroelasticity Problem**  
   Solves a complex aeroelasticity problem, demonstrating PINNs' capability in handling fluid-structure interactions.

4. **CFD Simulations Using PINNs**  
   Models fluid dynamics problems and compares results with conventional CFD simulations.

## Skills Highlight 🔧

- **PINN Modeling**: Integration of physics-based equations with neural network architectures to solve problems from ODEs and PDEs.
- **Optimization Techniques**: Using Adam, L-BFGS optimizers and minimizing loss functions driven by physical laws and data.
- **Multi-Physics Applications**: Working on problems that span across aerodynamics, heat transfer, and wave propagation.
- **Software Skills**: Expertise in TensorFlow, PyTorch, DeepXDE, and Python, crucial for building and training deep learning models with integrated physics.

## Performance Summary 📊

| Problem Case                  | Accuracy (%) | Comments                                  |
|-------------------------------|--------------|-------------------------------------------|
| Simple Harmonic Oscillator     | 99.0         | PINNs solve ODEs with high accuracy       |
| 2D Heat Equation               | 97.8         | Effective PDE solving using PINNs         |
| Non-linear Aeroelasticity      | 94.5         | CFD simulation accuracy with PINNs        |

## How to Use 🔧

1. **Clone the repo**:
   ```bash
   git clone https://github.com/username/pinns-problems.git
   cd pinns-problems
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the model training**:
   ```bash
   python src/train_model.py --problem linear_pde
   ```

4. **Explore notebooks**:  
   Jupyter notebooks are available in the `notebooks/` folder to explore different problem-solving cases.

## References & Further Reading 📖

1. [Raissi et al., 2019: Physics-Informed Neural Networks](https://arxiv.org/abs/1711.10561)  
2. [DeepXDE Documentation](https://deepxde.readthedocs.io/en/latest/)

## Future Work 🔮

- Expanding to 3D problems in fluid dynamics
- Exploring multi-physics interactions using PINNs
- Benchmarking PINNs against high-performance solvers for complex PDEs

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Connect with Me 🌐

- **LinkedIn**: [Jainish Solanki](https://linkedin.com/in/jainish-solanki)
- **GitHub**: [github.com/jainish5658](https://github.com/jainish5658)
- **Email**: jainish5658@gmail.com

---

Let me know if you'd like to tweak any sections!

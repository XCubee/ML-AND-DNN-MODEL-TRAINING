# ML & DNN WORKFLOW 

Welcome to my Machine Learning & Neural Network playground — a growing repository of hands-on models, experiments, and foundational deep learning code. Every file here reflects my learning journey from the ground up, as I build production-ready, research-inspired models using **PyTorch** and **Python**.

>  This repository is not just about building models—it's about mastering the process, structuring reusable code, and evolving towards cutting-edge AI systems.

---

##  What’s Inside

###  1. **Linear Regression (from scratch in PyTorch)**
- Implemented a basic linear regression model using PyTorch tensors and modules.
- Trained using L1 loss and SGD optimizer.
- Visualized training process and predictions.
- Includes:
  - Custom training/testing loop
  - Manual tensor conversion (NumPy ↔ Torch)
  - `.forward()` usage vs direct model call
  - Model saving/loading with `torch.save()` and `torch.load()`

###  2. **Neural Network for Classification**
- Built using `nn.Sequential()` with hidden layers.
- Tried on simple datasets like `make_circles` and `make_moons` from `sklearn.datasets`.
- Purpose: to understand how deep models learn nonlinear patterns.
- Applied:
  - Activation functions (e.g., `ReLU`, `Sigmoid`)
  - Custom visualization of decision boundaries

###  3. **Device-Agnostic Model Deployment**
- All models and tensors are compatible with both **CPU and GPU** (CUDA).
- Built logic to move data and models dynamically across devices for faster training.

---

##  What I’m Learning / Practicing

- PyTorch core API (`nn.Module`, `nn.Parameter`, optimizers, loss functions)
- Deep learning workflows: model design → training → evaluation → saving
- Data handling and preprocessing
- Binary classification using synthetic data
- Plotting decision boundaries and loss curves
- Preparing for scaling up to more complex datasets and architectures

---


# PDEsolver
The following sample problem will demonstrate that deep neural network can be utilized to approximate the solutions of partial differential equations (PDEs). This is a recent area of research, known as Physics Informed Neural Networks (PINNS). With this approach, a loss function is setup to penalize the fitted function’s deviation from the desired differential operator and boundary conditions. ﻿The main insight of this approach lies in the fact that the training data consists of randomly sampled points in the function’s domain. By sampling mini-batches from different parts of the domain and processing these small batches sequentially, the neural network “learns” the function without the computational bottleneck present with grid-based methods.
Problem: Let us consider a non-linear Poisson equation: first equation
### ∇.((1+u^2 )∇u)=f in Ω
### f=xsin(y)
### u=1 on ∂Ω_D
### ∇u.n=0 on ∂Ω_N



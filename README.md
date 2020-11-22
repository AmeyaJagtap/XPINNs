# Extended Physics-Informed Neural Networks (XPINNs): A Generalized Space-Time Domain Decomposition Based Deep Learning Framework for Nonlinear Partial Differential Equations


We propose a generalized space-time domain decomposition approach for the physics-informed neural networks (PINNs) to solve nonlinear partial differential equations (PDEs) on arbitrary complex-geometry domains. The proposed framework, named eXtended PINNs (XPINNs), further pushes the boundaries of both PINNs as well as conservative PINNs (cPINNs), which is a recently proposed domain decomposition approach in the PINN framework tailored to conservation laws. Compared to PINN, the XPINN method has large representation and parallelization capacity due to the inherent property of deployment of multiple neural networks in the smaller subdomains. Unlike cPINN, XPINN can be extended to any type of PDEs. Moreover, the domain can be decomposed in any arbitrary way (in space and time), which is not possible in cPINN. Thus, XPINN offers both space and time parallelization, thereby reducing the training cost more effectively. In each subdomain, a separate neural network is employed with optimally selected hyperparameters, e.g., depth/width of the network, number and location of residual points, activation function, optimization method, etc. A deep network can be employed in a subdomain with complex solution, whereas a shallow neural network can be used in a subdomain with relatively simple and smooth solutions. We demonstrate the versatility of XPINN by solving both forward and inverse PDE problems, ranging from one-dimensional to three-dimensional problems, from time-dependent to time-independent problems, and from continuous to discontinuous problems, which clearly shows that the XPINN method is promising in many practical problems. The proposed XPINN method is the generalization of PINN and cPINN methods, both in terms of applicability as well as domain decomposition approach, which efficiently lends itself to parallelized computation.

For more information, please refer to the following: 

References: For Domain Decomposition based PINN framework

1. A.D.Jagtap, G.E.Karniadakis, Extended Physics-Informed Neural Networks (XPINNs): A Generalized Space-Time Domain Decomposition Based Deep Learning Framework for Nonlinear Partial Differential Equations, Commun. Comput. Phys., Vol.28, No.5, 2002-2041, 2020. (https://doi.org/10.4208/cicp.OA-2020-0164)

2. A.D.Jagtap, E. Kharazmi, G.E.Karniadakis, Conservative physics-informed neural networks on discrete domains for conservation laws: Applications to forward and inverse problems, Computer Methods in Applied Mechanics and Engineering, 365, 113028 (2020). (https://doi.org/10.1016/j.cma.2020.113028)

References: For adaptive activation functions:

3. A.D.Jagtap, K.Kawaguchi, G.E.Karniadakis, Locally adaptive activation functions with slope recovery for deep and physics-informed neural networks, Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences, 20200334, 2020. (http://dx.doi.org/10.1098/rspa.2020.0334).

4. A.D. Jagtap, K.Kawaguchi, G.E.Karniadakis, Adaptive activation functions accelerate convergence in deep and physics-informed neural networks, Journal of Computational Physics, 404 (2020) 109136. (https://doi.org/10.1016/j.jcp.2019.109136)

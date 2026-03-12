---
title: "Semi-Lagrangian Physics-Informed Neural Networks (SL-PINNs) for solving hyperbolic Partial Differential Equations (PDEs)"
collection: publications
category: conferences
permalink: /publication/2026-03-12-paper-SLPINNS
excerpt: 'This paper propose Semi-Lagrangian PINN (SL-PINN).'
date: 2026-03-12
#venue: 
# slidesurl: 'http://aurorapoggi.github.io/files/slides2.pdf'
paperurl: 'http://aurorapoggi.github.io/files/SL_PINNs.pdf'
citation: 'E. Monti, K. Morozovska, A. Poggi, K. Shukla. SEMI-LAGRANGIAN PHYSICS-INFORMED NEURAL NETWORKS (SL-PINNS) FOR SOLVING HYPERBOLIC PARTIAL DIFFERENTIAL EQUATIONS (PDES). AI&PDE workshop at ICLR, 2026.'
---


Solving nonlinear kinetic systems such as the Vlasov-Poisson partial differential equations (PDEs) is challenging with both classical numerical schemes and vanilla physics-informed neural networks (PINNs) due to the curse of dimensionality, training instabilities in advection-dominated regimes, and prohibitive computational costs for long-time integration. Existing PINN approaches struggle with advection-dominated regimes and require careful constraint tuning to maintain stability over extended time integration. We propose \textbf{Semi-Lagrangian PINN (SL-PINN)}, a novel framework that learns the inverse characteristic flow map $\Psi_\theta(t,x,v) \to (x_0, v_0)$ to reconstruct the distribution as $f(t,x,v) = f_0(\Psi_\theta(t,x,v))$. From a machine learning perspective, the proposed method can be interpreted as learning a transport map that evolves the initial distribution along the characteristic flow of the kinetic equation, while solving the Poisson equation in Eulerian coordinates via spectral methods. Our framework integrates three key innovations: (1) \textbf{inverse flow map parameterization}; (2) \textbf{hybrid Lagrangian-Eulerian coupling} treating transport and field equations in their natural representations; (3) \textbf{volume-preserving loss penalty} that promotes conservation of mass, momentum, and energy. 
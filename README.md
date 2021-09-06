# Heat_GNN
This is Notebook is considered as a Hello World for me to one of my topics of interest. The problem is to train a simple Graph Neural Network (GNN) to integrate
a simple PDE, typically the heat equation. The first goal is to predict r(x,t+1) based on r(y, t) where y is a first neighbour of node x (including itself of course).
In the notebook, I created a method to perform numerical integration for the heat equation with specific initial conditions. My goal is to understand the
generalization properties of the NN: How does the GNN perform if we change initial condition, the value of the diffusion coefficient, boundary conditions. This work 
is still in progress. 

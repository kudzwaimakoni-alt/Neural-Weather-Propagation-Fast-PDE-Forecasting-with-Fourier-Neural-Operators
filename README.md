Operator Learing - Fourier Neural Operator
Solutions of PDEs are operators that act as mappings between function spaces. 
They take initial conditions, boundary conditions, and source terms as inputs and yield the PDE solution as output. 
For instance, in fluid dynamics, the solution operator can compute the flow profile at a specific future time (e.g. 𝑇=1) given the initial flow and boundary conditions.


In operator learning, models are tasked with handling functions as inputs and outputs, which are stored on a computer in their discrete representations (e.g. images). 
They should have ability to process and generalize across various representations of the inputs, such as different mesh refinements.
Data-driven models that exhibit the mentioned properties are commonly known as Neural Operators.

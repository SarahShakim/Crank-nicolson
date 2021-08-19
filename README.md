# Crank-nicolson

## Using the heat-conduction/diffusion equation to determine the temperature at a particular time for a specific point in space. This will allow us to know the temperature and how it changed over time until an equilibrium is obtained. 

Parameters

kappa = The diffusivity coefficient 

x_rng = The bounds of the space range that is being considered

t_rng = The range of time that is being considered

u_init = The function handle that is giving the initial state 

u_bndry = The function handle giving the boundary conditions

nx = The number of intervals the x-range should be divided by

nt = The number of intervals the time should be divided into 

**Example: solving using the Crank-nicolson method using the call [x3b, t3b, U3b] = crank_nicolson1d( 1, [0,pi], 10, [0, 2], 20, @u3b_init, @u3b_bndry );**

![image](https://user-images.githubusercontent.com/58648072/130009700-c8d921d9-e9c0-4af5-9422-3d9bab3a5d95.png)


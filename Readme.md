## 1. Project 1:Solving 2D Poission's Equations

### 1.1 Problem
Consider the following 2D Poission's Equations:


$$-\Delta{u}=400(x^4-y^4)sin(20xy),\quad (x,y)\in \Omega=(0,1) \times (0,1)$$

$$u(x,0)=0,\quad x\in(0,1)$$

$$u(0,y)=0,\quad y\in(0,1)$$

$$u_y(x,1)=20x(x^2-1)cos(20x)-2sin(20x)$$

$$u_x(1,y)=20y(1-y^2)cos(20y)+2sin(20y)$$

### 1.2 Numerical Scheme and Results
Please refer to the PDF report in /Project 1 for details

## 2. Project 2:Solving Time-Dependent Convection-Diffusion Equation

### 2.1 Problem

$$\frac{\partial{u}}{\partial{t}}+\mathbf{v}\cdot \nabla_x{u}=\frac{1}{10}\Delta{u} \quad \mathbf{x}=(x,y)^T\in \Omega,\quad t\in R^+$$

$$u(\mathbf{x}, t)=0,\quad \mathbf{x} \in \partial{\Omega}, \quad t\in R^+$$

$$u(\mathbf{x}, 0)=sin(\pi(x^2+y^2)[(x-1)^2+y^2-9]),\quad \mathbf{x}\in\Omega$$

Where $\mathbf{v}=(1,2)^T$ and the domain $\Omega$ is the region between two circles:

$$\Omega=\\{(x,y)|x^2+y^2>1 \text{  and  }(x-1)^2+y^2<9\\}$$

### 2.2 Numerical Scheme and Results
Please refer to the PDF report in /Project 2 for details

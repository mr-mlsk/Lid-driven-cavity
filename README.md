# Lid-driven-cavity
Solving lid driven cavity problem using SIMPLE algorithm
SIMPLE(Semi-Implicit Method for Pressure-Linked Equation) algorithm implemented for driven cavity problem on collocated grid in Python. This approach solves the issue of checkerboard oscillations which was originally faced by developers. Implemention is slightly more difficult in comparison to staggered grid but the code has extensive comments which makes it easily readable. In addition to that, I have also outlined some useful resources in order to tackle the problem. It is expected that the user has experience with staggered formulation before approaching this problem.

Results(Re=100)

<p float="left">
  <img src="https://github.com/deepmorzaria/Lid-Driven-Cavity-Collocated-Grid/blob/main/results/u_contours.png" width="400" >
  <img src="https://github.com/deepmorzaria/Lid-Driven-Cavity-Collocated-Grid/blob/main/results/v_contours.png" width="400"> 
</p>

<p float="left">
  <img src="https://github.com/mr-mlsk/Lid-driven-cavity/blob/main/pressure_contours.png width="400" >
  <img src="https://github.com/deepmorzaria/Lid-Driven-Cavity-Collocated-Grid/blob/main/results/u_centerline.png" width="400"> 
</p>
  
<image src= "https://github.com/deepmorzaria/Lid-Driven-Cavity-Collocated-Grid/blob/main/results/v_centerline.png" width=400>


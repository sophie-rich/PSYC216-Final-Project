Code appendix for paper "Mental Shape Rotation about Extreme Vertices" for Fall 2025 Algorithms of the Mind final project. 

Abstract: 
How do humans go about mentally simulating rotation of an object? 
If they visualize it rotating, what point do they chose about which to rotate it? 
In this paper, we hypothesize that this visualization happens by identifying an extreme or unique vertex about which to rotate. 
Using Julia and Gen.jl, we build a solver for a task inspired by Hamrick and Griffiths' 2013 paper "Mental Rotation as Bayesian Quadrature"
which involves determining if one shape is a rotated image of the other. 
We break down this hypothesized strategy into two inferences, first inferring a true shape from a noisy reading using Independent Block Resimulation Metropolis-Hastings, 
and then identifying an extreme vertex and inferring a rotation between the local part of one shape around that vertex and the same area on the other shape 
using Gaussian Drift Metropolis Hastings. This solver did not perform significantly better than random guessing, and we discuss limitations of this implementation, 
implications for the hypothesis, and future directions that could be pursued. 


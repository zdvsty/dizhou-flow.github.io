---
title: 'Research'
layout: default
permalink: /research/
published: true
---

My research includes theoretical and numerical analysis for partial differential equations (PDEs) with real-world applications. In particular, I mainly focus on the topics of stability and bifurcation since these two topics are of practical importance in applications. The following are some projects I did:


### 1. Tumor growth model with a time delay in cell proliferation
[ <a href="{{site.baseurl}}/research1">Details</a> ]



### 2. Atherosclerosis
![alt text](https://github.com/xinyue-zhao/xinyue-zhao.github.io/blob/master/assets/research/plaque.jpg?raw=true)

We studied the bifurcation for a highly nonlinear and highly coupled <i>free boundary</i> PDE system describing the growth of arterial plaque. The model involves high density lipoprotein cholestrols (HDL), low density lipoprotein cholestrols (LDL), macrophage cells and foam cells. As shown in the upper left figure, we consider the cross section of an artery. There are plaque region and blood flow region, with the interface separating these two regions being a free boundary. Finite branches of symmetry-breaking stationary solutions were established for the model (see my publication [3]). Moreover, we showed that the first bifurcation point for the system corresponds to the mode n=1 (see my publication [5]), which would result in the solution pattern shown in the upper right figure. As some arterial plaque is often accumulated more on one side of the artery, our bifurcation result can help to understand this phenomenon.


### 3. Solving free boundary systems by using neural networks

In a series of work, we developed some novel numerical schemes based on neural networks to solve different free boundary problems and proved the convergence of the schemes theoretically. 

In my publication [4], we proposed a method based on boundary integral method and neural network discretization to solve a modified Hele-Shaw problem with surface tension. In the simulations, we first verified this approach on radially symmetric and known non-radially symmetric solutions. The following 4 figures show the shapes of symmetry-breaking solutions on n=2, n=3, n=4, and n=5 bifurcation branches. All these solutions can be fully characterized by the theoretical bifurcation analysis and are recovered by our numerical method.

![alt text](https://github.com/xinyue-zhao/xinyue-zhao.github.io/blob/master/assets/research/HeleShaw1.png?raw=true)

Moreover, we further verified the capacity of the new method by computing some non-radially symmetric solutions which are not characterized by any existing theories. In particular, we found the following fingering-like patterns.

![alt text](https://github.com/xinyue-zhao/xinyue-zhao.github.io/blob/master/assets/research/HeleShaw2.png?raw=true)

In another projection (publication [6]), we proposed two neural-network-based numerical schemes to solve the elliptic obstacle problems. In the first method, energy informed neural networks (EINNs), the cost function comes naturally from the energy minimization of the problem. As for the second method, Penalized EINNs, we took the variation form of a penalized system as the cost function. We rigorously proved the convergence of
the two schemes and derive the convergence rates with the number of neurons N . In the simulations,
we used two example problems (both 1-D and 2-D) to verify the convergence rate of the methods and the
quality of the results.

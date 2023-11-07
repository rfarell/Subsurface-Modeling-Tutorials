# Subsurface Modeling Tutorials

This repository aims to explore various aspects related to the black oil equations, commonly employed in the simulation of hydrocarbon reservoirs. The notebooks cover the topics from the derivation of these equations in continuous and discrete forms to reduced-order modeling, history matching, and decision making under uncertainty.

## Table of Contents

1. [Introduction](#introduction)
2. [Reduced Order Modeling](#reduced-order-modeling)
3. [History Matching and Inverse Problems](#history-matching-and-inverse-problems)
4. [Decision Making under Uncertainty](#decision-making-under-uncertainty)



---

### Introduction

This section provides a comprehensive introduction to the black oil equations, including their derivation in continuous and discrete forms, as well as the fundamental problems related to them.

- [Derivation of the Continuous Black Oil Equations](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_01_Derivation_of_the_Continuous_Black_Oil_Equations.ipynb)
  
- [Derivation of Single-Phase Flow Equations](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_02_Derivation_of_Single_Phase_Flow_Equations.ipynb)
  
- [Derivation of Multi-Phase Flow Equations](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_03_Derivation_of_Multi_Phase_Flow_Equations.ipynb)
  
- [Discrete Single-Phase Reservoir Simulator](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_04_Discrete_Single_Phase_Reservoir_Simulator.ipynb)
  
- [Discrete Multi-Phase Reservoir Simulator](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_05_Discrete_Multi_Phase_Reservoir_Simulator.ipynb)
  
- [Problems of Interest](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/01_Introduction/01_06_Problems_of_Interest.ipynb)

---

### Reduced Order Modeling

Reduced Order Modeling (ROM) is an approach to simplify complex mathematical models while maintaining their essential characteristics. This section overviews various techniques applied to black oil equations.

- [Overview of Reduced Order Modeling Techniques](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/02_Reduced_Order_Modeling/02_01_Overview_of_Reduced_Order_Modeling_Techniques.ipynb)

---

### History Matching and Inverse Problems

History matching is a crucial step in reservoir simulation for calibrating the model to the available production data. This section explores different techniques for tackling these inverse problems.

- [Overview of History Matching Techniques](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/03_History_Matching_and_Inverse_Problems/03_01_Overview_of_History_Matching_Techniques.ipynb)

---

### Decision Making under Uncertainty

Making informed decisions over the life of a reservoir is challenging due to various uncertainties. This section dives into methodologies to tackle these challenges effectively.

- [Decision Making in Black Oil Models](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/04_Decision_Making_under_Uncertainty/04_01_Decision_Making_in_Black_Oil_Models.ipynb)

---

### Open Porous Media Flow Simulator
Interfacing with the Open Porous Media Flow Simulator (OPM) is a key component of this repository. The following notebooks provide a brief overview of the simulator and its capabilities.

- [OPM Simulator Overview](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/05_Open_Porous_Media_Flow_Simulator/05_01_OPM_SPE_Benchmark1.ipynb)
- [SPE Benchmark 1 UFNO](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/05_Open_Porous_Media_Flow_Simulator/05_02_OPM_SPE_Benchmark1_UFNO.ipynb)


### Physics Informed Motion Codes
- [Physics Informed Motion Code](https://colab.research.google.com/github/rfarell/Subsurface-Modeling-Tutorials/blob/main/notebooks/06_appendix/Physics_Informed_Motion_Codes.ipynb)


## Code Attribution and References

This repository comprises tutorials containing code adapted or inspired by seminal works in the field. At the onset of each notebook, we cite these sources as a testament to our commitment to intellectual integrity and the open-source ethos. We also encourage users to consult the cited works for a comprehensive theoretical foundation and additional applications of the methods.


We do use the following references throughout:
> [Odeh, Aziz S. "Comparison of solutions to a three-dimensional black-oil reservoir simulation problem."](https://onepetro.org/jpt/article-pdf/33/01/13/2229415/spe-9723-pa.pdf?casa_token=JYibD9xRM5IAAAAA:qSXB0PEO_qexB97bAwXMjwWo-tUTFLxn9XIvwCwlV1nPnquj2b662fvkk4NyiobYnggOWKJC) *Journal of Petroleum Technology 33.01 (1981): 13-25*.
> [Rasmussen, Atgeirr Flø, et al. "The open porous media flow reservoir simulator."](https://www.sciencedirect.com/science/article/pii/S0898122120302182) *Computers & Mathematics with Applications 81 (2021): 159-185*.
> Chen, Z. (2007). Reservoir simulation: mathematical techniques in oil recovery. Society for Industrial and Applied Mathematics. [Link](https://epubs.siam.org/doi/pdf/10.1137/1.9780898717075.fm)

---

## Todos
- [ ] Refine the scope of the repository more clearly. What specifically is our goal wrt the black oil equations?
- [ ] Add krigin demos to the repo
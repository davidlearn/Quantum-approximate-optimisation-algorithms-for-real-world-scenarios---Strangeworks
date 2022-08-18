# Quantum-approximate-optimisation-algorithms-for-real-world-scenarios---Strangeworks
Womanium Quantum Hackathon 2022

## Challenge Introduction
Current noisy intermediate scale quantum computers (NISQ) may be well suited to solving quantum approximate optimisation algorithms (QAOA) with some promising initial proof of principle results. These can be applied to solve a wide variety of problems such as the max-cut or traveling salesman problems, which are extremely relevant to real world scenarios useful for optimizing global supply chains for example. Classically they are extremely difficult to solve for an optimal solution, with a computational cost that scales exponentially with the number of parameters. 
We find that what many of our partners really want at this stage is to know how much quantum solutions to these problems are going to cost! This is very important because time on quantum hardware is currently extremely expensive. While they of course are interested in defining and quantifying how well these methods will actually work, their real world budgeting constraints is what will most impact the viability as far as they see it. 
This project will involve creating and testing a QAOA algorithm on a chosen graph. The accuracy of this method will then be tested upon varying the number of classical optimization steps, the depth of the quantum circuit and the number of measurements required on the quantum device at each step etc. This will then allow us to define the total classical hardware time and the total quantum hardware time, giving us an initial estimate for the overall cost of running such an algorithm.
For many real world scenarios we do not necessarily need the most optimal solution, just one that is better than those currently utilized, so we will be judging submissions based on an analysis which balances the overall cost of the routine with the quality of the solution. Additional points will be given for the presentation and interpretation of the data in terms of the viability of these methods as the graph size and complexity are increased. We will also be looking for more advanced offerings, such as methods for post processing the quantum measurement results to better refine the classical solution of the graph and sufficient explorations in the space of connected graphs as well as explorations of the parameter space for the variational coefficients.

### Team Jumpstart Quantum
Team Members:
 - David Liu, Discord: 708042604654100561  Github: davidlearn   Email: Liud@pfw.edu
 - Yiping Wang, Discord: 999347935630348359  Github: wyp7         Email: yipingwang2023@u.northwestern.edu
 - Jiaqi Guo,   Discord: 1004397306063376485 Github: emrysguo     Email: jiaqiguo@andrew.cmu.edu

- understand how QAOA solves combinatorial optimization problems insh even NISQ era and potenitally beats classicial algorithms
- explore how QAOA solves a weight Max-Cut optimization problem in Qiskit quantum circuit implementation
- study how QAOA circuit depth p. measurement shots, and the pertange of quantum output iprocessed as input to the classicall optimization solver affect the <b>optimization</b> value (energey in Hamiltonian system) and <b>cost</b>.
- Discussed how to assess how to measure QAOA resolution vs ultimate optimal solution
- investigate how to optiize QAOA for accuracy and computing time in term of the initalization of variational parameter of ($\boldsymbol{\beta}$, $\boldsymbol{\gamma}$) and the circuit depth <b>p</b>
- Investigate how to scale QAOA to solve large optimization problems with the limited qubit size in current quantun computers.

### Finding

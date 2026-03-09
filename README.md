# Hi, I'm Xuan Lin 👋

## About Me
I am a robotics researcher focused on the mathematical and algorithmic foundations of robot intelligence. I work across the full stack, from temporal logic motion planning, optimization, and control theory to hardware integration and deployment.

## Featured Repos

### [Logic Network Flow (LNF)](https://github.com/LogicNetworkFlow/LNF)
An optimization-based task and motion planning framework that integrates temporal logic 
into efficient mixed-integer programs. LNF encodes temporal predicates as network flow 
constraints, yielding provably tighter convex relaxations and computational speedups of 
up to several orders of magnitude. Validated on vehicle routing, multi-robot coordination, 
dynamical systems, and real-time replanning on quadrupedal robots.

**Paper:** [arXiv:2509.24235](https://arxiv.org/abs/2509.24235) · **Website:** [logicnetworkflow.github.io](https://logicnetworkflow.github.io/)


### [Benders-Hybrid-MPC](https://github.com/XuanLin/Benders-MPC)
A warm-started Generalized Benders Decomposition framework for hybrid model predictive control. The algorithm stores and transfers cutting planes across MPC iterations, with theoretical guarantees on warm-starting suboptimality. The algorithm achieves 2–3× speedups over Gurobi and often exceeding 1000 Hz on cart-pole, free-flying robot, and humanoid balancing with hand-assistance tasks.

**Papers:** [arXiv:2406.00780](https://arxiv.org/abs/2406.00780)

### [Benders-STL-Planning](https://github.com/XuanLin/Benders-MPC)
A Benders Decomposition approach for bipedal navigation under Signal Temporal Logic constraints. The method partitions the NP-hard planning problem into a master problem for task scheduling and subproblems for kinematics and dynamics feasibility checks, enabling faster computation for bipedal robot long-horizon task and motion planning by 20× for logistics and automation tasks.

**Paper:** [arXiv:2508.13407](https://arxiv.org/abs/2508.13407)


### [MIBLP Benchmark](https://github.com/XuanLin/MIBLP_benchmark)
A comparative study of data-driven acceleration techniques for mixed-integer bilinear 
programs (MIBLPs) in robot motion planning. Benchmarks two reformulation strategies — 
complementarity constraints (MPCC) and McCormick envelopes (MICP) — with K-nearest 
neighbor warm-starting. Demonstrated on a linear inverted pendulum with contacts and 
the SCALER robot transitioning between bipedal and quadrupedal configurations.

**Paper:** [Frontiers in Robotics and AI, 2026](https://doi.org/10.3389/frobt.2025.1656564)

### [ReDUCE](https://github.com/RoMeLaUCLA/ReDUCE)
A method that exploits structure within small to medium size datasets to accelerate 
mixed-integer convex and nonlinear programs. ReDUCE uses unsupervised clustering to 
learn efficient reformulation strategies, reducing solving times from minutes to seconds. 
Demonstrated as a high-level planner for a robotic arm on a bookshelf organization problem.

**Paper:** [IEEE ICRA 2022](https://ieeexplore.ieee.org/document/9811566)

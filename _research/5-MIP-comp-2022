---
title: "Design and Implementation of an Heuristic-Enhanced Branch-and-Bound Solver for MILP"
collection: research
permalink: /research/5-MIP-comp-2022
excerpt: ''
paperurl: 'https://arxiv.org/pdf/2206.01857.pdf'
---

We present a solver for Mixed Integer Programs (MIP) developed for the MIP competition 2022. 
Given the 10 minutes bound on the computational time established by the rules of the competition, our method focuses on finding a feasible solution and improves it through a Branch-and-Bound algorithm. 
Another rule of the competition allows the use of up to 8 threads. 
Each thread is given a different primal heuristic, which has been tuned by hyper-parameters, to find a feasible solution. 
In every thread, once a feasible solution is found, we stop and we use a Branch-and-Bound method, embedded with local search heuristics, to ameliorate the incumbent solution. 
The three variants of the Diving heuristic that we implemented manage to find a feasible solution for 10 instances of the training data set. 
These heuristics are the best performing among the heuristics that we implemented. 
Our Branch-and-Bound algorithm is effective on a small portion of the training data set, and it manages to find an incumbent feasible solution for an instance that we could not solve with the Diving heuristics. 
Overall, our combined methods, when implemented with extensive computational power, can solve 11 of the 19 problems of the training data set within the time limit. 
Our submission to the MIP competition was awarded the "Outstanding Student Submission" honorable mention.

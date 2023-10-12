---
title: "Capacity Planning in Stable Matching"
collection: research
permalink: /research/2-capacity-planning
excerpt: 'with Margarida Carvalho, Andrea Lodi, Ignacio Rios and Alfredo Torrico. Accepted at MATCH-UP 2022, EAAMO 2022, EC 2023.'
paperurl: 'https://arxiv.org/pdf/2110.00734.pdf'
---
Assignment mechanisms for many-to-one matching markets with preferences revolve around the key con-
cept of stability. Using school choice as our matching market application, we introduce the problem of
jointly allocating a school capacity expansion and finding the best stable allocation for the students in
the expanded market. We analyze theoretically the problem, focusing on the trade-off behind the multi-
plicity of student-optimal assignments, the incentive properties, and the problem’s complexity. Due to the
impossibility of efficiently solving the problem with classical methods, we generalize existent mathematical
programming formulations of stability constraints to our setting, most of which result in integer quadratically-
constrained programs. In addition, we propose a novel mixed-integer linear programming formulation that
is exponentially-large on the problem size. We show that its stability constraints can be separated in linear
time, leading to an effective cutting-plane method. We evaluate the performance of our approaches in a
detailed computational study, and we find that our cutting-plane method outperforms mixed-integer pro-
gramming solvers applied to the formulations obtained by extending existing approaches. We also propose
two heuristics that are effective for large instances of the problem. Finally, we use the Chilean school choice
system data to demonstrate the impact of capacity planning under stability conditions. Our results show
that each additional school seat can benefit multiple students. Moreover, our methodology can prioritize
the assignment of previously unassigned students or improve the assignment of several students through
improvement chains. These insights empower the decision-maker in tuning the matching algorithm to provide
a fair application-oriented solution.



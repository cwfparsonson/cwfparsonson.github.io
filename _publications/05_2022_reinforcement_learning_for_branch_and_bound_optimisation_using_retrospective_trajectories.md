---
title: "Reinforcement Learning for Branch-and-Bound Optimisation using Retrospective Trajectories"
collection: publications
permalink: /publication/05/2022/reinforcement_learning_for_branch_and_bound_optimisation_using_retrospective_trajectories
date: 2022-08-01
venue: AAAI'23: Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence
paperurl: https://arxiv.org/abs/2205.14345?context=cs
citation: 'C. W. F. Parsonson, A. Laterre and T. D. Barrett &quot;Reinforcement Learning for Branch-and-Bound Optimisation using Retrospective Trajectories&quot;, AAAI'23: Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence, 2023'
---
<div style="text-align: justify"> 
Combinatorial optimisation problems framed as mixed integer linear programmes
(MILPs) are ubiquitous across a range of real-world applications. The canonical
branch-and-bound algorithm seeks to exactly solve MILPs by constructing a
search tree of increasingly constrained sub-problems. In practice, its solving
time performance is dependent on heuristics, such as the choice of the next
variable to constrain ('branching'). Recently, machine learning (ML) has
emerged as a promising paradigm for branching. However, prior works have
struggled to apply reinforcement learning (RL), citing sparse rewards,
difficult exploration, and partial observability as significant challenges.
Instead, leading ML methodologies resort to approximating high quality
handcrafted heuristics with imitation learning (IL), which precludes the
discovery of novel policies and requires expensive data labelling. In this
work, we propose retro branching; a simple yet effective approach to RL for
branching. By retrospectively deconstructing the search tree into multiple
paths each contained within a sub-tree, we enable the agent to learn from
shorter trajectories with more predictable next states. In experiments on four
combinatorial tasks, our approach enables learning-to-branch without any expert
guidance or pre-training. We outperform the current state-of-the-art RL
branching algorithm by 3-5x and come within 20% of the best IL method's
performance on MILPs with 500 constraints and 1000 variables, with ablations
verifying that our retrospectively constructed trajectories are essential to
achieving these results.
</div>

[View paper here](https://arxiv.org/abs/2205.14345?context=cs)


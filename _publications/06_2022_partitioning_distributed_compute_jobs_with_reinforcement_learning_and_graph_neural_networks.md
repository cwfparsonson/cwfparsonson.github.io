---
title: "Partitioning Distributed Compute Jobs with Reinforcement Learning and Graph Neural Networks"
collection: publications
permalink: /publication/06_2022_partitioning_distributed_compute_jobs_with_reinforcement_learning_and_graph_neural_networks
date: 2022-09-01
venue: Under peer review
paperurl: Link to be added soon.
citation: 'C. W. F. Parsonson and G. Zervas &quot;Partitioning Distributed Compute Jobs with Reinforcement Learning and Graph Neural Networks&quot;, *Under peer review*, 2022'
---
<div style="text-align: justify"> 
From natural language processing to genome sequencing, large-scale machine
learning models are bringing advances to a broad range of fields. Many of these
models are too large to be trained on a single machine, and instead must be
distributed across multiple devices. This has motivated the research of new
compute and network systems capable of handling such tasks. In particular,
recent work has focused on developing management schemes which decide
*how* to allocate distributed resources such that some overall
objective, such as minimising the job completion time (JCT), is optimised.
However, such studies omit explicit consideration of *how much* a job
should be distributed, usually assuming that maximum distribution is desirable.
In this work, we show that maximum parallelisation is sub-optimal in relation
to user-critical metrics such as throughput and blocking rate. To address this,
we propose PAC-ML (partitioning for asynchronous computing with machine learning), which leverages a
graph neural network and reinforcement learning to learn how much to
partition computation graphs such that the number of jobs which meet arbitrary
user-defined JCT requirements is maximised. In experiments with five real deep
learning computation graphs on a recently proposed optical architecture across
four user-defined JCT requirement distributions, we demonstrate PAC-ML
achieving up to 56.2% lower blocking rates in dynamic job arrival settings
than the canonical maximum parallelisation strategy used by most prior works. 
</div>

<!--
   -[View paper here](https://arxiv.org/abs/2205.14345?context=cs)
   -->


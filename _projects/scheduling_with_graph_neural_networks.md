---
title: "Scheduling with Graph Neural Networks"
excerpt: "Two broad communities concern themselves with scheduling; computer science and networking. Often the computer science approach involves only the consideration of the job computation graph that each flow being scheduled is part of, whereas the properties and states of the network in which the flow is being scheduled are ignored. This leads to unrealistic assumptions of 0 latency for links, switches, etc., and can incur large buffering penalties due to congestion queueing. By contrast, the networking approach often only considers the network, ignoring the job computation graph that each flow is part of and only focusing on minmising e.g. flow completion time, rather than optimising the scheduler's performance with respsect to the overall job graph. This project saw a new approach which considered both the job graph *and* the network when scheduling flows. By framing this as a combinatorial optimisation problem whereby an agent must choose an optimal sub-set of queued flows in a network graph to be scheduled for the next timeslot, a graph neural network was trained to schedule flows in an end-to-end reinforcement learning environment, demonstrating both good performance and the ability to be scaled to large networks.<br/><img src='/images/projects/scheduling_with_graph_neural_networks/excerpt.png'>"
collection: projects
---

Text here
---
title: "Network Traffic Generation Tool"
excerpt: "Data related to communication networks is often sensitve and proprietary. Consequently, many networking academic papers are published without open-accessing the network traffic data that was used to obtain the results, and when they are published the datasets are often too limited for data-hungry applications such as reinforcement learning. In an effort to aid reproducibility, some authors release characteristic distributions which broadly describe the underlying data. However, these distributions are often not analytically described and may not fall under the classic 'named' distributions (Gaussian, log-normal, Pareto etc.). As a result, other researchers find themselves using unrealistically simple uniform traffic distributions or their own distributions which are difficult to universally benchmark. This project saw the development of an open-access network traffic generation tool for (1) standardising the traffic patterns used to benchmark networking systems, and (2) enabling rapid and easy replication of literature distributions even in the absence of raw open-access data.<br/><img src='/images/projects/network_traffic_generation_tool/excerpt.png'>"
collection: projects
---

<div style="text-align: justify"> 
Data related to communication networks is often sensitve and proprietary. Consequently, many networking academic papers are published without open-accessing the network traffic data that was used to obtain the results, and when they are published the datasets are often too limited for data-hungry applications such as reinforcement learning. In an effort to aid reproducibility, some authors release characteristic distributions which broadly describe the underlying data. However, these distributions are often not analytically described and may not fall under the classic 'named' distributions (Gaussian, log-normal, Pareto etc.). As a result, other researchers find themselves using unrealistically simple uniform traffic distributions or their own distributions which are difficult to universally benchmark. This project saw the development of an open-access network traffic generation tool for (1) standardising the traffic patterns used to benchmark networking systems, and (2) enabling rapid and easy replication of literature distributions even in the absence of raw open-access data.
</div>
<br/><br/>



## A Case in Point
<div style="text-align: justify"> 
In one Google DeepMind paper {% cite paliwal_2020 %}, researchers trained a graph neural network (GNN) to place operations (ops) onto machines for real TensorFlow computation (job) graphs. Placing ops and scheduling the tensors (flows) that pass between them is a common task for data centres, which often have many specialised high-bandwidth processing units and are therefore ideal for hosting large-scale machine learning inference and training. 

<br/><br/>
Google did not want to release real TensorFlow data. In an effort to aid reproducibility, the researchers published some characteristic distributions of the real graphs and released a database of 'synthetic' graphs. However, as shown in the image below, the distributions of the real and synthetic graphs are quite different. As such, benchmarking other systems on realistic TensorFlow graphs is not possible using only the synthetic dataset.   

<br/><br/>
{% include image.html url="/images/projects/network_traffic_generation_tool/num_nodes_num_edges_paper_dists.png" description="Histogram distribution for the number of nodes (operations) in the real and synthetic TensorFlow job graphs." %}

<br/><br/>
This is just one of many encounters of distribution-related limitations networking researchers face when reading, reproducing and benchmarking against literture results; fragments of information that describe parts of the data which are difficult to piece together into a dataset which accurately mimics the real/original data. Is there a way that we can make this process quick and easy?




## 





</div>


### References
{% bibliography %}






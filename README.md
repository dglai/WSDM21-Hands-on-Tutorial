WSDM'21 Tutorial: Scalable Graph Neural Networks with Deep Graph Library
===

**Time:** Mar. 8, 2021, 9:30 a.m. - 12:00 p.m. (GMT+2)

**Author:** Da Zheng, Minjie Wang, Quan Gan, Xiang Song, Zheng Zhang from *Amazon AI*

Learning from graph and relational data plays a major role in many applications including social network analysis, marketing, e-commerce, information retrieval, knowledge modeling, medical and biological sciences, engineering, and others. In the last few years, Graph Neural Networks (GNNs) have emerged as a promising new supervised learning framework capable of bringing the power of deep representation learning to graph and relational data. This ever-growing body of research has shown that GNNs achieve state-of-the-art performance for problems such as link prediction, fraud detection, target-ligand binding activity prediction, knowledge-graph completion, and product recommendations. In practice, many of the real-world graphs are very large. It is urgent to have scalable solutions to train GNN on large graphs efficiently. This tutorial will provide an overview of the theory behind GNNs, discuss the types of problems that GNNs are well suited for, and introduce some of the most widely used GNN model architectures and problems/applications that are designed to solve. It will introduce the Deep Graph Library (DGL), a scalable GNN framework that simplifies the development of efficient GNN-based training at a large scale. The tutorial will provide hands-on sessions to show how to use DGL to perform scalable training in different settings (multi-GPU training and distributed training).

Agenda
---

| Time  | Session | Instructor |
| --- | --- | --- |
| 9:00 - 9:50 | A Blitz Introduction to Deep Graph Library | Minjie Wang | 
| 9:50 - 10:00 | Q & A and Break |  |
| 10:00 - 10:50 | Stochastic GNN Training | Quan Gan |
| 10:50 - 11:00 | Q & A and Break |  |
| 11:00 - 11:50 | Mini-batch Training for Link Prediction & Multi-GPU Training | Xiang Song |
| 11:50 - 12:00 | Final Q & A | |

Requirements
---

* dgl 0.6
* torch >= 1.7.0

Community
---

If you have any questions, [join our Slack](https://join.slack.com/t/deep-graph-library/shared_invite/zt-eb4ict1g-xcg3PhZAFAB8p6dtKuP6xQ) channel `wsdm21-tutorial`.

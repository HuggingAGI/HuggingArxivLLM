# 致力于解决实际问题，《学习交付：构建蒙特利尔载货车辆路径问题的基础模型》一文，旨在探索并提出一种针对载货车辆在蒙特利尔地区进行高效路线规划的基础模型。

发布时间：2024年02月28日

`LLM应用`

> Learning to Deliver: a Foundation Model for the Montreal Capacitated Vehicle Routing Problem

# 摘要

> 本文介绍了一种创新的深度学习模型——蒙特利尔载货车辆路径问题基础模型（FM-MCVRP），它能有效求解反映众多真实应用场景特点的载货车辆路径问题（CVRP）变体，并生成高质量解决方案。MCVRP问题首次由Bengio等人于2021年明确阐述，它建立在一个类似城市的固定有限图形之上。每个MCVRP实例实质上是固定图形中随机选取的部分节点构成的子图，代表着某一天实际配送问题中可能的送货地址集合。我们巧妙地将MCVRP问题转化为一个类似自然语言处理的任务，并借助嵌套在大型语言模型（LLM）框架内的Transformer架构，以监督学习的方式对源自算法、计算成本较低的次优MCVRP解决方案进行训练。经过广泛而深入的计算实验，我们发现FM-MCVRP不仅能够在训练数据上生成更优质的MCVRP解决方案，还能成功应用于训练阶段未曾遇到的更大规模问题实例。即使对比最先进的启发式算法产生的近乎最优解，FM-MCVRP在使用较弱的数据训练条件下仍能取得颇具竞争力的结果，例如在处理400个客户问题时，FM-MCVRP给出的解决方案平均距离基准点仅相差2%。此外，我们的研究成果进一步揭示了FM-MCVRP的独特之处，即作为一个统一模型，它能在多种规模的问题实例和参数设置（如车辆容量）下始终保持稳定、可信赖的表现，这与之前相关文献中的研究有所不同。

> In this paper, we present the Foundation Model for the Montreal Capacitated Vehicle Routing Problem (FM-MCVRP), a novel Deep Learning (DL) model that approximates high-quality solutions to a variant of the Capacitated Vehicle Routing Problem (CVRP) that characterizes many real-world applications. The so-called Montreal Capacitated Vehicle Routing Problem (MCVRP), first formally described by Bengio et al. (2021), is defined on a fixed and finite graph, which is analogous to a city. Each MCVRP instance is essentially the sub-graph connecting a randomly sampled subset of the nodes in the fixed graph, which represent a set of potential addresses in a real-world delivery problem on a given day. Our work exploits this problem structure to frame the MCVRP as an analogous Natural Language Processing (NLP) task. Specifically, we leverage a Transformer architecture embedded in a Large Language Model (LLM) framework to train our model in a supervised manner on computationally inexpensive, sub-optimal MCVRP solutions obtained algorithmically. Through comprehensive computational experiments, we show that FM-MCVRP produces better MCVRP solutions than the training data and generalizes to larger sized problem instances not seen during training. Even when compared to near-optimal solutions from state-of-the-art heuristics, FM-MCVRP yields competitive results despite being trained on inferior data. For instance, for 400-customer problems, FM-MCVRP solutions on average fall within 2% of the benchmark. Our results further demonstrate that unlike prior works in the literature, FM-MCVRP is a unified model, which performs consistently and reliably on a range of problem instance sizes and parameter values such as the vehicle capacity.

[Arxiv](https://arxiv.org/abs/2403.00026)
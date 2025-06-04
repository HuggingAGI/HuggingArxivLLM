# 通过测试时间投影学习提升神经组合优化在车辆路径问题中的泛化性能

发布时间：2025年06月02日

`LLM应用` `运筹学`

> Improving Generalization of Neural Combinatorial Optimization for Vehicle Routing Problems via Test-Time Projection Learning

# 摘要

> 神经组合优化 (NCO) 通过减少对大量手动工程的需求，为解决车辆路径问题 (VRPs) 提供了一种有前景的基于学习的方法。然而，现有的 NCO 方法在小规模实例（如 100 个节点）上表现良好，但面对大规模场景时，性能显著下降。这种下降源于训练数据与测试数据之间的分布偏移，导致在小规模实例上学到的策略无法有效扩展到更大规模的问题。

为了解决这一限制，我们提出了一种由大型语言模型 (LLMs) 驱动的新学习框架。该框架通过学习训练分布与测试分布之间的映射关系，增强了 NCO 模型的扩展能力。与现有需要与神经网络联合训练的技术不同，我们的方法仅在推理阶段运行，避免了对模型重新训练的需求。

大量实验表明，我们的方法使一个基础模型（在 100 个节点的实例上进行训练）能够在来自不同分布的 10 万节点大规模旅行商问题 (TSP) 和带容量约束的车辆路径问题 (CVRP) 上实现更优的性能。

> Neural Combinatorial Optimization (NCO) has emerged as a promising learning-based paradigm for addressing Vehicle Routing Problems (VRPs) by minimizing the need for extensive manual engineering. While existing NCO methods, trained on small-scale instances (e.g., 100 nodes), have demonstrated considerable success on problems of similar scale, their performance significantly degrades when applied to large-scale scenarios. This degradation arises from the distributional shift between training and testing data, rendering policies learned on small instances ineffective for larger problems. To overcome this limitation, we introduce a novel learning framework driven by Large Language Models (LLMs). This framework learns a projection between the training and testing distributions, which is then deployed to enhance the scalability of the NCO model. Notably, unlike prevailing techniques that necessitate joint training with the neural network, our approach operates exclusively during the inference phase, obviating the need for model retraining. Extensive experiments demonstrate that our method enables a backbone model (trained on 100-node instances) to achieve superior performance on large-scale Traveling Salesman Problem (TSP) and Capacitated Vehicle Routing Problem (CVRP) of up to 100K nodes from diverse distributions.

[Arxiv](https://arxiv.org/abs/2506.02392)
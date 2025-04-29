# Intelligent4DSE：结合图神经网络与大型语言模型，优化高层次综合设计空间探索

发布时间：2025年04月28日

`LLM应用` `电子设计自动化` `硬件设计`

> Intelligent4DSE: Optimizing High-Level Synthesis Design Space Exploration with Graph Neural Networks and Large Language Models

# 摘要

> 高阶综合（HLS）设计空间探索（DSE）是电子设计自动化（EDA）中的优化过程，旨在通过系统性探索高阶设计配置，实现性能、面积和功耗（PPA）平衡的帕累托最优硬件实现。在优化这一过程时，HLS预测任务通常采用消息传递神经网络（MPNNs），利用其复杂架构实现高精度预测。这些预测器在DSE过程中充当评估器，有效规避了传统HLS工具所需的时间消耗估计。然而，现有模型往往侧重于结构复杂性和训练损失最小化，忽视了任务特定特性。此外，尽管进化算法在DSE中广泛应用，但它们通常需要大量领域特定知识来设计有效的交叉和变异算子。为了解决这些限制，我们提出了CoGNNs-LLMEA框架，结合了具有任务自适应消息传递的图神经网络和增强的大语言模型进化算法。作为预测模型，CoGNNs直接利用编译器前端处理后从源代码生成的中间表示，无需调用HLS工具即可预测结果质量（QoR）。由于其强大的任务适应性，CoGNNs可以调整以预测HLS后和实现后的结果，有效弥合了高层次抽象与物理实现特性之间的差距。CoGNNs在HLS后QoR预测中实现了最先进的预测精度，与基线模型相比，延迟的平均预测误差减少了2.8【数学公式】倍，资源利用率减少了3.4【数学公式】倍。

> High-level synthesis (HLS) design space exploration (DSE) is an optimization process in electronic design automation (EDA) that systematically explores high-level design configurations to achieve Pareto-optimal hardware implementations balancing performance, area, and power (PPA). To optimize this process, HLS prediction tasks often employ message-passing neural networks (MPNNs), leveraging complex architectures to achieve high accuracy. These predictors serve as evaluators in the DSE process, effectively bypassing the time-consuming estimations traditionally required by HLS tools. However, existing models often prioritize structural complexity and minimization of training loss, overlooking task-specific characteristics. Additionally, while evolutionary algorithms are widely used in DSE, they typically require extensive domain-specific knowledge to design effective crossover and mutation operators. To address these limitations, we propose CoGNNs-LLMEA, a framework that integrates a graph neural network with task-adaptive message passing and a large language model-enhanced evolutionary algorithm. As a predictive model, CoGNNs directly leverages intermediate representations generated from source code after compiler front-end processing, enabling prediction of quality of results (QoR) without invoking HLS tools. Due to its strong adaptability to tasks, CoGNNs can be tuned to predict post-HLS and post-implementation outcomes, effectively bridging the gap between high-level abstractions and physical implementation characteristics. CoGNNs achieves state-of-the-art prediction accuracy in post-HLS QoR prediction, reducing mean prediction errors by 2.8$\times$ for latency and 3.4$\times$ for resource utilization compared to baseline models.

[Arxiv](https://arxiv.org/abs/2504.19649)
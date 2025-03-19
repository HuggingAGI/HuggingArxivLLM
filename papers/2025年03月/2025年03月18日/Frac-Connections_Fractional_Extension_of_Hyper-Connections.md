# Frac-Connections：超连接的分数扩展

发布时间：2025年03月18日

`LLM理论`

> Frac-Connections: Fractional Extension of Hyper-Connections

# 摘要

> 残差连接是现代深度学习架构的核心，它通过有效缓解梯度消失问题，使训练超深层网络成为可能。Hyper-Connections 最近通过引入多深度连接强度，将残差连接进行了泛化，从而解决了梯度消失与表示坍塌之间的跷跷板效应。然而，Hyper-Connections 通过扩展隐藏状态的宽度增加了内存访问成本。本文中，我们提出了 Frac-Connections，这是一种创新方法，将隐藏状态划分为多个部分，而非简单扩展其宽度。Frac-Connections 在保留 Hyper-Connections 部分优势的同时，显著降低了内存消耗。为了验证其有效性，我们在语言任务上进行了大规模实验，其中最大规模的实验是在 3T 个标记上训练的 7B MoE 模型，结果表明 Frac-Connections 的性能显著优于传统残差连接。

> Residual connections are central to modern deep learning architectures, enabling the training of very deep networks by mitigating gradient vanishing. Hyper-Connections recently generalized residual connections by introducing multiple connection strengths at different depths, thereby addressing the seesaw effect between gradient vanishing and representation collapse. However, Hyper-Connections increase memory access costs by expanding the width of hidden states. In this paper, we propose Frac-Connections, a novel approach that divides hidden states into multiple parts rather than expanding their width. Frac-Connections retain partial benefits of Hyper-Connections while reducing memory consumption. To validate their effectiveness, we conduct large-scale experiments on language tasks, with the largest being a 7B MoE model trained on up to 3T tokens, demonstrating that Frac-Connections significantly outperform residual connections.

[Arxiv](https://arxiv.org/abs/2503.14125)
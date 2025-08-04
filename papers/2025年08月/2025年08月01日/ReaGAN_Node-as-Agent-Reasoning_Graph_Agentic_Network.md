# # ReaGAN：基于智能体推理的图网络节点智能系统

发布时间：2025年08月01日

`Agent` `图神经网络` `智能体`

> ReaGAN: Node-as-Agent-Reasoning Graph Agentic Network

# 摘要

> 图神经网络（GNNs）通过预定义的信息传播机制在基于图的学习中取得了显著成功。然而，传统方案存在两大局限：首先，无法有效处理节点间信息量的不平衡；其次，过度依赖局部结构相似性而忽略了全局语义关系，限制了模型对远处相关信息的捕捉能力。为此，我们提出检索增强的图智能体网络（ReaGAN），这是一种基于智能体的框架，赋予每个节点自主决策能力。每个节点作为独立智能体，基于内部记忆进行自主规划和自适应信息传播。同时，借助检索增强生成（RAG），节点能够访问语义相关的内容并构建全局关系。实验表明，ReaGAN在少量样本的上下文设置下，无需微调即可实现优异性能，充分展现了智能体规划和全局检索在图学习中的潜力。

> Graph Neural Networks (GNNs) have achieved remarkable success in graph-based learning by propagating information among neighbor nodes via predefined aggregation mechanisms. However, such fixed schemes often suffer from two key limitations. First, they cannot handle the imbalance in node informativeness -- some nodes are rich in information, while others remain sparse. Second, predefined message passing primarily leverages local structural similarity while ignoring global semantic relationships across the graph, limiting the model's ability to capture distant but relevant information. We propose Retrieval-augmented Graph Agentic Network (ReaGAN), an agent-based framework that empowers each node with autonomous, node-level decision-making. Each node acts as an agent that independently plans its next action based on its internal memory, enabling node-level planning and adaptive message propagation. Additionally, retrieval-augmented generation (RAG) allows nodes to access semantically relevant content and build global relationships in the graph. ReaGAN achieves competitive performance under few-shot in-context settings using a frozen LLM backbone without fine-tuning, showcasing the potential of agentic planning and local-global retrieval in graph learning.

[Arxiv](https://arxiv.org/abs/2508.00429)
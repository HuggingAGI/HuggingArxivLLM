# 多模态多跳源检索在网络问答中的应用

发布时间：2025年01月07日

`LLM应用

理由：这篇论文主要讨论了多模态多跳问答（QA）中的学习与推理挑战，并提出了一种基于句子语义结构的图推理网络。虽然论文中提到了预训练模型的特征表示，但核心内容集中在如何利用图结构来提升多模态多跳问答的性能。这与LLM应用相关，因为预训练模型（如大型语言模型）在多模态任务中的应用是一个重要的研究方向。论文的重点在于如何利用图结构来增强模型在多模态任务中的表现，而不是深入探讨LLM的理论或构建新的LLM架构。因此，将其归类为LLM应用是合适的。` `问答系统` `多模态学习`

> Multimodal Multihop Source Retrieval for Web Question Answering

# 摘要

> 本文聚焦于多模态多跳问答（QA）中的学习与推理挑战。我们提出了一种基于句子语义结构的图推理网络，旨在学习多源推理路径，并从图像和文本模态中提取支持事实以回答问题。本文深入探讨了图结构在多模态多跳问答中的重要性，并以WebQA为研究对象。我们构建了一个强大的基线模型，通过成对分类任务识别相关来源。研究表明，合理利用预训练模型的特征表示，图结构能够显著提升多模态多跳问答的性能。我们指出，图结构和邻接矩阵均为任务相关的先验知识，且图结构有助于提升任务检索性能。实验与可视化分析表明，图网络上的消息传播或整个图结构可替代大规模多模态变压器中的逐令牌交叉注意力机制。我们展示了该方法的适用性，并在变压器基线模型上实现了4.6%的检索F1分数提升，尽管模型非常轻量。此外，我们还验证了该模型在大规模检索场景中的适用性。

> This work deals with the challenge of learning and reasoning over multi-modal multi-hop question answering (QA). We propose a graph reasoning network based on the semantic structure of the sentences to learn multi-source reasoning paths and find the supporting facts across both image and text modalities for answering the question. In this paper, we investigate the importance of graph structure for multi-modal multi-hop question answering. Our analysis is centered on WebQA. We construct a strong baseline model, that finds relevant sources using a pairwise classification task. We establish that, with the proper use of feature representations from pre-trained models, graph structure helps in improving multi-modal multi-hop question answering. We point out that both graph structure and adjacency matrix are task-related prior knowledge, and graph structure can be leveraged to improve the retrieval performance for the task. Experiments and visualized analysis demonstrate that message propagation over graph networks or the entire graph structure can replace massive multimodal transformers with token-wise cross-attention. We demonstrated the applicability of our method and show a performance gain of \textbf{4.6$\%$} retrieval F1score over the transformer baselines, despite being a very light model. We further demonstrated the applicability of our model to a large scale retrieval setting.

[Arxiv](https://arxiv.org/abs/2501.04173)
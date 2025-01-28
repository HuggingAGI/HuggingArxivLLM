# 整合多元视角：多智能体框架助力知识图谱错误检测

发布时间：2025年01月27日

`Agent

理由：这篇论文提出了一种多智能体框架MAKGED，通过协作使用多个大型语言模型（LLMs）来提升知识图谱错误检测的准确性和决策透明性。该框架涉及多个智能体的协作和讨论，符合“Agent”分类的定义，即涉及多个智能体或代理的协作和交互。` `知识图谱`

> Harnessing Diverse Perspectives: A Multi-Agent Framework for Enhanced Error Detection in Knowledge Graphs

# 摘要

> # 摘要
知识图谱在工业应用中广泛使用，错误检测对确保下游应用的可靠性至关重要。然而，现有方法往往无法有效利用细粒度子图信息，仅依赖固定图结构，且决策过程缺乏透明度，导致检测性能不佳。本文提出了一种新颖的多智能体框架MAKGED，通过协作使用多个大型语言模型（LLMs），在训练中将细粒度双向子图嵌入与LLM查询嵌入结合，生成四个专门智能体。这些智能体利用不同维度的子图信息进行多轮讨论，提升错误检测的准确性并确保决策透明性。在FB15K和WN18RR上的实验表明，MAKGED优于现有方法，显著提升了知识图谱评估的准确性和鲁棒性。对于特定工业场景，MAKGED可利用领域知识图谱训练专门智能体进行错误检测，展现了其潜在的工业应用价值。代码和数据集已开源：https://github.com/kse-ElEvEn/MAKGED。

> Knowledge graphs are widely used in industrial applications, making error detection crucial for ensuring the reliability of downstream applications. Existing error detection methods often fail to effectively leverage fine-grained subgraph information and rely solely on fixed graph structures, while also lacking transparency in their decision-making processes, which results in suboptimal detection performance. In this paper, we propose a novel Multi-Agent framework for Knowledge Graph Error Detection (MAKGED) that utilizes multiple large language models (LLMs) in a collaborative setting. By concatenating fine-grained, bidirectional subgraph embeddings with LLM-based query embeddings during training, our framework integrates these representations to produce four specialized agents. These agents utilize subgraph information from different dimensions to engage in multi-round discussions, thereby improving error detection accuracy and ensuring a transparent decision-making process. Extensive experiments on FB15K and WN18RR demonstrate that MAKGED outperforms state-of-the-art methods, enhancing the accuracy and robustness of KG evaluation. For specific industrial scenarios, our framework can facilitate the training of specialized agents using domain-specific knowledge graphs for error detection, which highlights the potential industrial application value of our framework. Our code and datasets are available at https://github.com/kse-ElEvEn/MAKGED.

[Arxiv](https://arxiv.org/abs/2501.15791)
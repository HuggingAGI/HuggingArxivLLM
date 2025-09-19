# TableDART：用于表格理解的动态自适应多模态路由

发布时间：2025年09月18日

`Agent` `基础理论`

> TableDART: Dynamic Adaptive Multi-Modal Routing for Table Understanding

# 摘要

> 从表格数据中同时建模语义与结构信息，一直是实现高效表格理解的核心难题。现有“表格转文本”方法将表格扁平化适配大型语言模型（LLMs），却丢失关键结构线索；“表格转图像”方法虽保留结构，却难以处理细粒度语义。近期“表格转多模态”策略尝试融合文本与视觉视图，但存在局限：（1）在大型多模态LLM（MLLMs）中静态处理每个查询-表格对的两种模态，不可避免引入冗余甚至冲突；（2）依赖昂贵的MLLM微调。为此，我们提出TableDART——一个训练高效的框架，通过重用预训练单模态模型整合多模态视图。TableDART引入轻量级MLP门控网络（259万参数），能为每个表格-查询对动态选择最优路径（仅文本、仅图像或融合），有效减少模态冗余与冲突。此外，我们设计新型智能体，通过分析文本模型和图像模型的输出协调跨模态知识整合，既可选择最佳结果，也能通过推理合成新答案。该设计避免了全MLLM微调的高昂成本。在七个基准数据集上的大量实验显示，TableDART在开源模型中刷新最先进性能，平均比最强基线高出4.02%。代码链接：https://anonymous.4open.science/r/TableDART-C52B

> Modeling semantic and structural information from tabular data remains a core challenge for effective table understanding. Existing Table-as-Text approaches flatten tables for large language models (LLMs), but lose crucial structural cues, while Table-as-Image methods preserve structure yet struggle with fine-grained semantics. Recent Table-as-Multimodality strategies attempt to combine textual and visual views, but they (1) statically process both modalities for every query-table pair within a large multimodal LLMs (MLLMs), inevitably introducing redundancy and even conflicts, and (2) depend on costly fine-tuning of MLLMs. In light of this, we propose TableDART, a training-efficient framework that integrates multimodal views by reusing pretrained single-modality models. TableDART introduces a lightweight 2.59M-parameter MLP gating network that dynamically selects the optimal path (either Text-only, Image-only, or Fusion) for each table-query pair, effectively reducing redundancy and conflicts from both modalities. In addition, we propose a novel agent to mediate cross-modal knowledge integration by analyzing outputs from text- and image-based models, either selecting the best result or synthesizing a new answer through reasoning. This design avoids the prohibitive costs of full MLLM fine-tuning. Extensive experiments on seven benchmarks show that TableDART establishes new state-of-the-art performance among open-source models, surpassing the strongest baseline by an average of 4.02%. The code is available at: https://anonymous.4open.science/r/TableDART-C52B

[Arxiv](https://arxiv.org/abs/2509.14671)
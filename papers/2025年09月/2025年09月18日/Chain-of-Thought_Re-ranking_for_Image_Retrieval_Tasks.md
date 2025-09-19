# 面向图像检索任务的思维链重排序

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Chain-of-Thought Re-ranking for Image Retrieval Tasks

# 摘要

> 图像检索是计算机视觉领域中一个基础且极具挑战性的问题。尽管多模态大型语言模型（MLLMs）的最新进展已展现出强大的推理能力，但现有方法往往仅将其用于评估环节，并未直接纳入排序过程。这使得其丰富的多模态推理能力未被充分发挥，进而导致性能不理想。为此，本文提出一种新颖的思维链重排序（CoTRR）方法。具体来说，我们设计了列表式排序提示，让MLLM直接参与候选图像的重排序。这一排序过程依托图像评估提示，用于衡量每个候选图像与用户查询的匹配度。通过让MLLM进行列表式推理，我们的方法支持全局比较、一致推理和可解释决策，而这些正是精准图像检索的核心要素。为实现结构化与细粒度分析，我们还引入了查询解构提示，将原始查询拆解为多个语义组件。在五个数据集上的大量实验验证了CoTRR方法的有效性，它在文本到图像检索（TIR）、组合图像检索（CIR）和基于聊天的图像检索（Chat-IR）这三个任务上均达到了当前最优性能。相关代码已开源：https://github.com/freshfish15/CoTRR。

> Image retrieval remains a fundamental yet challenging problem in computer vision. While recent advances in Multimodal Large Language Models (MLLMs) have demonstrated strong reasoning capabilities, existing methods typically employ them only for evaluation, without involving them directly in the ranking process. As a result, their rich multimodal reasoning abilities remain underutilized, leading to suboptimal performance. In this paper, we propose a novel Chain-of-Thought Re-Ranking (CoTRR) method to address this issue. Specifically, we design a listwise ranking prompt that enables MLLM to directly participate in re-ranking candidate images. This ranking process is grounded in an image evaluation prompt, which assesses how well each candidate aligns with users query. By allowing MLLM to perform listwise reasoning, our method supports global comparison, consistent reasoning, and interpretable decision-making - all of which are essential for accurate image retrieval. To enable structured and fine-grained analysis, we further introduce a query deconstruction prompt, which breaks down the original query into multiple semantic components. Extensive experiments on five datasets demonstrate the effectiveness of our CoTRR method, which achieves state-of-the-art performance across three image retrieval tasks, including text-to-image retrieval (TIR), composed image retrieval (CIR) and chat-based image retrieval (Chat-IR). Our code is available at https://github.com/freshfish15/CoTRR .

[Arxiv](https://arxiv.org/abs/2509.14746)
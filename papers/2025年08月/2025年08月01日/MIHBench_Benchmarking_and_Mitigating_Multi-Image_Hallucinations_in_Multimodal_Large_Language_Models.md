# MIHBench：多模态大型语言模型中多图像幻觉的基准测试与缓解

发布时间：2025年08月01日

`LLM应用` `多模态模型` `图像处理`

> MIHBench: Benchmarking and Mitigating Multi-Image Hallucinations in Multimodal Large Language Models

# 摘要

> 尽管人们对多模态大语言模型中的幻觉现象越来越感兴趣，但现有研究主要集中在单图像设置上，多图像场景下的幻觉问题仍未得到充分研究。为了解决这一研究空白，我们进行了首个针对多图像 MLLM 幻觉现象的系统性研究，并提出了 MIHBench，这是一个专门用于评估多图像环境下物体相关幻觉的基准测试。MIHBench 包含三个核心任务：多图像物体存在幻觉、多图像物体计数幻觉和物体身份一致性幻觉，旨在针对物体存在性理解、数量推理以及跨视角身份一致性进行研究。通过广泛的评估，我们发现与多图像幻觉发生相关的几个关键因素，包括：图像输入数量与幻觉发生概率之间的渐进关系；单图像幻觉倾向与多图像情境下幻觉表现之间的强相关性；以及同物图像比例和负样本在图像序列中的位置对物体身份一致性幻觉发生的影响。为应对这些挑战，我们提出了一种动态注意力平衡机制，能够在保持整体视觉注意力比例的同时调整图像间注意力分布。在多个先进 MLLM 上的实验表明，我们的方法能够有效减少幻觉发生，并提升多图像场景下的语义整合和推理稳定性。

> Despite growing interest in hallucination in Multimodal Large Language Models, existing studies primarily focus on single-image settings, leaving hallucination in multi-image scenarios largely unexplored. To address this gap, we conduct the first systematic study of hallucinations in multi-image MLLMs and propose MIHBench, a benchmark specifically tailored for evaluating object-related hallucinations across multiple images. MIHBench comprises three core tasks: Multi-Image Object Existence Hallucination, Multi-Image Object Count Hallucination, and Object Identity Consistency Hallucination, targeting semantic understanding across object existence, quantity reasoning, and cross-view identity consistency. Through extensive evaluation, we identify key factors associated with the occurrence of multi-image hallucinations, including: a progressive relationship between the number of image inputs and the likelihood of hallucination occurrences; a strong correlation between single-image hallucination tendencies and those observed in multi-image contexts; and the influence of same-object image ratios and the positional placement of negative samples within image sequences on the occurrence of object identity consistency hallucination. To address these challenges, we propose a Dynamic Attention Balancing mechanism that adjusts inter-image attention distributions while preserving the overall visual attention proportion. Experiments across multiple state-of-the-art MLLMs demonstrate that our method effectively reduces hallucination occurrences and enhances semantic integration and reasoning stability in multi-image scenarios.

[Arxiv](https://arxiv.org/abs/2508.00726)
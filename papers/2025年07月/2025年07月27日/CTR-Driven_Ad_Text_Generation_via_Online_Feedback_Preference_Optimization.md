# 通过在线反馈偏好优化提升点击率的广告文案生成方法

发布时间：2025年07月27日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来生成广告文案，并通过在线反馈优化点击率（CTR）。虽然提到了RAG（检索增强生成）作为方法的一部分，但论文的核心是将LLMs应用于广告文案生成，并通过实际应用证明其有效性。因此，它属于LLM应用类别。` `电子商务`

> CTR-Driven Ad Text Generation via Online Feedback Preference Optimization

# 摘要

> 广告文案对在线广告的点击率 (CTR) 至关重要。与人工创作相比，大型语言模型 (LLMs) 在广告文案生成效率上具有显著优势。然而，LLM 生成的广告文案并不一定比人工创作的文案带来更高的 CTR，这表明广告文案生成质量与实际在线表现之间存在差距。本文提出了一种全新的广告文案生成方法，通过在线反馈的偏好优化来提升 CTR。我们的方法采用了一个创新的两阶段框架：首先，基于单次上下文学习进行多样化广告文案采样，利用检索增强生成 (RAG) 提供具有链式推理 (CoT) 的示例；其次，根据在线反馈进行 CTR 驱动的偏好优化，根据偏好对的 CTR 增益和置信水平进行加权。通过我们的方法，生成的模型能够实现高 CTR 广告文案的端到端生成。大量实验结果证明了我们在离线和在线指标上的有效性。值得注意的是，我们已经在大型在线购物平台上应用了该方法，并取得了显著的 CTR 提升，充分展示了其在广告系统中的强大适用性和有效性。

> Advertising text plays a critical role in determining click-through rates (CTR) in online advertising. Large Language Models (LLMs) offer significant efficiency advantages over manual ad text creation. However, LLM-generated ad texts do not guarantee higher CTR performance compared to human-crafted texts, revealing a gap between generation quality and online performance of ad texts. In this work, we propose a novel ad text generation method which optimizes for CTR through preference optimization from online feedback. Our approach adopts an innovative two-stage framework: (1) diverse ad text sampling via one-shot in-context learning, using retrieval-augmented generation (RAG) to provide exemplars with chain-of-thought (CoT) reasoning; (2) CTR-driven preference optimization from online feedback, which weighs preference pairs according to their CTR gains and confidence levels. Through our method, the resulting model enables end-to-end generation of high-CTR ad texts. Extensive experiments have demonstrated the effectiveness of our method in both offline and online metrics. Notably, we have applied our method on a large-scale online shopping platform and achieved significant CTR improvements, showcasing its strong applicability and effectiveness in advertising systems.

[Arxiv](https://arxiv.org/abs/2507.20227)
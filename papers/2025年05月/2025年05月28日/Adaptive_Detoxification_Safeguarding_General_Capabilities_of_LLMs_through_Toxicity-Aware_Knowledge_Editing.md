# 自适应净化：利用毒性感知知识编辑保障大型语言模型的通用能力

发布时间：2025年05月28日

`LLM理论`

> Adaptive Detoxification: Safeguarding General Capabilities of LLMs through Toxicity-Aware Knowledge Editing

# 摘要

> 大型语言模型（LLMs）虽然展现了强大的语言能力，但仍然容易受到恶意提示和越狱攻击的影响。现有的LLM净化知识编辑方法面临两大挑战：首先，这些方法通常依赖于特定实体的定位，因此在面对没有明确实体的对抗输入时效果不佳；其次，这些方法往往存在过度编辑的问题，导致净化后的模型拒绝合法查询，从而影响整体性能。本文中，我们提出了ToxEdit，这是一种毒性感知的知识编辑方法。它能够在前向传播过程中动态检测有毒激活模式，并通过自适应的层间路径进行计算，从而有效缓解毒性。这种设计不仅能够精准地进行毒性缓解，还能保留LLMs的一般能力。为了更准确地评估过度编辑的问题，我们还通过加入指令遵循评估任务增强了SafeEdit基准。实验结果表明，我们的ToxEdit在多个LLMs上均优于之前最先进的方法，在净化性能和保护LLMs一般能力方面表现尤为突出。

> Large language models (LLMs) exhibit impressive language capabilities but remain vulnerable to malicious prompts and jailbreaking attacks. Existing knowledge editing methods for LLM detoxification face two major challenges. First, they often rely on entity-specific localization, making them ineffective against adversarial inputs without explicit entities. Second, these methods suffer from over-editing, where detoxified models reject legitimate queries, compromising overall performance. In this paper, we propose ToxEdit, a toxicity-aware knowledge editing approach that dynamically detects toxic activation patterns during forward propagation. It then routes computations through adaptive inter-layer pathways to mitigate toxicity effectively. This design ensures precise toxicity mitigation while preserving LLMs' general capabilities. To more accurately assess over-editing, we also enhance the SafeEdit benchmark by incorporating instruction-following evaluation tasks. Experimental results on multiple LLMs demonstrate that our ToxEdit outperforms previous state-of-the-art methods in both detoxification performance and safeguarding general capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2505.22298)
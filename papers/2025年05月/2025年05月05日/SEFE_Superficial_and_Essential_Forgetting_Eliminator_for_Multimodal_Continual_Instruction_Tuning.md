# SEFE：多模态持续指令微调中的表面与本质遗忘消除器

发布时间：2025年05月05日

`LLM应用` `人工智能` `机器学习`

> SEFE: Superficial and Essential Forgetting Eliminator for Multimodal Continual Instruction Tuning

# 摘要

> 多模态持续指令微调（MCIT）旨在使多模态大型语言模型（MLLMs）能够逐步学习新任务，同时避免灾难性遗忘。本文中，我们将遗忘现象分为表层遗忘和深层遗忘两类。表层遗忘指的是模型的知识可能并未真正丢失，但由于后续任务回答风格的影响，模型对先前任务的响应偏离了预期格式，导致结果不可用。相比之下，深层遗忘指的是模型提供了格式正确但事实不准确的回答，这表明知识真正丢失。评估深层遗忘需要首先解决表层遗忘问题，因为严重的表层遗忘可能会掩盖模型的知识状态。因此，我们引入了回答风格多样化（ASD）范式，它定义了一个标准化的数据风格转换过程，将不同任务的训练集统一为多样化风格，从而防止因风格变化导致的表层遗忘。在此基础上，我们提出了RegLoRA来缓解深层遗忘问题。RegLoRA通过正则化稳定存储先前知识的关键参数，使模型能够保留现有能力。实验结果表明，我们的整体方法SEFE达到了最先进的性能水平。

> Multimodal Continual Instruction Tuning (MCIT) aims to enable Multimodal Large Language Models (MLLMs) to incrementally learn new tasks without catastrophic forgetting. In this paper, we explore forgetting in this context, categorizing it into superficial forgetting and essential forgetting. Superficial forgetting refers to cases where the model's knowledge may not be genuinely lost, but its responses to previous tasks deviate from expected formats due to the influence of subsequent tasks' answer styles, making the results unusable. By contrast, essential forgetting refers to situations where the model provides correctly formatted but factually inaccurate answers, indicating a true loss of knowledge. Assessing essential forgetting necessitates addressing superficial forgetting first, as severe superficial forgetting can obscure the model's knowledge state. Hence, we first introduce the Answer Style Diversification (ASD) paradigm, which defines a standardized process for transforming data styles across different tasks, unifying their training sets into similarly diversified styles to prevent superficial forgetting caused by style shifts. Building on this, we propose RegLoRA to mitigate essential forgetting. RegLoRA stabilizes key parameters where prior knowledge is primarily stored by applying regularization, enabling the model to retain existing competencies. Experimental results demonstrate that our overall method, SEFE, achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2505.02486)
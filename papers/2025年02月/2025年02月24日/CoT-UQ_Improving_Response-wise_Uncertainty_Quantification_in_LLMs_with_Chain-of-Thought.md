# CoT-UQ：利用思维链提升LLMs的响应层面不确定性量化能力

发布时间：2025年02月24日

`LLM理论` `人工智能` `推理系统`

> CoT-UQ: Improving Response-wise Uncertainty Quantification in LLMs with Chain-of-Thought

# 摘要

> 大型语言模型（LLMs）在各项任务中表现出色，但在量化生成回复的不确定性方面仍存在挑战。这一问题使得检测虚假信息和确保可靠决策变得困难。现有的LLMs不确定性量化（UQ）方法主要基于提示而非回复，通常需要多次采样，导致计算成本高昂。此外，LLMs在推理过程中表现出过度自信，尤其是在通过推理步骤得出答案时。本研究提出了一种基于回复的UQ框架——CoT-UQ，通过将LLMs的内在推理能力（Chain-of-Thought，CoT）整合到UQ过程中。CoT-UQ通过提取每个推理步骤中的关键词并评估其对最终答案的重要性，捕获推理过程中的关键信息。随后，将这些关键推理信息聚合以生成最终的不确定性估计。我们基于LLaMA Family进行了广泛实验，模型规模从8B到13B，涵盖逻辑和数学推理任务。实验结果表明，CoT-UQ显著优于现有UQ方法，在AUROC方面平均提升了5.9%。代码可在以下地址获取：https://github.com/ZBox1005/CoT-UQ。

> Large language models (LLMs) excel in many tasks but struggle to accurately quantify uncertainty in their generated responses. This limitation makes it challenging to detect misinformation and ensure reliable decision-making. Existing uncertainty quantification (UQ) methods for LLMs are primarily prompt-wise rather than response-wise, often requiring multiple response samples, which incurs high computational costs. Moreover, LLMs have been shown to be overconfident, particularly when using reasoning steps to derive their answers. In this work, we propose CoT-UQ, a response-wise UQ framework that integrates LLMs' inherent reasoning capabilities through Chain-of-Thought (CoT) into the UQ process. CoT-UQ captures critical information during inference by extracting keywords from each reasoning step and assessing their importance to the final answer. This key reasoning information is then aggregated to produce a final uncertainty estimate. We conduct extensive experiments based on LLaMA Family with model sizes varying from 8B to 13B across logical and mathematical reasoning tasks. Experimental results demonstrate that CoT-UQ significantly outperforms existing UQ methods, achieving an average improvement of 5.9% AUROC compared to current UQ methods. The code is available at: https://github.com/ZBox1005/CoT-UQ.

[Arxiv](https://arxiv.org/abs/2502.17214)
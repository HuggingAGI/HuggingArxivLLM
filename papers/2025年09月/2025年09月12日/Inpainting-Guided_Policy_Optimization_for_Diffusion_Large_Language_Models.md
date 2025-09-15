# 图像修复引导的策略优化：面向扩散大型语言模型

发布时间：2025年09月12日

`强化学习` `基础理论`

> Inpainting-Guided Policy Optimization for Diffusion Large Language Models

# 摘要

> 掩码扩散大型语言模型（dLLMs）作为自回归LLMs的新兴替代方案，不仅性能具有竞争力，还支持修复等独特的生成能力。我们探索如何利用修复能力为dLLMs的强化学习（RL）算法设计提供思路。让LLMs与强化学习对齐面临探索难题：奖励信号稀疏，且当模型无法找到正确解时会造成样本浪费。尽管这种低效问题普遍存在于LLMs中，但dLLMs带来了独特机遇——其修复能力可引导探索过程。我们提出了IGPO（修复引导策略优化）——一种在在线采样时策略性插入部分真实推理轨迹的RL框架。与提供完整解不同，修复在保留模型自主生成推理的同时，将探索引向更有潜力的轨迹空间，从而架起了监督微调与强化学习之间的桥梁。我们将IGPO应用于GRPO等基于分组的优化方法——在这些方法中，探索失败会导致优势和梯度归零。IGPO不仅恢复了有意义的梯度，还提升了样本效率。我们还提出对合成重写的简洁轨迹进行监督微调，这些轨迹更符合dLLM的生成模式。结合基于熵的过滤等额外技术，我们的训练方案在GSM8K、Math500和AMC三个数学基准上均取得显著提升，为全注意力掩码dLLMs刷新了最先进性能。

> Masked diffusion large language models (dLLMs) are emerging as promising alternatives to autoregressive LLMs, offering competitive performance while supporting unique generation capabilities such as inpainting. We explore how inpainting can inform RL algorithm design for dLLMs. Aligning LLMs with reinforcement learning faces an exploration challenge: sparse reward signals and sample waste when models fail to discover correct solutions. While this inefficiency affects LLMs broadly, dLLMs offer a distinctive opportunity--their inpainting ability can guide exploration. We introduce IGPO (Inpainting Guided Policy Optimization), an RL framework that strategically inserts partial ground-truth reasoning traces during online sampling. Unlike providing full solutions, inpainting steers exploration toward promising trajectory spaces while preserving self-generated reasoning, bridging supervised fine-tuning and reinforcement learning. We apply IGPO to group-based optimization methods such as GRPO, where exploration failures cause zero advantages and gradients. IGPO restores meaningful gradients while improving sample efficiency. We also propose supervised fine-tuning on synthetically rewritten concise traces that better align with dLLM generation patterns. With additional techniques including entropy-based filtering, our training recipe yields substantial gains across three mathematical benchmarks--GSM8K, Math500, and AMC--achieving new state-of-the-art results for full-attention masked dLLMs.

[Arxiv](https://arxiv.org/abs/2509.10396)
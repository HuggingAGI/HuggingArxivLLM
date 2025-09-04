# 借助长思维链监督微调（Long CoT SFT）提升轻量级小型语言模型（MLLMs）的推理能力

发布时间：2025年09月03日

`LLM应用` `基础理论`

> Empowering Lightweight MLLMs with Reasoning via Long CoT SFT

# 摘要

> 尽管带可验证奖励的强化学习已提升大规模语言模型（LLMs）的推理能力，但对于参数不足70亿的轻量级多模态语言模型（MLLMs），其效果尚未得到充分研究。本文探讨了长思维链（long CoT）数据对提升这类MLLMs推理能力的作用。研究发现，利用长CoT数据进行监督微调（SFT）能显著增强MLLM的推理表现；进一步观察表明，在初始SFT阶段后，MLLMs还可通过后续RL阶段实现性能的额外提升。我们的结论是，基于长CoT数据的SFT阶段是轻量级MLLMs推理能力开发的关键前提。

> While Reinforcement Learning with Verifiable Rewards has enhanced the reasoning of large-scale language models (LLMs), its efficacy for lightweight multimodal language models (MLLMs) with fewer than seven billion parameters remains underexplored. This paper investigates the role of long Chain-of-Thought (long CoT) data in enhancing the reasoning abilities of such MLLMs. Our findings demonstrate that Supervised Fine-Tuning (SFT) with long CoT data significantly improves MLLM reasoning. Furthermore, we observe that after this initial SFT phase, MLLMs can achieve additional performance gains through a subsequent RL stage. We conclude that a SFT stage with long CoT data is a critical prerequisite for developing the reasoning capabilities of lightweight MLLMs.

[Arxiv](https://arxiv.org/abs/2509.03321)
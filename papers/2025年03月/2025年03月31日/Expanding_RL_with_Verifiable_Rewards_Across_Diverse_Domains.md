# 强化学习的可验证奖励机制在多样化领域的拓展

发布时间：2025年03月31日

`LLM应用` `跨领域应用`

> Expanding RL with Verifiable Rewards Across Diverse Domains

# 摘要

> 可验证奖励强化学习（RLVR）在数学推理和编程任务中表现出色，但在更广泛领域的应用潜力尚未被充分挖掘。本研究探索将RLVR扩展至医学、化学、心理学和经济学等多样化领域。我们发现，当存在客观参考答案时，不同大型语言模型（LLMs）在二元判断上高度一致，这表明大规模标注可能并非训练领域特定奖励模型的必要条件。为解决二元奖励在处理非结构化参考答案时的局限性，我们引入基于模型的软评分机制，提升RLVR的灵活性。实验结果表明，蒸馏后的生成式奖励模型可作为跨领域验证器，在无需领域特定标注的情况下为强化学习提供可靠奖励信号。通过对基础7B模型进行微调，并结合多种强化学习算法对抗我们的奖励模型，我们在自由形式回答设置下，跨领域获得了显著超越当前先进的开源对齐LLMs（如Qwen2.5-72B-Instruct和DeepSeek-R1-Distill-Qwen-32B）的策略。这不仅增强了RLVR的鲁棒性和可扩展性，也凸显了其在现实世界中处理噪声或弱标签任务的潜力。

> Reinforcement learning (RL) with verifiable rewards (RLVR) has shown promising results in mathematical reasoning and coding tasks where well-structured reference answers are available. However, its applicability to broader domains remains underexplored. In this work, we study the extension of RLVR to more diverse domains such as medicine, chemistry, psychology, and economics. We observe high agreement in binary judgments across different large language models (LLMs) when objective reference answers exist, which challenges the necessity of large-scale annotation for training domain-specific reward models. To address the limitations of binary rewards when handling unstructured reference answers, we further incorporate model-based soft scoring into RLVR to improve its flexibility. Our experiments show that a distilled generative reward model can serve as an effective cross-domain verifier, providing reliable reward signals for RL without requiring domain-specific annotations. By fine-tuning a base 7B model using various RL algorithms against our reward model, we obtain policies that outperform state-of-the-art open-source aligned LLMs such as Qwen2.5-72B-Instruct and DeepSeek-R1-Distill-Qwen-32B by a large margin, across domains in free-form answer settings. This also strengthens RLVR's robustness and scalability, highlighting its potential for real-world applications with noisy or weak labels.

[Arxiv](https://arxiv.org/abs/2503.23829)
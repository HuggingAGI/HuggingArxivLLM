# SEED-GRPO：语义熵增强的GRPO，用于不确定性感知的策略优化方法

发布时间：2025年05月18日

`LLM理论` `数学推理`

> SEED-GRPO: Semantic Entropy Enhanced GRPO for Uncertainty-Aware Policy Optimization

# 摘要

> 大型语言模型（LLMs）在处理不同输入提示时表现出不同的置信水平：有些提示能生成一致且语义相似的回答，而有些则会导致多样或矛盾的输出。这种差异反映了LLMs对输入提示的不确定性，这是模型对特定问题理解信心的重要信号。然而，传统的组相对策略优化（GRPO）在策略更新过程中将所有提示一视同仁，忽视了模型知识边界的重要信息。为了解决这一局限性，我们提出了SEED-GRPO（语义熵增强型GRPO），该方法明确测量LLMs对输入提示的语义熵不确定性。语义熵衡量了在给定提示下多个生成答案的意义多样性，并利用这一点来调节策略更新的幅度。这种感知不确定性的训练机制使政策更新幅度能够根据问题的不确定性进行动态调整。对于高不确定性问题，它允许更保守的更新，同时保持对高信心问题的原始学习信号。在五个数学推理基准测试（AIME24 56.7，AMC 68.7，MATH 83.4，Minerva 34.2和OlympiadBench 48.0）上的实验结果表明，SEED-GRPO在平均准确率上达到了新的最先进性能，验证了感知不确定性策略优化的有效性。

> Large language models (LLMs) exhibit varying levels of confidence across input prompts (questions): some lead to consistent, semantically similar answers, while others yield diverse or contradictory outputs. This variation reflects LLM's uncertainty about the input prompt, a signal of how confidently the model understands a given problem. However, vanilla Group Relative Policy Optimization (GRPO) treats all prompts equally during policy updates, ignoring this important information about the model's knowledge boundaries. To address this limitation, we propose SEED-GRPO (Semantic Entropy EnhanceD GRPO), which explicitly measures LLMs' uncertainty of the input prompts semantic entropy. Semantic entropy measures the diversity of meaning in multiple generated answers given a prompt and uses this to modulate the magnitude of policy updates. This uncertainty-aware training mechanism enables dynamic adjustment of policy update magnitudes based on question uncertainty. It allows more conservative updates on high-uncertainty questions while maintaining the original learning signal on confident ones. Experimental results on five mathematical reasoning benchmarks (AIME24 56.7, AMC 68.7, MATH 83.4, Minerva 34.2, and OlympiadBench 48.0) demonstrate that SEED-GRPO achieves new state-of-the-art performance in average accuracy, validating the effectiveness of uncertainty-aware policy optimization.

[Arxiv](https://arxiv.org/abs/2505.12346)
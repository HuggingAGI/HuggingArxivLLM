# 回溯未来：基于概率推理的可控语言生成方法

发布时间：2025年04月25日

`LLM应用` `生成控制` `属性管理`

> TRACE Back from the Future: A Probabilistic Reasoning Approach to Controllable Language Generation

# 摘要

> 大型语言模型（LMs）的快速发展带来了对输出控制的需求，以确保其符合人类价值观（如去毒化）或特定属性（如个性化、主题）。然而，自回归模型专注于下一个词的预测，在处理需要展望未来的全局属性时表现不佳。现有的解决方案要么通过微调或后训练LM来适应每个新属性，这种方式成本高昂且缺乏灵活性；要么通过采样或训练来近似未来序列的预期属性概率（EAP），但对于罕见属性，这种方法既缓慢又不可靠。我们提出了TRACE（可适应可控生成的 tractable 概率推理），一个创新框架，通过 tractable 概率推理和轻量级控制，高效计算EAP并适应新属性。TRACE从LM中蒸馏出一个隐马尔可夫模型（HMM），并结合一个小分类器来估计属性概率，从而实现对HMM预测未来的精确EAP计算。随后，利用此EAP重新加权LM的下一个词概率，以生成全局合规的文本。实证结果表明，TRACE在去毒化任务中达到了最先进的水平，仅增加10%的解码开销。它还能在几秒钟内适应76个低资源个性化LLMs，并无缝扩展到复合属性。

> As large language models (LMs) advance, there is an increasing need to control their outputs to align with human values (e.g., detoxification) or desired attributes (e.g., personalization, topic). However, autoregressive models focus on next-token predictions and struggle with global properties that require looking ahead. Existing solutions either tune or post-train LMs for each new attribute - expensive and inflexible - or approximate the Expected Attribute Probability (EAP) of future sequences by sampling or training, which is slow and unreliable for rare attributes. We introduce TRACE (Tractable Probabilistic Reasoning for Adaptable Controllable gEneration), a novel framework that efficiently computes EAP and adapts to new attributes through tractable probabilistic reasoning and lightweight control. TRACE distills a Hidden Markov Model (HMM) from an LM and pairs it with a small classifier to estimate attribute probabilities, enabling exact EAP computation over the HMM's predicted futures. This EAP is then used to reweigh the LM's next-token probabilities for globally compliant continuations. Empirically, TRACE achieves state-of-the-art results in detoxification with only 10% decoding overhead, adapts to 76 low-resource personalized LLMs within seconds, and seamlessly extends to composite attributes.

[Arxiv](https://arxiv.org/abs/2504.18535)
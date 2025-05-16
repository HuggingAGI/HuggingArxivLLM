# PIG：基于梯度迭代上下文优化的 LLM 隐私越狱攻击

发布时间：2025年05月14日

`LLM理论` `隐私保护` `人工智能`

> PIG: Privacy Jailbreak Attack on LLMs via Gradient-based Iterative In-Context Optimization

# 摘要

> 大型语言模型 (LLMs) 在多个领域表现出色，但同时也带来了固有的隐私风险。现有用于评估 LLMs 隐私泄露的方法通常采用记忆前缀或简单指令来提取数据，这两种方法均容易被具有良好对齐性的模型拦截。同时，Jailbreak 攻击能够绕过 LLM 的安全机制生成有害内容，但其在隐私场景中的作用仍未得到充分探索。本文研究了 Jailbreak 攻击在提取敏感信息方面的有效性，将隐私泄露与 LLMs 中的 Jailbreak 攻击联系起来。此外，我们提出了 PIG，一个针对个人身份信息 (PII) 的新框架，旨在解决当前 Jailbreak 方法的局限性。具体而言，PIG 在隐私查询中识别 PII 实体及其类型，利用上下文学习构建隐私上下文，并通过三种基于梯度的策略迭代更新该上下文以提取目标 PII。我们使用两个与隐私相关的数据集评估了 PIG 和现有的 Jailbreak 方法。在四个白盒和两个黑盒 LLM 上的实验表明，PIG 在性能上优于基线方法，并达到了当前最优 (SoTA) 结果。实验结果突显了 LLMs 中存在的重大隐私风险，强调了加强隐私保护的必要性。我们的代码可在 \href{https://github.com/redwyd/PrivacyJailbreak}{https://github.com/redwyd/PrivacyJailbreak} 获取。

> Large Language Models (LLMs) excel in various domains but pose inherent privacy risks. Existing methods to evaluate privacy leakage in LLMs often use memorized prefixes or simple instructions to extract data, both of which well-alignment models can easily block. Meanwhile, Jailbreak attacks bypass LLM safety mechanisms to generate harmful content, but their role in privacy scenarios remains underexplored. In this paper, we examine the effectiveness of jailbreak attacks in extracting sensitive information, bridging privacy leakage and jailbreak attacks in LLMs. Moreover, we propose PIG, a novel framework targeting Personally Identifiable Information (PII) and addressing the limitations of current jailbreak methods. Specifically, PIG identifies PII entities and their types in privacy queries, uses in-context learning to build a privacy context, and iteratively updates it with three gradient-based strategies to elicit target PII. We evaluate PIG and existing jailbreak methods using two privacy-related datasets. Experiments on four white-box and two black-box LLMs show that PIG outperforms baseline methods and achieves state-of-the-art (SoTA) results. The results underscore significant privacy risks in LLMs, emphasizing the need for stronger safeguards. Our code is availble at \href{https://github.com/redwyd/PrivacyJailbreak}{https://github.com/redwyd/PrivacyJailbreak}.

[Arxiv](https://arxiv.org/abs/2505.09921)
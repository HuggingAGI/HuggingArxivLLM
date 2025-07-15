# AICrypto：评估大型语言模型密码学能力的全面基准测试

发布时间：2025年07月13日

`LLM应用` `密码学` `网络安全`

> AICrypto: A Comprehensive Benchmark For Evaluating Cryptography Capabilities of Large Language Models

# 摘要

> 大型语言模型（LLMs）在多个领域展现了卓越的能力，然而在密码学这一网络安全基石领域的应用仍鲜有探索。为填补这一空白，我们提出了	extbf{AICrypto}，这是首个全面评估LLMs密码能力的基准测试。该基准包含135道选择题、150个CTF挑战和18个证明问题，涵盖从事实记忆到漏洞利用和形式推理的多种技能。所有任务均由密码学专家精心审核或构建，以确保准确性和严谨性。为支持CTF挑战的自动化评估，我们设计了一个基于代理的框架。为了深入了解当前LLMs在密码学方面的掌握程度，我们引入了人类专家表现基线，以便在所有任务类型中进行比较。我们对17个领先LLMs的评估表明，当前先进的模型不仅达到了人类专家的水平，甚至在某些方面超越了他们，尤其是在记忆密码学概念、利用常见漏洞和常规证明方面。然而，它们仍缺乏对抽象数学概念的深刻理解，在需要多步推理和动态分析的任务上表现吃力。我们希望这项工作能为未来在密码学应用中研究LLMs提供启发。我们的代码和数据集可在https://aicryptobench.github.io获取。

> Large language models (LLMs) have demonstrated remarkable capabilities across a variety of domains. However, their applications in cryptography, which serves as a foundational pillar of cybersecurity, remain largely unexplored. To address this gap, we propose \textbf{AICrypto}, the first comprehensive benchmark designed to evaluate the cryptographic capabilities of LLMs. The benchmark comprises 135 multiple-choice questions, 150 capture-the-flag (CTF) challenges, and 18 proof problems, covering a broad range of skills from factual memorization to vulnerability exploitation and formal reasoning. All tasks are carefully reviewed or constructed by cryptography experts to ensure correctness and rigor. To support automated evaluation of CTF challenges, we design an agent-based framework. To gain deeper insight into the current state of cryptographic proficiency in LLMs, we introduce human expert performance baselines for comparison across all task types. Our evaluation of 17 leading LLMs reveals that state-of-the-art models match or even surpass human experts in memorizing cryptographic concepts, exploiting common vulnerabilities, and routine proofs. However, they still lack a deep understanding of abstract mathematical concepts and struggle with tasks that require multi-step reasoning and dynamic analysis. We hope this work could provide insights for future research on LLMs in cryptographic applications. Our code and dataset are available at https://aicryptobench.github.io.

[Arxiv](https://arxiv.org/abs/2507.09580)
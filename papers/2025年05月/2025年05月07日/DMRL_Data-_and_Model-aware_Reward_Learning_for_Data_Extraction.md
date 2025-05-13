# DMRL：面向数据抽取的模型与数据双感知奖励学习

发布时间：2025年05月07日

`LLM应用` `信息安全` `人工智能`

> DMRL: Data- and Model-aware Reward Learning for Data Extraction

# 摘要

> 大型语言模型（LLMs）在设计上就容易遭受意外的隐私泄露。因此，系统性的红队研究对于开发稳健的防御机制至关重要。然而，当前的数据提取方法存在几个局限性：（1）依赖于数据集的重复（可通过去重解决），（2）依赖于提示工程（已被检测和防御手段所应对），以及（3）依赖于随机搜索的对抗生成。为了解决这些挑战，我们提出了DMRL（数据与模型感知的奖励学习方法），用于数据提取。该技术利用逆向强化学习从LLMs中提取敏感数据。我们的方法包括两个主要部分：（1）构建一个内省推理数据集，捕捉泄露思维模式，以指导模型行为；（2）使用组相对策略优化（GRPO）训练奖励模型，在数据和模型层面动态调整优化，根据任务难度进行调整。在多种LLMs上的全面实验表明，DMRL在数据提取性能上优于所有基线方法。


> Large language models (LLMs) are inherently vulnerable to unintended privacy breaches. Consequently, systematic red-teaming research is essential for developing robust defense mechanisms. However, current data extraction methods suffer from several limitations: (1) rely on dataset duplicates (addressable via deduplication), (2) depend on prompt engineering (now countered by detection and defense), and (3) rely on random-search adversarial generation. To address these challenges, we propose DMRL, a Data- and Model-aware Reward Learning approach for data extraction. This technique leverages inverse reinforcement learning to extract sensitive data from LLMs. Our method consists of two main components: (1) constructing an introspective reasoning dataset that captures leakage mindsets to guide model behavior, and (2) training reward models with Group Relative Policy Optimization (GRPO), dynamically tuning optimization based on task difficulty at both the data and model levels. Comprehensive experiments across various LLMs demonstrate that DMRL outperforms all baseline methods in data extraction performance.

[Arxiv](https://arxiv.org/abs/2505.06284)
# 面向多编程语言理解的基于组等价偏好的策略优化方法

发布时间：2025年05月19日

`LLM应用` `软件开发`

> On-Policy Optimization with Group Equivalent Preference for Multi-Programming Language Understanding

# 摘要

> 大型语言模型（LLMs）在代码生成任务中表现优异，但广泛使用的编程语言（如Python、C++）与其他语言之间仍存在显著性能差异。为解决这一问题，我们利用代码翻译任务训练LLMs，促进跨语言的编码能力迁移。同时，我们提出了一种结合在线策略和离线策略的新型强化学习框架OORL。在OORL框架中，代码翻译过程中采用在线策略RL，其奖励信号由基于单元测试的规则生成。为补充这一规则奖励，我们提出了组等价偏好优化（GEPO），一种新颖的偏好优化方法。具体来说，GEPO通过中间表示（IRs）组来训练LLMs，使其能够识别与源代码等价的IRs，并利用组内IRs之间的相互等价性信号，从而捕捉代码功能的细微差别。通过结合OORL框架和代码翻译任务训练LLMs，模型能够更好地理解代码功能及其跨语言实现的关系。实验结果表明，我们的方法在多种编程语言的代码基准测试中取得了显著性能提升。

> Large language models (LLMs) achieve remarkable performance in code generation tasks. However, a significant performance disparity persists between popular programming languages (e.g., Python, C++) and others. To address this capability gap, we leverage the code translation task to train LLMs, thereby facilitating the transfer of coding proficiency across diverse programming languages. Moreover, we introduce OORL for training, a novel reinforcement learning (RL) framework that integrates on-policy and off-policy strategies. Within OORL, on-policy RL is applied during code translation, guided by a rule-based reward signal derived from unit tests. Complementing this coarse-grained rule-based reward, we propose Group Equivalent Preference Optimization (GEPO), a novel preference optimization method. Specifically, GEPO trains the LLM using intermediate representations (IRs) groups. LLMs can be guided to discern IRs equivalent to the source code from inequivalent ones, while also utilizing signals about the mutual equivalence between IRs within the group. This process allows LLMs to capture nuanced aspects of code functionality. By employing OORL for training with code translation tasks, LLMs improve their recognition of code functionality and their understanding of the relationships between code implemented in different languages. Extensive experiments demonstrate that our OORL for LLMs training with code translation tasks achieves significant performance improvements on code benchmarks across multiple programming languages.

[Arxiv](https://arxiv.org/abs/2505.12723)
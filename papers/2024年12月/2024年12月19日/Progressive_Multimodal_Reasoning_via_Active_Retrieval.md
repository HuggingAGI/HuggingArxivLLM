# 通过主动检索实现的渐进式多模态推理

发布时间：2024年12月19日

`LLM应用` `多模态推理` `语言模型`

> Progressive Multimodal Reasoning via Active Retrieval

# 摘要

> 多步多模态推理任务给多模态大型语言模型（MLLMs）带来巨大挑战，如何在这种情形下有效提升其性能仍是未解难题。在本文中，我们提出了 AR-MCTS 这一通用框架，旨在借助主动检索（AR）和蒙特卡罗树搜索（MCTS）逐步增强 MLLMs 的推理能力。我们的方法先开发出统一的检索模块，从混合模态检索语料库中获取解决复杂推理问题的关键支持性见解。为填补自动多模态推理验证的空缺，我们采用 MCTS 算法与主动检索机制相结合，能够自动生成逐步注释。此策略为每个推理步骤动态获取关键见解，突破传统波束搜索采样，提升推理空间的多样性和可靠性。另外，我们引入一个过程奖励模型，逐步适配以支持多模态推理任务的自动验证。在三个复杂的多模态推理基准测试中的实验结果证实了 AR-MCTS 框架对提升各类多模态模型性能的有效性。进一步分析表明，AR-MCTS 能够优化采样的多样性和准确性，实现可靠的多模态推理。

> Multi-step multimodal reasoning tasks pose significant challenges for multimodal large language models (MLLMs), and finding effective ways to enhance their performance in such scenarios remains an unresolved issue. In this paper, we propose AR-MCTS, a universal framework designed to progressively improve the reasoning capabilities of MLLMs through Active Retrieval (AR) and Monte Carlo Tree Search (MCTS). Our approach begins with the development of a unified retrieval module that retrieves key supporting insights for solving complex reasoning problems from a hybrid-modal retrieval corpus. To bridge the gap in automated multimodal reasoning verification, we employ the MCTS algorithm combined with an active retrieval mechanism, which enables the automatic generation of step-wise annotations. This strategy dynamically retrieves key insights for each reasoning step, moving beyond traditional beam search sampling to improve the diversity and reliability of the reasoning space. Additionally, we introduce a process reward model that aligns progressively to support the automatic verification of multimodal reasoning tasks. Experimental results across three complex multimodal reasoning benchmarks confirm the effectiveness of the AR-MCTS framework in enhancing the performance of various multimodal models. Further analysis demonstrates that AR-MCTS can optimize sampling diversity and accuracy, yielding reliable multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2412.14835)
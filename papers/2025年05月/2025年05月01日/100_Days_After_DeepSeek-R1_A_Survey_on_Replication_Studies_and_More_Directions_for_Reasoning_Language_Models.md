# DeepSeek-R1发布百日之后：复现研究的回顾与展望，以及推理语言模型的未来发展

发布时间：2025年05月01日

`LLM理论` `模型复现` `语言模型`

> 100 Days After DeepSeek-R1: A Survey on Replication Studies and More Directions for Reasoning Language Models

# 摘要

> 推理语言模型（RLMs）的最新发展标志着大型语言模型的一次重要演进。DeepSeek-R1的发布不仅引发了广泛关注，更激发了研究界对语言模型显式推理范式的探索热情。然而，DeepSeek尚未完全开源其模型的实现细节，包括DeepSeek-R1-Zero、DeepSeek-R1以及蒸馏后的轻量级模型。因此，许多研究团队致力于复现DeepSeek-R1的强劲表现，通过相似的训练流程和完全开源的数据资源达到了可比的性能水平。这些研究重点探究了监督微调（SFT）和基于可验证奖励的强化学习（RLVR）的可行策略，聚焦于数据准备和方法设计，取得了诸多宝贵见解。

本报告旨在总结近期的复现研究，为未来研究提供启发。我们主要聚焦于SFT和RLVR两大方向，详细介绍现有复现研究在数据构建、方法设计和训练流程方面的细节。此外，我们从这些研究的实现细节和实验结果中总结关键发现，期望能为未来研究提供启发。我们还探讨了提升RLMs的附加技术，强调了扩大这些模型应用范围的潜力，并讨论了开发过程中面临的挑战。通过这项调研，我们力求帮助RLMs的研究者和开发者紧跟最新进展，并激发新的思路以进一步提升RLMs的能力。

> The recent development of reasoning language models (RLMs) represents a novel evolution in large language models. In particular, the recent release of DeepSeek-R1 has generated widespread social impact and sparked enthusiasm in the research community for exploring the explicit reasoning paradigm of language models. However, the implementation details of the released models have not been fully open-sourced by DeepSeek, including DeepSeek-R1-Zero, DeepSeek-R1, and the distilled small models. As a result, many replication studies have emerged aiming to reproduce the strong performance achieved by DeepSeek-R1, reaching comparable performance through similar training procedures and fully open-source data resources. These works have investigated feasible strategies for supervised fine-tuning (SFT) and reinforcement learning from verifiable rewards (RLVR), focusing on data preparation and method design, yielding various valuable insights. In this report, we provide a summary of recent replication studies to inspire future research. We primarily focus on SFT and RLVR as two main directions, introducing the details for data construction, method design and training procedure of current replication studies. Moreover, we conclude key findings from the implementation details and experimental results reported by these studies, anticipating to inspire future research. We also discuss additional techniques of enhancing RLMs, highlighting the potential of expanding the application scope of these models, and discussing the challenges in development. By this survey, we aim to help researchers and developers of RLMs stay updated with the latest advancements, and seek to inspire new ideas to further enhance RLMs.

[Arxiv](https://arxiv.org/abs/2505.00551)
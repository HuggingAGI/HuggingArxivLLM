# 重新审视大型语言模型推理：信息瓶颈方法的应用

发布时间：2025年07月24日

`LLM理论` `人工智能` `数学推理`

> Revisiting LLM Reasoning via Information Bottleneck

# 摘要

> 大型语言模型（LLMs）在基于可验证奖励的强化学习（RLVR）中展现出了推理能力的显著进步。借助简单规则的奖励机制，强化学习（RL）成功激励LLMs生成扩展的思维链（CoT）推理轨迹，逐步引导它们走向正确答案。然而，现有方法仍主要依赖启发式和直觉驱动，限制了基于原理的方法的发展。本文中，我们基于信息瓶颈（IB）原理，对LLM推理进行了理论上的刻画，提出了IB感知的推理优化（IBRO）框架，旨在鼓励推理轨迹既对最终正确答案具有信息量，又能在多样化的提示中具备可推广性。我们推导出一个实用的token级替代目标，并提出了一种高效的近似方法，从而形成了轻量级的IB正则化技术。该方法能够无缝集成到现有的基于RL的后训练框架中，无需额外的计算开销，仅需一行代码修改。实验上，我们在多个数学推理基准测试和RL算法中验证了IB正则化的效果，结果表明其在提升LLM推理性能方面具有显著且一致的改进。

> Large language models (LLMs) have recently demonstrated remarkable progress in reasoning capabilities through reinforcement learning with verifiable rewards (RLVR). By leveraging simple rule-based rewards, RL effectively incentivizes LLMs to produce extended chain-of-thought (CoT) reasoning trajectories, progressively guiding them toward correct answers. However, existing approaches remain largely heuristic and intuition-driven, limiting the development of principled methodologies. In this paper, we present a theoretical characterization of LLM reasoning grounded in information bottleneck (IB) principle, introducing IB-aware reasoning optimization (IBRO), a framework that encourages reasoning trajectories to be both informative about the final correct answer and generalizable across diverse prompts. We derive a practical token-level surrogate objective and propose an efficient approximation, resulting in the lightweight IB regularization method. This technique integrates seamlessly into existing RL-based post-training frameworks without additional computational overhead, requiring only a one-line code modification. Empirically, we validate IB regularization across multiple mathematical reasoning benchmarks and RL algorithms, demonstrating consistent improvements in LLM reasoning performance.

[Arxiv](https://arxiv.org/abs/2507.18391)
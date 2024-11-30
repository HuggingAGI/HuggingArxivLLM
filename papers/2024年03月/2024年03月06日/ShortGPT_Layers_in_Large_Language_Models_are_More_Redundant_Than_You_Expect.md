# ShortGPT 揭示，大型语言模型内部的层级存在超乎预期的冗余现象。

发布时间：2024年03月06日

`LLM理论`

> ShortGPT: Layers in Large Language Models are More Redundant Than You Expect

# 摘要

> 随着LLMs性能突飞猛进，其规模已跃升至数十亿甚至数万亿参数级别。但研究表明，LLMs内部多层结构高度相似，部分层级对整体网络功能贡献甚微。为此，我们创新性地提出了“块影响”(BI)这一评估指标，旨在精确衡量LLMs中各层的重要性。进而，我们提议采用一种直观易行的剪枝策略——“层删除”，依据各层BI得分，直接剔除LLMs中的冗余层。实验证明，我们的ShortGPT方法在模型剪枝领域大幅超越了现有的最优水平，并且它与量化等压缩手段相辅相成，能有效缩减参数及计算负担。简而言之，相较于复杂的剪枝技术，仅通过简单移除冗余层就可取得更优效果，揭示了模型架构中潜在的高度冗余特性。

> As Large Language Models (LLMs) continue to advance in performance, their size has escalated significantly, with current LLMs containing billions or even trillions of parameters. However, in this study, we discovered that many layers of LLMs exhibit high similarity, and some layers play a negligible role in network functionality. Based on this observation, we define a metric called Block Influence (BI) to gauge the significance of each layer in LLMs. We then propose a straightforward pruning approach: layer removal, in which we directly delete the redundant layers in LLMs based on their BI scores. Experiments demonstrate that our method, which we call ShortGPT, significantly outperforms previous state-of-the-art (SOTA) methods in model pruning. Moreover, ShortGPT is orthogonal to quantization-like methods, enabling further reduction in parameters and computation. The ability to achieve better results through simple layer removal, as opposed to more complex pruning techniques, suggests a high degree of redundancy in the model architecture.

[Arxiv](https://arxiv.org/abs/2403.03853)
# 主动层对比解码方法有效降低大规模语言模型生成中的幻觉现象

发布时间：2025年05月29日

`LLM理论

理由：这篇论文探讨了改进大型语言模型（LLM）生成过程中解码策略的方法，提出了一种新的解码策略（ActLCD），结合强化学习和奖励感知分类器来优化生成过程，减少幻觉现象。研究属于模型改进和生成机制优化，因此归类为LLM理论。` `模型优化`

> Active Layer-Contrastive Decoding Reduces Hallucination in Large Language Model Generation

# 摘要

> 近期，改进的解码方法通过优化生成过程中下一标记的选择方式，显著提升了大型语言模型（LLMs）的事实准确性。这些方法通常在标记级别操作，利用内部表示来抑制表层模式。然而，LLMs仍然容易出现幻觉，尤其是在处理较长上下文时。本文中，我们提出了一种新型解码策略——主动层对比解码（ActLCD），该策略能够在生成过程中主动决定何时应用对比层。通过将解码视为一个顺序决策问题，ActLCD采用强化学习策略，由奖励感知分类器引导，以超越标记级别优化事实准确性。实验结果表明，ActLCD在五个基准测试中超越了现有最先进的方法，充分展示了其在各种生成场景中有效缓解幻觉的能力。

> Recent decoding methods improve the factuality of large language models~(LLMs) by refining how the next token is selected during generation. These methods typically operate at the token level, leveraging internal representations to suppress superficial patterns. Nevertheless, LLMs remain prone to hallucinations, especially over longer contexts. In this paper, we propose Active Layer-Contrastive Decoding (ActLCD), a novel decoding strategy that actively decides when to apply contrasting layers during generation. By casting decoding as a sequential decision-making problem, ActLCD employs a reinforcement learning policy guided by a reward-aware classifier to optimize factuality beyond the token level. Our experiments demonstrate that ActLCD surpasses state-of-the-art methods across five benchmarks, showcasing its effectiveness in mitigating hallucinations in diverse generation scenarios.

[Arxiv](https://arxiv.org/abs/2505.23657)
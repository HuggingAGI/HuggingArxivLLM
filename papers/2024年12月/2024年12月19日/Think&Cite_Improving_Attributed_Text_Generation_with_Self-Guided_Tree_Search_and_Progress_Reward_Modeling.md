# Think&Cite：通过自引导树搜索和进度奖励建模提升归因文本生成

发布时间：2024年12月19日

`LLM应用` `文本生成`

> Think&Cite: Improving Attributed Text Generation with Self-Guided Tree Search and Progress Reward Modeling

# 摘要

> 尽管大型语言模型（LLMs）能力出众，但容易产生幻觉和生成错误信息。这一难题促使人们致力于有属性文本生成，促使 LLMs 生成有支撑证据的内容。在本文中，我们提出一个新颖的框架——Think&Cite，将有属性文本生成构建为与搜索相结合的多步推理问题。具体来说，我们提出了自引导蒙特卡罗树搜索（SG-MCTS），借助 LLMs 的自我反思能力来反思 MCTS 的中间状态，从而指导树扩展过程。为提供可靠且全面的反馈，我们引入进度奖励模型，从生成和归因进度两方面衡量从根节点到当前状态的树搜索进度。我们在三个数据集上开展了大量实验，结果显示我们的方法显著优于基线方法。

> Despite their outstanding capabilities, large language models (LLMs) are prone to hallucination and producing factually incorrect information. This challenge has spurred efforts in attributed text generation, which prompts LLMs to generate content with supporting evidence. In this paper, we propose a novel framework, called Think&Cite, and formulate attributed text generation as a multi-step reasoning problem integrated with search. Specifically, we propose Self-Guided Monte Carlo Tree Search (SG-MCTS), which capitalizes on the self-reflection capability of LLMs to reflect on the intermediate states of MCTS for guiding the tree expansion process. To provide reliable and comprehensive feedback, we introduce Progress Reward Models to measure the progress of tree search from the root to the current state from two aspects, i.e., generation and attribution progress. We conduct extensive experiments on three datasets and the results show that our approach significantly outperforms baseline approaches.

[Arxiv](https://arxiv.org/abs/2412.14860)
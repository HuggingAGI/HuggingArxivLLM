# TurnaboutLLM：基于侦探游戏的演绎推理基准

发布时间：2025年05月21日

`LLM应用`

> TurnaboutLLM: A Deductive Reasoning Benchmark from Detective Games

# 摘要

> 本文提出了一种新颖的框架和数据集——TurnaboutLLM，它通过利用侦探游戏《Ace Attorney》和《Danganronpa》的互动 gameplay 来评估大型语言模型（LLMs）的演绎推理能力。该框架要求 LLMs 在长篇叙述语境中识别证词与证据之间的矛盾，这一任务极具挑战性，因为其问题涉及广阔的答案空间和多样的推理类型。我们对十二个最先进的 LLMs 在该数据集上进行了评估，结果揭示了增强演绎推理的流行策略（如广泛的思考和链式思维提示）的局限性。此外，实验结果表明，上下文大小、推理步骤数量和答案空间大小对模型性能的影响各不相同。总体而言，TurnaboutLLM 为评估 LLMs 在复杂、叙事丰富的环境中的演绎推理能力提供了一个极具挑战性的基准。

> This paper introduces TurnaboutLLM, a novel framework and dataset for evaluating the deductive reasoning abilities of Large Language Models (LLMs) by leveraging the interactive gameplay of detective games Ace Attorney and Danganronpa. The framework tasks LLMs with identifying contradictions between testimonies and evidences within long narrative contexts, a challenging task due to the large answer space and diverse reasoning types presented by its questions. We evaluate twelve state-of-the-art LLMs on the dataset, hinting at limitations of popular strategies for enhancing deductive reasoning such as extensive thinking and Chain-of-Thought prompting. The results also suggest varying effects of context size, the number of reasoning step and answer space size on model performance. Overall, TurnaboutLLM presents a substantial challenge for LLMs' deductive reasoning abilities in complex, narrative-rich environments.

[Arxiv](https://arxiv.org/abs/2505.15712)
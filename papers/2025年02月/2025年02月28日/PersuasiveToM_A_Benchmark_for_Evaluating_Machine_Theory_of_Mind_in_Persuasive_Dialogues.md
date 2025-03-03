# PersuasiveToM：用于评测有说服力对话中机器心智理论的基准

发布时间：2025年02月28日

`LLM应用

这篇论文探讨了大型语言模型在心智理论（ToM）任务中的应用，特别是评估其在劝说性对话中的能力。通过提出PersuasiveToM基准测试，研究者旨在评估模型在复杂心理活动中的表现，属于LLM应用的范畴。` `人工智能` `社交智能`

> PersuasiveToM: A Benchmark for Evaluating Machine Theory of Mind in Persuasive Dialogues

# 摘要

> 理解并预测自己和他人心理状态的能力，即心智理论（ToM），对于有效的人际互动至关重要。最近的研究开始评估大型语言模型（LLMs）是否具备某种心智理论能力。尽管近期研究已经评估了LLMs的心智理论，但现有的基准测试主要集中在物理感知上，其指导原则来源于合成故事和对话中的莎莉-安测试，未能捕捉到真实社交互动中心理状态的复杂心理活动。

为了弥补这一差距，我们提出了PersuasiveToM，一个旨在评估LLMs在劝说性对话中心智理论能力的基准测试。我们的框架引入了两类问题：（1）ToM推理，评估LLMs跟踪心理状态演变的能力（例如说服对象的需求变化）；（2）ToM应用，评估LLMs是否能够利用推断出的心理状态选择有效的劝说策略（例如强调稀有性）并评估劝说策略的有效性。

针对八种最先进的LLMs进行的实验表明，尽管模型在多个问题上表现出色，但它们难以回答需要跟踪心理状态动态变化和全面理解整个对话中心理状态的问题。我们的目标是通过PersuasiveToM实现对LLMs心智推理能力的有效评估，更加关注复杂的心理活动。我们的代码可在https://github.com/Yu-Fangxu/PersuasiveToM获取。

> The ability to understand and predict the mental states of oneself and others, known as the Theory of Mind (ToM), is crucial for effective social interactions. Recent research has emerged to evaluate whether Large Language Models (LLMs) exhibit a form of ToM. Although recent studies have evaluated ToM in LLMs, existing benchmarks focus predominantly on physical perception with principles guided by the Sally-Anne test in synthetic stories and conversations, failing to capture the complex psychological activities of mental states in real-life social interactions. To mitigate this gap, we propose PersuasiveToM, a benchmark designed to evaluate the ToM abilities of LLMs in persuasive dialogues. Our framework introduces two categories of questions: (1) ToM Reasoning, assessing the capacity of LLMs to track evolving mental states (e.g., desire shifts in persuadees), and (2) ToM Application, evaluating whether LLMs can take advantage of inferred mental states to select effective persuasion strategies (e.g., emphasize rarity) and evaluate the effectiveness of persuasion strategies. Experiments across eight state-of-the-art LLMs reveal that while models excel on multiple questions, they struggle to answer questions that need tracking the dynamics and shifts of mental states and understanding the mental states in the whole dialogue comprehensively. Our aim with PersuasiveToM is to allow an effective evaluation of the ToM reasoning ability of LLMs with more focus on complex psychological activities. Our code is available at https://github.com/Yu-Fangxu/PersuasiveToM.

[Arxiv](https://arxiv.org/abs/2502.21017)
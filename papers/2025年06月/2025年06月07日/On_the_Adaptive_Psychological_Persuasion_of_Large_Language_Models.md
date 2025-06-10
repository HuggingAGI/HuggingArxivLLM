# # 探索大型语言模型的自适应心理劝说

发布时间：2025年06月07日

`LLM应用` `心理劝说` `对话系统`

> On the Adaptive Psychological Persuasion of Large Language Models

# 摘要

> 大型语言模型（LLMs）在遵循指令和修辞流畅性方面展现出了令人惊叹的能力，但它们在自主劝说和抵抗劝说方面的双重潜力，尤其是在心理修辞领域，尚未得到系统性探索。本文首先通过让四个常用LLMs在对抗性对话中轮流扮演劝说者和倾听者，评估其劝说能力。实证结果表明，作为劝说者的LLMs主要依赖重复策略，导致成功率较低。随后，我们提出了十一项全面的心理劝说策略，发现明确指示LLMs采用特定策略（如流畅效果和重复效果）能显著提升劝说成功率。然而，没有一种“万能”策略能在所有情境中都有效，其表现受情境反事实因素的显著影响。基于这些观察，我们提出了一种基于直接偏好优化的自适应框架，通过分析特定策略响应的劝说结果，训练LLMs自主选择最优策略。实验结果表明，我们的自适应心理劝说方法能够显著提升劝说者LLMs的成功率，同时保持其一般能力。我们的代码已在GitHub上开源，地址为https://github.com/KalinaEine/PsychologicalPersuasion。

> Previous work has showcased the intriguing capabilities of Large Language Models (LLMs) in instruction-following and rhetorical fluency. However, systematic exploration of their dual capabilities to autonomously persuade and resist persuasion, particularly in contexts involving psychological rhetoric, remains unexplored. In this paper, we first evaluate four commonly adopted LLMs by tasking them to alternately act as persuaders and listeners in adversarial dialogues. Empirical results show that persuader LLMs predominantly employ repetitive strategies, leading to low success rates. Then we introduce eleven comprehensive psychological persuasion strategies, finding that explicitly instructing LLMs to adopt specific strategies such as Fluency Effect and Repetition Effect significantly improves persuasion success rates. However, no ``one-size-fits-all'' strategy proves universally effective, with performance heavily dependent on contextual counterfactuals. Motivated by these observations, we propose an adaptive framework based on direct preference optimization that trains LLMs to autonomously select optimal strategies by leveraging persuasion results from strategy-specific responses as preference pairs. Experiments on three open-source LLMs confirm that the proposed adaptive psychological persuasion method effectively enables persuader LLMs to select optimal strategies, significantly enhancing their success rates while maintaining general capabilities. Our code is available at https://github.com/KalinaEine/PsychologicalPersuasion.

[Arxiv](https://arxiv.org/abs/2506.06800)
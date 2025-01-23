# 利用AI反馈优化对话系统，提升整体对话体验

发布时间：2025年01月22日

`LLM应用

解释：这篇论文主要讨论了如何利用大型语言模型（LLMs）和基于AI反馈的强化学习（RLAIF）来优化对话系统的响应，以提升用户与系统互动时的参与度。论文中提到的技术和方法都是围绕LLM的应用展开的，特别是如何通过监督微调和奖励模型来调整对话模型，从而改善对话系统的表现。因此，这篇论文应被分类为LLM应用。` `对话系统` `人工智能`

> Training Dialogue Systems by AI Feedback for Improving Overall Dialogue Impression

# 摘要

> 为了提升用户与对话系统互动时的参与度，我们不仅需要优化单个对话响应，还需提升整个对话的连贯性、个性化和同理心等印象。尽管大型语言模型（LLMs）推动了对话系统的快速发展，但基于AI反馈的强化学习（RLAIF）正成为调整LLM对话模型以实现这些印象的关键技术。在RLAIF中，我们利用另一个LLM构建的奖励模型，通过零-shot/少-shot提示技术为对话模型生成训练信号。然而，仅依赖LLMs提示来评估整个对话仍具挑战。为此，我们通过监督微调（SFT）LLMs，构建了与12个对话印象指标相关的奖励模型，用于评估对话响应。通过将奖励模型信号作为反馈调整对话模型，我们成功提升了系统的整体印象。自动和人工评估结果显示，使用与对话印象对应的奖励模型调整对话模型，显著改善了个别指标的评估结果和对话响应的自然流畅度。

> To improve user engagement during conversations with dialogue systems, we must improve individual dialogue responses and dialogue impressions such as consistency, personality, and empathy throughout the entire dialogue. While such dialogue systems have been developing rapidly with the help of large language models (LLMs), reinforcement learning from AI feedback (RLAIF) has attracted attention to align LLM-based dialogue models for such dialogue impressions. In RLAIF, a reward model based on another LLM is used to create a training signal for an LLM-based dialogue model using zero-shot/few-shot prompting techniques. However, evaluating an entire dialogue only by prompting LLMs is challenging. In this study, the supervised fine-tuning (SFT) of LLMs prepared reward models corresponding to 12 metrics related to the impression of the entire dialogue for evaluating dialogue responses. We tuned our dialogue models using the reward model signals as feedback to improve the impression of the system. The results of automatic and human evaluations showed that tuning the dialogue model using our reward model corresponding to dialogue impression improved the evaluation of individual metrics and the naturalness of the dialogue response.

[Arxiv](https://arxiv.org/abs/2501.12698)
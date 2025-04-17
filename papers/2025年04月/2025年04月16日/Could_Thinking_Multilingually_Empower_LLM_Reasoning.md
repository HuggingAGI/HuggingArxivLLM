# 多语言思维能否为LLM推理注入更强能力？

发布时间：2025年04月16日

`LLM应用` `多语言模型`

> Could Thinking Multilingually Empower LLM Reasoning?

# 摘要

> 先前研究指出，大型语言模型存在显著的“英语偏好”，即在以英语呈现任务时，模型通常表现更佳。然而，我们发现有趣的现象：使用某些其他语言进行推理任务时，性能甚至可能超越英语。尽管如此，这一现象尚未得到充分研究。本文探讨了在推理任务中运用多语言能力的上限，揭示多语言推理不仅在准确率（Acc@k）上比单语种推理高出近10个百分点，且在面对翻译质量波动和语言选择变化时更具鲁棒性。除了剖析这一上限的成因及其实现挑战外，我们还发现，现有的答案选择方法受限于其固有缺陷和偏见，难以触及这一上限。这些发现为未来研究提供了方向，旨在充分挖掘大型语言模型中多语言推理的潜力。

> Previous work indicates that large language models exhibit a significant "English bias", i.e. they often perform better when tasks are presented in English. Interestingly, we have observed that using certain other languages in reasoning tasks can yield better performance than English. However, this phenomenon remains under-explored. In this paper, we explore the upper bound of harnessing multilingualism in reasoning tasks, suggesting that multilingual reasoning promises significantly (by nearly 10 Acc@$k$ points) and robustly (tolerance for variations in translation quality and language choice) higher upper bounds than English-only reasoning. Besides analyzing the reason behind the upper bound and challenges in reaching it, we also find that common answer selection methods cannot achieve this upper bound, due to their limitations and biases. These insights could pave the way for future research aimed at fully harnessing the potential of multilingual reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2504.11833)
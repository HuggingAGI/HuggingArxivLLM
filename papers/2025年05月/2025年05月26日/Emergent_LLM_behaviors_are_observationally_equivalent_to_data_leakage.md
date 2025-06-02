# 大型语言模型中新出现的行为，在观察效果上与数据泄露无异。

发布时间：2025年05月26日

`LLM理论` `社会科学` `认知科学`

> Emergent LLM behaviors are observationally equivalent to data leakage

# 摘要

> Ashery 等人最近提出，大型语言模型（LLMs）在进行经典的“命名游戏”时，会自发形成类似人类社会规范的语言习惯，这被认为是模型的“涌现”现象。然而，作者们通过分析指出，这些结果其实可以用数据泄漏来更好地解释：模型只是再现了他们在预训练过程中已经见过的惯例。尽管原作者采取了一些缓解措施，但通过多个分析，作者们证明，LLMs 其实是识别了协调游戏的结构并回忆其结果，而不是表现出“涌现”的惯例。因此，观察到的行为与训练语料的记忆行为无法区分。最后，作者们提出了潜在的替代策略，并更广泛地反思了LLMs在社会科学模型中的位置。

> Ashery et al. recently argue that large language models (LLMs), when paired to play a classic "naming game," spontaneously develop linguistic conventions reminiscent of human social norms. Here, we show that their results are better explained by data leakage: the models simply reproduce conventions they already encountered during pre-training. Despite the authors' mitigation measures, we provide multiple analyses demonstrating that the LLMs recognize the structure of the coordination game and recall its outcomes, rather than exhibit "emergent" conventions. Consequently, the observed behaviors are indistinguishable from memorization of the training corpus. We conclude by pointing to potential alternative strategies and reflecting more generally on the place of LLMs for social science models.

[Arxiv](https://arxiv.org/abs/2505.23796)
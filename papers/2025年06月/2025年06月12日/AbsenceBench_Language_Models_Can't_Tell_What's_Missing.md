# AbsenceBench：语言模型难以察觉缺失之处

发布时间：2025年06月12日

`LLM应用` `数值序列` `软件开发`

> AbsenceBench: Language Models Can't Tell What's Missing

# 摘要

> 大型语言模型（LLMs）在处理长输入和定位关键信息方面的能力日益增强，这一点在“针在稻草堆中”（NIAH）测试中得到了充分体现。然而，尽管模型在捕捉令人意外的信息上表现出色，但在识别明显缺失的信息时仍显不足。为此，我们推出了AbsenceBench，旨在评估LLMs在三个领域中检测缺失信息的能力：数值序列、诗歌和GitHub拉取请求。AbsenceBench要求模型在同时查看原始和编辑后上下文的情况下，找出文档中被刻意移除的部分。尽管这些任务看似简单，但实验结果表明，即便是Claude-3.7-Sonnet这样先进的模型，在平均上下文长度仅为5K tokens的情况下，其F1分数也只有69.6%。我们的分析揭示，这种表现不佳源于一个根本性限制：Transformer注意力机制难以关注到文档中的“空白”，因为这些缺失并不对应任何特定的可关注键。总的来说，我们的研究结果和分析提供了一个典型案例，展示了模型在某些任务中已经超越人类（如NIAH）而在其他任务中却意外失效（如AbsenceBench）的接近性。

> Large language models (LLMs) are increasingly capable of processing long inputs and locating specific information within them, as evidenced by their performance on the Needle in a Haystack (NIAH) test. However, while models excel at recalling surprising information, they still struggle to identify clearly omitted information. We introduce AbsenceBench to assesses LLMs' capacity to detect missing information across three domains: numerical sequences, poetry, and GitHub pull requests. AbsenceBench asks models to identify which pieces of a document were deliberately removed, given access to both the original and edited contexts. Despite the apparent straightforwardness of these tasks, our experiments reveal that even state-of-the-art models like Claude-3.7-Sonnet achieve only 69.6% F1-score with a modest average context length of 5K tokens. Our analysis suggests this poor performance stems from a fundamental limitation: Transformer attention mechanisms cannot easily attend to "gaps" in documents since these absences don't correspond to any specific keys that can be attended to. Overall, our results and analysis provide a case study of the close proximity of tasks where models are already superhuman (NIAH) and tasks where models breakdown unexpectedly (AbsenceBench).

[Arxiv](https://arxiv.org/abs/2506.11440)